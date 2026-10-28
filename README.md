index.html
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Matchdayfits – Amateurfußball, Matchday-Outfits und unsere Player Community.">
  <title>Matchdayfits | Football meets Style</title>

  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; scroll-padding-top: 100px; }

    body {
      background: #f7f7f7;
      color: #111;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
    }

    a { color: inherit; text-decoration: none; }

    header {
      position: sticky;
      top: 0;
      z-index: 10;
      background: #fff;
      border-bottom: 1px solid #e5e5e5;
    }

    nav {
      max-width: 1100px;
      margin: auto;
      padding: 17px 22px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 18px;
      flex-wrap: wrap;
    }

    .logo { font-size: 21px; font-weight: 900; letter-spacing: -1px; }

    .nav-links {
      display: flex;
      flex-wrap: wrap;
      gap: 17px;
      font-size: 13px;
      font-weight: bold;
    }

    .hero {
      background: #111;
      color: white;
      text-align: center;
      padding: 100px 22px;
    }

    .eyebrow, .section-label {
      font-size: 11px;
      letter-spacing: 3px;
      text-transform: uppercase;
      font-weight: bold;
      color: #888;
      margin-bottom: 15px;
    }

    .hero .eyebrow { color: #aaa; }

    h1 {
      font-size: clamp(42px, 9vw, 86px);
      line-height: 1;
      letter-spacing: -3px;
      margin-bottom: 24px;
    }

    h1 span { color: #aaa; }

    .hero p {
      max-width: 540px;
      margin: 0 auto 30px;
      color: #ccc;
    }

    .button {
      display: inline-block;
      padding: 14px 22px;
      background: white;
      color: #111;
      font-size: 13px;
      font-weight: bold;
      border: 1px solid white;
      cursor: pointer;
    }

    .button:hover { opacity: .8; }

    .button-dark {
      background: #111;
      color: white;
      border-color: #111;
    }

    section {
      max-width: 1100px;
      margin: auto;
      padding: 75px 22px;
    }

    h2 {
      font-size: clamp(31px, 5vw, 47px);
      line-height: 1.1;
      letter-spacing: -1.5px;
      margin-bottom: 18px;
    }

    .intro {
      max-width: 620px;
      color: #666;
      margin-bottom: 32px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 16px;
    }

    .card {
      background: white;
      border: 1px solid #e6e6e6;
      padding: 26px;
    }

    .number {
      color: #888;
      font-size: 11px;
      letter-spacing: 2px;
      font-weight: bold;
    }

    h3 { font-size: 21px; margin: 17px 0 10px; }

    .card p { color: #666; font-size: 14px; }

    .dark-section {
      max-width: none;
      background: #111;
      color: white;
      padding: 75px 22px;
      scroll-margin-top: 90px;
    }

    .dark-inner { max-width: 1056px; margin: auto; }

    .dark-section .intro { color: #bbb; }

    .dark-section .card {
      background: #1b1b1b;
      border-color: #333;
    }

    .dark-section .card p { color: #bbb; }

    .dark-section .number { color: #aaa; }

    .join {
      max-width: none;
      text-align: center;
      background: #eee;
      padding: 65px 22px;
    }

    .join p {
      max-width: 550px;
      margin: 0 auto 24px;
      color: #666;
    }

    footer {
      background: #111;
      color: #aaa;
      text-align: center;
      padding: 28px 20px;
      font-size: 12px;
    }

    footer strong { color: white; }

    @media (max-width: 700px) {
      nav { align-items: flex-start; flex-direction: column; }
      .nav-links { gap: 12px; font-size: 12px; }
      .hero { padding: 75px 20px; }
      h1 { letter-spacing: -2px; }
      section { padding: 55px 20px; }
      .grid { grid-template-columns: 1fr; }
    }
  </style>
</head>

<body>
  <header>
    <nav>
      <a class="logo" href="#home">MATCHDAYFITS.</a>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#players">Player Team</a>
        <a href="#content">Content</a>
        <a href="#brands">Kooperationen</a>
      </div>
    </nav>
  </header>

  <main>
    <div class="hero" id="home">
      <div class="eyebrow">Football meets Style</div>
      <h1>MORE THAN<br><span>JUST FOOTBALL.</span></h1>
      <p>Wir verbinden Amateurfußball, persönliche Styles und eine Community, die gemeinsam wachsen möchte.</p>
      <a class="button" href="https://www.instagram.com/matchdayfits.123/" target="_blank" rel="noopener noreferrer">
        FOLLOW US ON INSTAGRAM ↗
      </a>
    </div>

    <section id="about">
      <div class="section-label">01 / About us</div>
      <h2>Mehr als 90 Minuten.</h2>
      <p class="intro">Fußball ist nicht nur das Spiel. Es sind die Menschen, der Style und die Community dahinter.</p>

      <div class="grid">
        <div class="card">
          <div class="number">01 / FOOTBALL</div>
          <h3>Amateurfußball</h3>
          <p>Wir möchten Spielerinnen und Spieler aus Amateurvereinen sichtbarer machen.</p>
        </div>
        <div class="card">
          <div class="number">02 / STYLE</div>
          <h3>Dein Look. Dein Ding.</h3>
          <p>Matchday-Outfits, Streetwear und persönliche Styles rund um den Fußball.</p>
        </div>
        <div class="card">
          <div class="number">03 / COMMUNITY</div>
          <h3>Gemeinsam wachsen</h3>
          <p>Neue Kontakte, kreative Ideen und gemeinsame Projekte.</p>
        </div>
      </div>
    </section>

    <div class="dark-section" id="players">
      <div class="dark-inner">
        <div class="section-label">02 / Player Team</div>
        <h2>Werde Teil unserer Community.</h2>
        <p class="intro">Du spielst in einem Amateurverein und hast Lust, deinen Style zu zeigen? Bewirb dich für das Matchdayfits Player Team.</p>
        <a class="button" href="https://forms.gle/7gnEuHuyi71yjKjbA" target="_blank" rel="noopener noreferrer">
          JETZT BEWERBEN ↗
        </a>
      </div>
    </div>

    <section id="content">
      <div class="section-label">03 / Our Content</div>
      <h2>Football. Fits. People.</h2>
      <p class="intro">Unsere Inhalte drehen sich um echte Menschen, ihren Fußballalltag und ihren persönlichen Style.</p>
      <div class="grid">
        <div class="card">
          <div class="number">01</div>
          <h3>Player Features</h3>
          <p>Spielerinnen und Spieler und ihre Geschichten.</p>
        </div>
        <div class="card">
          <div class="number">02</div>
          <h3>Matchday Fits</h3>
          <p>Outfits, Streetwear und Looks rund um den Spieltag.</p>
        </div>
        <div class="card">
          <div class="number">03</div>
          <h3>Reels & Stories</h3>
          <p>Kreative Inhalte aus dem Amateurfußball.</p>
        </div>
      </div>
    </section>

    <div class="dark-section" id="brands">
      <div class="dark-inner">
        <div class="section-label">04 / Collaborations</div>
        <h2>Let's work together.</h2>
        <p class="intro">Du hast eine Marke oder ein Projekt, das zu Fußball und Streetwear passt? Wir freuen uns über passende Kooperationsideen.</p>
        <a class="button" href="https://www.instagram.com/matchdayfits.123/" target="_blank" rel="noopener noreferrer">
          KOOPERATION ANFRAGEN ↗
        </a>
      </div>
    </div>

    <div class="join">
      <div class="section-label">MATCHDAYFITS COMMUNITY</div>
      <h2>Football is better together.</h2>
      <p>Folge uns auf Instagram und entdecke unsere nächsten Player Features, Outfits und Projekte.</p>
      <a class="button button-dark" href="https://www.instagram.com/matchdayfits.123/" target="_blank" rel="noopener noreferrer">
        ZU UNSEREM INSTAGRAM ↗
      </a>
    </div>
  </main>

  <footer>
    <strong>MATCHDAYFITS.</strong><br>
    Football meets Style.<br><br>
    <a href="https://www.instagram.com/matchdayfits.123/" target="_blank" rel="noopener noreferrer">Instagram ↗</a>
  </footer>
</body>
</html>