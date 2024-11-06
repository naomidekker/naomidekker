<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pac-man pagina </title>
  <head>
    <title>Pac-Man</title>
    <link rel="stylesheet" href="style.css">
  </head>
  
  <body>
    <header>
      <img src="./images/logo.png" alt="pacman logo" id="logo">
      <div id="navigatiegedeelte">
        <ul>
          <li>Home</li>
          <li>Het Spel</li>
          <li>Geschiedenis</li>
          <li>Muziek</li>
          <li>Contact</li>
        </ul>
      </div>
    </header>
    <main>
  
      <div id="pacman">
        <div class="uitleg">
          <h1>Pac-Man</h1>
          <p>
            Pac-Man is een klassiek computerspel, voor het eerst uitgebracht als arcadespel op 22 mei 1980. 
            Het spel is ontwikkeld door Namco. Binnen een jaar werden honderdduizend arcademachines verkocht. 
            Het is daarmee een van de succesvolste computerspellen aller tijden, 
            en overtreft spellen als Tetris en Street Fighter.
          </p>
        </div>
        <div class="werking">
          <img src="images/pacgame.gif" alt="Het Pacman basis spel in werking">
          <p>Het Pacman basis spel in werking</p>
        </div>
      </div>
  
      <div id="spel">
        <h2>Het spel</h2>
        <p>
          De speler bestuurt in het spel een geel "happertje" genaamd Pac-Man, 
          waarmee hij zich een weg moet banen door een speelveld gevuld met bolletjes 
          en andere voorwerpen zoals vruchtjes. Het doel is om alle bolletjes in het speelveld op te eten.
          De vruchtjes leveren extra punten op.
        </p>
        <div id="afbeeldinggroep">
          
            <img src="images/pacman-ghosts.jpg" alt="De spookjes">
            <p>
              De spookjes
            </p>
        </div>
        <p id="spookjes" class="spookjes">
          Het speelveld wordt echter onveilig gemaakt door vier spoken 
          in de kleuren rood, roze, lichtblauw en oranje. Als Pac-Man door een spook gepakt wordt, 
          is hij er geweest. De speler moet de spoken dan ook ontlopen.
          Als Pac-Man echter een witte pil pakt, waarvan er in het speelveld vier aanwezig zijn, 
          worden de rollen tijdelijk omgedraaid en kan hij de spoken uitschakelen. 
          De spoken worden dan allemaal donkerblauw en gaan langzamer lopen, 
          maar proberen nu op hun beurt de Pac-Man te ontlopen.
        </p>
        <p class="besturing">
          De besturing geschiedt veelal via een joystick, maar kan ook met het toetsenbord van de computer. 
          Hierbij worden de vier pijltjestoetsen gebruikt om de Pac-Man te besturen. 
          Op apparaten met een touchscreen verschijnen onder of
          naast het speelveld vier pijltjes waarmee de Pac-Man kan worden bestuurd.
        </p>
      </div>
  
      <div id="trivia">
        <h3>Trivia</h3>
        <p>
          De eerste opvolger van Pac-Man kwam een jaar later uit onder de naam Ms. Pac-Man.
        </p>
      </div>
  
      <div id="geschiedenis">
        <h2>Geschiedenis</h2>
        <p>
          Pac-Man is ontwikkeld door Toru Iwatani, game-ontwerper bij de 
          Japanse spellenfabrikant Namco.
          Jarenlang hebben er vele verschillende verhalen de ronde gedaan over hoe Pac-Man bedacht is. 
          Tijdens de NLGD in 2010, waar Toru Iwatani van het 
          World Guinness Book of Records
          een trofee in ontvangst mocht nemen voor het succes van Pac-Man, 
          vertelt hij het gehele verhaal achter Pac-Man.
        </p>
        <div id="toru">
          <img src="./images/toru-iwatani.jpg" alt="Toru Iwatani, creator of Pac-Man, at GDC 2011">
          <p>Toru Iwatani, creator of Pac-Man, at GDC 2011</p>
          <p>
            "Ik wilde een game maken die ook vrouwen aan zou spreken, want arcadehallen waren toen nog echte mannenplekken. 
            Ik wilde iets maken wat ze samen zouden willen spelen op een date, of gewoon alleen. 
            Daarom wilde ik een game maken die leuk (fun) en toegankelijk was, en karakters die schattig (cute/kawaii) waren.
            Voor de setting dacht ik aan verschillende dingen die dames aanspreken, zoals mode en winkelen. 
            Mijn vriendin van destijds hield heel erg van eten, dus dat werd mijn thema. 
            Toen ik bij Mickey's Pizza, - een Amerikaans pizzarestaurant in Japan, 
            want Japanse pizza's zijn niet echt lekker- een pizzapunt had gegeten en de rest van de pizza zo zag liggen, 
            was daar het character dat ik zocht: schattig en eetbaar. Pac-Man was geboren. 
            Hij is genoemd naar de Japanse term voor 'het geluid van de mondbeweging om te eten': paku-paku taberu.
            De ghosts zijn ook ontstaan uit het idee van kawaii-karakters. Iets als aliens zou de dames niet aanspreken, 
            maar de gekleurde spookjes waren de schattige tegenstrevers die ik voor Pac-Man wilde hebben. 
            Het maakte van de rivaliteit een beetje een Tom and Jerry-scenario: tegenstrevers, maar met een komische inslag."
          </p>
        </div>
        <p>
          De antagonisten in het spel stonden oorspronkelijk niet bekend als spoken maar gewoon als monsters. 
          De naam spoken danken ze aan de versie van Pac-Man die in 1981 werd uitgebracht voor de spelcomputer Atari 2600. 
          De Atari 2600-versie was van slechte kwaliteit; de monsters knipperden zo dat ze sindsdien voor spoken werden aangezien.
        </p>
      </div>
  
      <div id="muziek">
        <h2>Muziek</h2>
        <p>De herkenbare muziek van Pac-Man is gemaakt door Toshio Kai.
        </p>
        <audio src="audio/pacman.wav" controls>
          <p>Het ingesloten audio bestand kan helaas niet worden afgespeeld.</p>
        </audio>
      </div>
  
    </main>
  
    <div id="copyright">
      <div class="container">
        <small>Copyright &copy;2020 </small>
      </div>
    </div>
  
  </body>
  
</html>
