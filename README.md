<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Układ Okresowy Aplikacji</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #e0f0ff;
      margin: 0;
      padding: 20px;
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 30px;
      max-width: 12000px;
      margin: 0 auto;
    }

    .element {
      background-color: #ffffff;
      border-radius: 10px;
      padding: 10px;
      text-align: center;
      text-decoration: none;
      color: black;
      transition: transform 0.2s;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    .element:hover {
      transform: scale(1.05);
    }

    .element img {
      width: 40px;
      height: 40px;
      margin-bottom: 5px;
    }

    .element span {
      display: block;
      font-size: 13px;
      margin-top: 4px;
    }

    /* Kategorie */
    .quiz { background-color: #d6e9ff; }
    .interaktywne { background-color: #d4edda; }
    .prezentacja { background-color: #fff3cd; }
    .komunikacja { background-color: #f8d7da; }
    .inne { background-color: #e2e3e5; }
	
	
	button {
  padding: 8px 12px;
  margin: 0 5px 10px;
  border: none;
  border-radius: 5px;
  background-color: #007bff;
  color: white;
  cursor: pointer;
  font-size: 14px;
}

button:hover {
  background-color: #0056b3;
}
  </style>
</head>
<body>

  <h1>Układ Okresowy Aplikacji</h1>
    
	
	
	<div style="text-align: center; margin-bottom: 20px;">
  <button onclick="filterApps('all')">Wszystko</button>
  <button onclick="filterApps('testy')">Quizy</button>
  <button onclick="filterApps('interaktywne')">Interaktywne</button>
  <button onclick="filterApps('mapy')">Prezentacje</button>
  <button onclick="filterApps('komunikacja')">Komunikacja</button>
  <button onclick="filterApps('inne')">Inne</button>
</div>


  <div class="grid">

<!-- Testy i quizy (niebieski) -->
<a href="https://quizizz.com" class="element testy" target="_blank">
  <img src="https://quizizz.com/favicon.ico" alt="Quizizz">
  <span>Quizizz</span>
</a>

<a href="https://www.plickers.com" class="element testy" target="_blank">
  <img src="https://www.plickers.com/favicon.ico" alt="Plickers">
  <span>Plickers</span>
</a>

<a href="https://kahoot.com" class="element testy" target="_blank">
  <img src="https://kahoot.com/files/2020/11/Kahoot-1024-rounded.png" alt="Kahoot!">
  <span>Kahoot!</span>
</a>

<a href="https://www.testportal.com" class="element testy" target="_blank">
  <img src="https://a.storyblok.com/f/120497/2400x1254/bb7255f9dc/testportal.png" alt="Testportal">
  <span>Testportal</span>
</a>

<a href="https://www.socrative.com" class="element testy" target="_blank">
  <img src="https://educraft.tech/wp-content/uploads/2020/11/socrative-logo.jpg" alt="Socrative">
  <span>Socrative</span>
</a>

<a href="https://wordwall.net" class="element testy" target="_blank">
  <img src="https://wordwall.net/favicon.ico" alt="Wordwall">
  <span>Wordwall</span>
</a>

<a href="https://www.bamboozle.com" class="element testy" target="_blank">
  <img src="https://cdn.mos.cms.futurecdn.net/ZwHoBHiHJmHmNngfJvovXJ.jpeg" alt="Bamboozle">
  <span>Bamboozle</span>
</a>

<a href="https://quizlet.com" class="element testy" target="_blank">
  <img src="https://quizlet.com/favicon.ico" alt="Quizlet">
  <span>Quizlet</span>
</a>

<a href="https://quizalize.com" class="element testy" target="_blank">
  <img src="https://quizalize.com/favicon.ico" alt="Quizalize">
  <span>Quizalize</span>
</a>

<a href="https://www.tricider.com" class="element testy" target="_blank">
  <img src="https://www.tricider.com/favicon.ico" alt="Tricider">
  <span>Tricider</span>
</a>

<a href="https://quizshow.com" class="element testy" target="_blank">
  <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple112/v4/21/32/b3/2132b37e-2485-3578-f88e-985af6f257d0/AppIcon-0-0-1x_U007emarketing-0-0-0-7-0-0-sRGB-0-0-0-GLES2_U002c0-512MB-85-220-0-0.png/1200x630wa.png" alt="Quizshow">
  <span>Quizshow</span>
</a>

<a href="https://wheeldecide.com" class="element testy" target="_blank">
  <img src="https://wheeldecide.com/favicon.ico" alt="Wheel Decide">
  <span>Wheel Decide</span>
</a>

<!-- Interaktywne gry i aktywności (różowy) -->
<a href="https://learningapps.org" class="element interaktywne" target="_blank">
  <img src="https://learningapps.org/favicon.ico" alt="LearningApps.org">
  <span>LearningApps.org</span>
</a>

<a href="https://nearpod.com" class="element interaktywne" target="_blank">
  <img src="https://nearpod.com/favicon.ico" alt="Nearpod">
  <span>Nearpod</span>
</a>

<a href="https://www.voki.com" class="element interaktywne" target="_blank">
  <img src="https://www.voki.com/favicon.ico" alt="Voki">
  <span>Voki</span>
</a>

<a href="https://classtools.net" class="element interaktywne" target="_blank">
  <img src="https://classtools.net/favicon.ico" alt="ClassTools">
  <span>ClassTools</span>
</a>

<a href="https://edpuzzle.com" class="element interaktywne" target="_blank">
  <img src="https://play-lh.googleusercontent.com/MACIkVCNnNsPS-E-VAjIguH9IDUM_1xtvBu016EAzcshxYXJKM4B6a8r36EYgqASOh8" alt="Edupuzzle">
  <span>Edupuzzle</span>
</a>

<a href="https://www.liveworksheets.com" class="element interaktywne" target="_blank">
  <img src="https://www.liveworksheets.com/sites/default/files/2025-01/mstile-1200x630.png" alt="Liveworksheets">
  <span>Liveworksheets</span>
</a>

<a href="https://wizer.me" class="element interaktywne" target="_blank">
  <img src="https://wizer.me/favicon.ico" alt="Wizer.me">
  <span>Wizer.me</span>
</a>

<!-- Prezentacje (zielony) -->
<a href="https://genial.ly" class="element prezentacje" target="_blank">
  <img src="https://yt3.googleusercontent.com/4FvPZe4YtxAlPgZe_VxZdJURmvuyJ0RbqA57q1rArA-S4DV9eY7zgqsJhjpKvHMjTX3PUPdg=s900-c-k-c0x00ffffff-no-rj" alt="Genially">
  <span>Genially</span>
</a>

<a href="https://prezi.com" class="element prezentacje" target="_blank">
  <img src="https://prezi.com/favicon.ico" alt="Prezi">
  <span>Prezi</span>
</a>

<a href="https://www.emaze.com" class="element prezentacje" target="_blank">
  <img src="https://www.emaze.com/favicon.ico" alt="Emaze">
  <span>Emaze</span>
</a>

<a href="https://www.canva.com" class="element prezentacje" target="_blank">
  <img src="https://www.canva.com/favicon.ico" alt="Canva">
  <span>Canva</span>
</a>

<!-- Mapy myśli / informacja zwrotna (fioletowy) -->
<a href="https://www.mindmeister.com" class="element mapy" target="_blank">
  <img src="https://play-lh.googleusercontent.com/rYz25b_qg2gm3e5A9Z_tFqqDeDr7-uQOe_0oO1KrZ2Eqm4GKmc0TpZe3sTj3ZB8ROgk" alt="Mindmeister">
  <span>Mindmeister</span>
</a>

<a href="https://www.mindmup.com" class="element mapy" target="_blank">
  <img src="https://store-images.s-microsoft.com/image/apps.35150.fc18773b-db2e-45a1-ae84-328f624350e7.eb99fb23-fa02-4771-8302-d5974fa03521.22f263a1-7089-423f-9d81-a286a9117786.png" alt="MindMup">
  <span>MindMup</span>
</a>

<a href="https://www.mentimeter.com" class="element mapy" target="_blank">
  <img src="https://www.mentimeter.com/favicon.ico" alt="Mentimeter">
  <span>Mentimeter</span>
</a>

<a href="https://coggle.it" class="element mapy" target="_blank">
  <img src="https://coggle.it/favicon.ico" alt="Coggle">
  <span>Coggle</span>
</a>

<a href="https://answergarden.ch" class="element mapy" target="_blank">
  <img src="https://answergarden.ch/favicon.ico" alt="AnswerGarden">
  <span>AnswerGarden</span>
</a>

<a href="https://padlet.com" class="element mapy" target="_blank">
  <img src="https://padlet.com/favicon.ico" alt="Padlet">
  <span>Padlet</span>
</a>

<!-- Rozszerzona rzeczywistość (jasnofioletowy) -->
<a href="https://cospaces.io" class="element rozszerzona" target="_blank">
  <img src="https://play-lh.googleusercontent.com/aN2kZU-TaRu0ZT5_XUnElDpmQg6YtjDsrE5DJqbu3W-KMiI9k19thatdQ-d6A5HcskA=w240-h480-rw" alt="CoSpaces">
  <span>CoSpaces</span>
</a>

<a href="https://edu.google.com/expeditions" class="element rozszerzona" target="_blank">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEYktXPLW7vYaUGUQe3K8zHszq24szifFoGg&s" alt="Google Expeditions">
  <span>Google Expeditions</span>
</a>

<a href="https://www.3dbear.io" class="element rozszerzona" target="_blank">
  <img src="https://www.3dbear.io/favicon.ico" alt="3DBear">
  <span>3DBear</span>
</a>

<!-- Białe tablice (granatowy) -->
<a href="https://jamboard.google.com" class="element tablice" target="_blank">
  <img src="https://img.utdstc.com/icon/752/b67/752b67a8dd9456831db10b7f0b4ecf19534a9c159ee5ecd0d1ae3402a8e03f5a:200" alt="Jamboard">
  <span>Jamboard</span>
</a>

<a href="https://whiteboard.fi" class="element tablice" target="_blank">
  <img src="https://whiteboard.fi/favicon.ico" alt="Whiteboard.fi">
  <span>Whiteboard.fi</span>
</a>

<!-- Komunikacja (żółty) -->
<a href="https://www.classdojo.com" class="element komunikacja" target="_blank">
  <img src="https://www.classdojo.com/favicon.ico" alt="ClassDojo">
  <span>ClassDojo</span>
</a>

<a href="https://www.microsoft.com/en-us/microsoft-teams" class="element komunikacja" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Microsoft_Office_Teams_%282018%E2%80%93present%29.svg/1200px-Microsoft_Office_Teams_%282018%E2%80%93present%29.svg.png" alt="Microsoft Teams">
  <span>Microsoft Teams</span>
</a>

<a href="https://www.remind.com" class="element komunikacja" target="_blank">
  <img src="https://3.files.edl.io/4a65/20/09/03/130515-5e053d47-f6c3-4519-b52a-58283a355c22.png" alt="Remind">
  <span>Remind</span>
</a>

<a href="https://www.edmodo.com" class="element komunikacja" target="_blank">
  <img src="https://cdn.elearningindustry.com/wp-content/uploads/2018/01/512dcfa8738cd56c546a9f00356d358f.jpeg" alt="Edmodo">
  <span>Edmodo</span>
</a>

<!-- Karty pracy (pomarańczowy) -->
<a href="https://web.seesaw.me" class="element karty" target="_blank">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS1H6oFuFN6KLhU8Iz7tbhAaqyn1Jv37fw_oQ&s" alt="Seesaw">
  <span>Seesaw</span>
</a>

<a href="https://www.explaineverything.com" class="element karty" target="_blank">
  <img src="https://play-lh.googleusercontent.com/9_GOad-DlDSp_22IsSRullGVEHt_hA1_333_LJfTjsmzwaX5WHWRB0D2n3Q_pw_6lw" alt="Explain Everything">
  <span>Explain Everything</span>
</a>

<a href="https://www.kamiapp.com" class="element karty" target="_blank">
  <img src="https://www.kamiapp.com/favicon.ico" alt="Kami">
  <span>Kami</span>
</a>

<!-- Przechowywanie (niebieskawy) -->
<a href="https://wakelet.com" class="element przechowywanie" target="_blank">
  <img src="https://superbelfrzy.edu.pl/wp-content/uploads/2020/06/unnamed.png" alt="Wakelet">
  <span>Wakelet</span>
</a>

<a href="https://drive.google.com" class="element przechowywanie" target="_blank">
  <img src="https://drive.google.com/favicon.ico" alt="Google Drive">
  <span>Google Drive</span>
</a>

<!-- Inne (szary) -->
<a href="https://www.pinterest.com" class="element inne" target="_blank">
  <img src="https://www.pinterest.com/favicon.ico" alt="Pinterest">
  <span>Pinterest</span>
</a>

<a href="https://www.thinklink.com" class="element inne" target="_blank">
  <img src="https://www.thinklink.com/favicon.ico" alt="Thinklink">
  <span>Thinklink</span>
</a>

<a href="https://www.classroomscreen.com" class="element inne" target="_blank">
  <img src="https://www.classroomscreen.com/favicon.ico" alt="Classroomscreen">
  <span>Classroomscreen</span>
</a>


<a href="https://www.ahaslides.com" class="element inne" target="_blank">
  <img src="https://www.ahaslides.com/favicon.ico" alt="AhaSlides">
  <span>AhaSlides</span>
</a>

  
  

<script>
  function filterApps(category) {
    const elements = document.querySelectorAll('.element');

    elements.forEach(el => {
      if (category === 'all') {
        el.style.display = 'flex';
      } else {
        if (el.classList.contains(category)) {
          el.style.display = 'flex';
        } else {
          el.style.display = 'none';
        }
      }
    });
  }
</script>

</body>
</html>
