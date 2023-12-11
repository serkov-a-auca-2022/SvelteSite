<!DOCTYPE html>
<!-- svelte-ignore a11y-missing-attribute -->
<html>
<head>
  <link rel="stylesheet" href="style.css">
  <title>Porsche 911 Turbo S</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
</head>
<body>
  <header>
    <div id="logo">
        <img class="LogoPorsche" src="img/PorscheLogo.jpg" height="50px" alt="Porsche Logo">
    </div>
    <div class="burger-menu" onclick="toggleMenu()">
      <div></div>
      <div></div>
      <div></div>
  </div>
        <div class="menu">
        <div class="menu-items">
        <a class="menu-item" href="#Title">Home</a>
        <a class="menu-item" href="#designer">Designer</a>
        <a class="menu-item" href="#location">Production</a>
        <a class="menu-item" href="#owners">Owners</a>
        <a class="menu-item" href="USP">USP</a>
      </div>
      </div>
    <div id="Title" class="title">
    </div>    
  </header>
  <div class="hero">
    <div class="hero-content">
      <h2>Experience Power and Elegance</h2>
      <button><a href="https://configurator.porsche.com/en-US/model/992450" target="_blank">Explore Now</a></button>
    </div>
  </div>  
  <main>
    <section class="intro-section">
      <h1>Porsche 911 Turbo S</h1>
            <p class="intro">The Porsche 911 was first unveiled to the public on 12 September 1963 when it was launched at the Frankfurt International Motor Show. Full production of the car began a year later in September 1964 at the Porsche factory in Zuffenhausen.</p>
      <p class="info"><span>The 2022 Porsche 911 Turbo and Turbo S is powered by a 3.7-liter twin-turbocharged flat-six engine that generates up to 640 horsepower in powerful variants and 572 horsepower in the regular Turbo model. All-wheel drive is standard, and the shifts are taken care of by an eight-speed dual-clutch automatic transmission.</span></p>
    </section>

    <section class="image-section">
      <img src="img/Porsche911S.jpg" alt="Porsche 911 is one of the most beautiful cars in the world!" width="450" height="auto" />
      <img src="img/porsche911TURBOS.jpg" alt="Porsche 911 is one of the most beautiful cars in the world!" width="450" height="auto" />
    </section>

    <section class="choice-section">
      <h2>Why Should I Choose Porsche?</h2>
      
      <div class="choice">
        <div class="choice-item">
          <div class="choice-content">
            <h3>Style</h3>
            <p>Porsche's style represents the beauty of German cars. Each element is perfectly matched for the exact combination of style and elegance. The development of the design of this machine has been going on for more than 60 years.</p>
          </div>
          <img src="img/PorscheStyle.jpg" alt="Porsche Style">
        </div>
      </div>

      <div class="choice reverse">
        <div class="choice-item" id="reversed">
          <img src="img/PorscheStatus.jpg" alt="Porsche Status">
          <div class="choice-content">
            <h3>Status</h3>
            <p>Driving a Porsche comes with a unique status and lifestyle. Unusual, but at the same time simple design, gives the owner of this car seriousness and self-confidence.</p>
          </div>
        </div>
      </div>
      
      <div class="choice">
        <div class="choice-item">
          <div class="choice-content">
            <h3>Dynamic</h3>
            <p>Experience incredible speed and performance with Porsche. 0-100 km/h in just 2.6 seconds. Let people spend millions of dollars on Bugatti, but Bugatti owners will never know what a real start is. Porsche is ready to compete with the fastest cars in the world for its modest price.</p>
          </div>
          <img src="img/PorscheDynamic.jpg" alt="Porsche Dynamic">
        </div>
      </div>      
    </section>

    <section id="designer" class="designer-section"> 
      <h2> Who designed the Porsche 911?</h2>
      <p class="design"> The first-ever Porsche 911 was designed by F.A. Porsche – son of the founder of the company, Ferry Porsche – and his team. The original 911 had an air-cooled flat-six engine instead of the four-cylinder boxer engine of the 356. It developed 130PS, could accelerate from 0-100km/h in 9.1 seconds and had a top speed of 210km/h. These were hugely impressive figures for a production sportscar at the time.</p>
      <img src="img/First911.jpg" alt="It was the first model of this legendary car!">
      <p class="design"> Many great Porsche designers have been involved in updating and evolving the 911 over the decades. They include such legendary figures as Anatole Lapine, who designed the G series, the successor to the original 911, and Harm Lagaay. This Dutchman was chief designer at Porsche from 1989 to 2004 and was the man who, among many other highlights, introduced the much talked about ‘fried egg’ headlights on the 911 (type 996). And, since 2004, it's been Michael Mauer who has overseen the design of the 911 in his role as Head of Style Porsche.</p>
      <p class="design"> These days you can choose a Porsche 911 to fit a wide range of lifestyles, like the new 911 Dakar, the first standard off-road model in the series, or the fastest production car in the current 911 line-up, the 911 Turbo S. Or, as Ferry Porsche once famously said, “The 911 is the only car that you can drive from an African safari to Le Mans, then to the theatre and onto the streets of New York.”</p>  
      <a class="Home" href="#Title">Home</a>
    </section>

    <section id="location" class="location-section"> 
      <h5> Where is the Porsche 911 built?</h5>
      <p class="design">The Porsche 911 is only built at Zuffenhausen, Germany, the headquarters of Dr. Ing. h.c. F. Porsche AG. It’s exactly the same factory complex, in fact, where the first-ever 911 rolled off the line back when full-scale production began in 1964, a year after its Frankfurt International Motor Show launch. Every new 911 that has ever been built since has been made at Zuffenhausen.</p>
      <img src="img/PorscheProducted.jpg" alt="The Porsche 911 is only built at Zuffenhausen">
      <p><a class="Home" href="#Title">Home</a></p>
    </section>

    <section class="image-text-section">
      <div class="image-text-block">
        <img src="img/logotype.jpg" alt="Porsche logotype" width="350" height="100%">
        <div class="text-block">
          <h3>Logotype</h3>
          <p>The horse represents strength, the red and black stripes on either side are reflective of the traditional crest colors of Württemberg-Hohenzollern.</p>
        </div>
      </div>
      <div class="image-text-block">
        <img src="img/porschelogo2.jpg" alt="Porsche Logotype" width="350" height="100%">
        <div class="text-block">
          <h3>History</h3>
          <p>For the design of the Porsche logo, Franz drew inspiration from Stuttgart's city seal, which features a rearing horse, and incorporated this into the center of the shield shape.</p>
        </div>
      </div>
    </section>

    <section id="owners" class="owners-section"> 
      <h6> Who are famous Porsche 911 owners?</h6>
      <p class="design">Many of the biggest names in music, sport, film, and television have owned a Porsche 911. Famous people to own a Porsche 911 include rapper Eminem, model Kendall Jenner, footballer David Beckham, fashion designer Ralph Lauren, pop star Harry Styles, and actor, racing driver, and Porsche brand ambassador, Patrick Dempsey.
        <img src="img/PorscheFamousOwners.jpg" alt="Porsche famous owners">
        <p class="design">One of the most famous personal Porsche collections belongs to comedian and actor Jerry Seinfeld, who owns one of the biggest and most impressive Porsche line-ups – including several 911 sports cars – in the world. He admits that the day he first bought a 911 (20 January 1988) will be etched on his memory for life. Oh, he bought a black 911 Carrera, by the way.</p>
        <p><a class="Home" href="#Title">Home</a></p>
    </section>
    
  </main>
  <script type="text/javascript">
    window.onbeforeunload = function () {
      window.scrollTo(0, 0);
    }
  </script>

  <script>
    function toggle() {
      if (document.getElementById("panel").style.display == "block") {
        document.getElementById("panel").style.display = "none"
      } else {
        document.getElementById("panel").style.display = "block"
      }      
    }
  </script>
</body>
</html>

<style>
body {
    background-color:white ;
    background-size: cover;
    margin: 0px;
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.5;
    margin: 0 auto;
  }
  header {
    background-color: black;
    color: white;
    padding: 10px;
    display: flex;
    gap: 100px;
    font-size: 25px;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }
  
  
  .menu-items {
    display: flex; 
    padding: 0px 20px;
    gap: 20px; 
  }
  
  .menu-item {
    text-decoration: none;
    color: #fff;
    font-size: 16px;
    position: relative;
  }
  

  .burger-menu {
    display: none;
    cursor: pointer;
  }
  
  .burger-menu div {
    width: 30px;
    height: 3px;
    background-color: white;
    margin: 6px 0;
    transition: 0.4s;
  }
  
  .menu {
    display: flex;
    gap: 100px;
  }
  
  .menu-items {
    display: flex;
    gap: 20px;
  }
  
  @media only screen and (max-width: 768px) {
    .burger-menu {
        display: block;
    }
  
    .menu {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 60px;
        left: 0;
        width: 100%;
        background-color: black;
        padding: 20px;
    }
  
    .menu.show {
        display: flex;
    }
  }
  
  .Home {
    font-size: 30px;
  }
  
  .title {
    margin: 0;
    font-size: 30px;
    text-align: center;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 0px;
  }
  
  a {
    text-decoration: none;
  }
  
  main {
    padding: 0px;
    text-align: center;
  }
  
  h1 {
    margin: 0;
    color: white;
  }
  
  .intro {
    margin-top: 20px;
    font-size: 30px;
  }
  
  .info {
    font-size: 25px;
  }
  
  h2,
  h3,
  h5,
  h6 {
    font-family: Arial, Helvetica, sans-serif;
    color: #a17d7d;
    font-size: 40px;
  }
  
  .design {
    font-size: 25px;
    padding: 20px;
  }
  
  #designer {
    background-color: rgba(188, 187, 187, 0.718);
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
  }
  
  button {
    padding: 15px 30px;
    background-color: #268996;
    color: #fff;
    border: none;
    cursor: pointer;
    margin-top: 20px;
    font-size: 18px;
    display: inline-block;
  }
  
  button:hover {
    background-color: #1a1a5e;
  }
  
  .intro-section{
    font-size: 40px;
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
  }
  
  #location {
    font-size: 40px;
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
  }
  #owners {
    font-size: 40px;
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
  }
  
  button .toggle {
    font-size: 20px;
    padding: 10px;
    cursor: pointer;
    background-color: rgb(28, 28, 94);
  }
  
  .panel {
    display: none;
    font-size: 25px;
    background-color: rgba(169, 189, 182, 0.9);
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-top: 10px;
  }
  
  .hero {
    background: url("Mysite/img/backgroundImage.jpg") no-repeat center center fixed;
    background-size: cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    text-align: center;
  }
  
  .hero-content {
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    position: relative;
    padding-top: 250px;
  }
  
  .hero h2 {
    font-size: 34px;
    margin-top: 10px;
  }
  
  .hero button {
    padding: 15px 30px;
    background-color: #26899642;
    color: #fff;
    border: none;
    cursor: pointer;
    margin-top: 20px;
    font-size: 18px;
    display: inline-block;
  }
  
  button {
    padding: 12px 24px;
    background-color: #268996;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 18px;
    transition: background-color 0.3s ease;
  }
  
  button:hover {
    background-color: #1a1a5e;
  }
    
  .image-text-section {
    display: flex;
    justify-content: space-between;
    padding: 0px 0;
    background-color: #504b4b59;
    max-width: 1000px;
    margin: 0 auto;
  }
  
  .image-text-block {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    background-color: #504b4b59;
    text-align: center;
  }
  
  .image-text-block img {
    width: 350px;
    height: auto;
    max-height: 350px;
    padding: 30px;
  }
  
  .text-block {
    padding: 20px;
  }
  
  .text-block h3 {
    font-size: 40px;
  }
  
  .text-block p {
    font-size: 30px;
  }
  
  .choice {
    display: flex;
    flex-direction: column;
    align-items: stretch;
    gap: 20px;
    text-align: center;
    max-width: 1000px;
    margin: 0 auto;
  }
    
  .choice-item {
    display: flex;
    align-items: center;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    background-color: rgba(255, 255, 255, 0.9);
  }
  
  .choice-content {
    flex: 1;
    padding: 20px;
  }
  
  .choice h3 {
    font-size: 30px;
    margin-top: 20px;
    color: #333;
  }
  
  .choice-content p {
    font-size: 24px;
    color: #666;
  }
  
  .reverse {
    flex-direction: row-reverse;
    background-color: white;
  }
  
  .choice-item img {
    max-width: 40%;
    height: auto;
  }
  
  #reversed {
    background-color: rgba(158, 157, 157, 0.562);
  }
  
  .toggle {
    padding: 15px 30px;
    background-color: #26899642;
    color: #fff;
    border: none;
    cursor: pointer;
    margin-top: 20px;
    font-size: 18px;
    display: inline-block;
  }
  </style>