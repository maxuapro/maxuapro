<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
      color: aliceblue;
    }

    body {
      background-color: rgb(30, 51, 58);
    }

    .impoblock {
      margin: 0 auto;
      margin: 20px;
      padding: 20px;
      border: 4px solid;
      /* border-radius: 30px; */
      border-image: linear-gradient(#ea3cf6, #0c369f) 30;
      border-radius: 50em;
      text-align: center;
    }

    .bulletpoints {
      /* width: 100%; */
      margin: 20px;
      margin-left: 40px;
    }

    .flexrow {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
    }

    .pill {
      padding: 7px;
      padding-left: 14px;
      padding-right: 14px;
      border: 2px solid aliceblue;
      margin: 5px;
      background-image: linear-gradient(to bottom, #274776, #8f1d93);
      border-radius: 50px;
    }
  </style>
  
  <div class="bulletpoints">
    <h1>Maxuapro 😎</h1><span>the official Github page</span>
  </div>

  <div class="impoblock">
    <p>
      Hello there, I'm Max aka Maxuapro.
    </p>
    <br>
    <p>
      Really glad to see you here on my Github page! Why? Because to me it means two things: 1. You actually checked
      this
      page and we have something to talk about. Now go carefully through my repos and remember everything you saw,
      because
      I'be asking about them on our interview... and 2. You are very likely here to offer me a cooperation of a kind,
      which is always good news for me )
    </p>
  </div>

  <div class="bulletpoints">
    <p>
      Here are technologies that I LOVE to work with:
    </p>
    <br>
    <div class="flexrow">
      <div class="pill">JavaScript</div>
      <div class="pill">React</div>
      <div class="pill">Remix</div>
      <div class="pill">Python</div>
      <div class="pill">FastAPI</div>
      <div class="pill">MongoDB</div>
      <div class="pill">Firebase</div>
    </div>
    <br>
    <p>
      Here are technologies that I CAN work with:
    </p>
    <br>
    <div class="flexrow">
      <div class="pill">Node.js</div>
      <div class="pill">Nest.js</div>
      <div class="pill">Next.js</div>
    </div>
  </div>

  <div class="impoblock">
    <p>
      - Okay, Max! you would say now. What we can do together?
    </p>
    <br>
    <p>
      - Good question! I can work with you on your project, or you can work with me on my project!
    </p>
  </div>
</body>

</html>
