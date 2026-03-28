<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HUSSLE RECORDS 23</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Montserrat', sans-serif; }
    body { background-color:#0f0f0f; color:#f5f5f5; scroll-behavior:smooth; }
    a { color:#f5c518; text-decoration:none; transition:0.3s; }
    a:hover { color:#ff0000; }

    /* Navigation */
    nav { position:sticky; top:0; background:#111; display:flex; justify-content:center; gap:2rem; padding:1rem 0; z-index:100; }
    nav a { font-weight:bold; }

    /* Header/Hero */
    header { display:flex; flex-direction:column; justify-content:center; align-items:center; height:100vh; text-align:center; background:linear-gradient(180deg,#111 0%,#222 100%); }
    header h1 { font-size:3rem; margin-bottom:1rem; }
    header p { font-size:1.5rem; margin-bottom:2rem; }
    .cta-btn { padding:0.75rem 1.5rem; border:2px solid #f5c518; color:#f5c518; font-weight:bold; border-radius:5px; cursor:pointer; transition:0.3s; }
    .cta-btn:hover { background:#f5c518; color:#0f0f0f; }

    /* Sections */
    section { padding:5rem 2rem; max-width:1200px; margin:0 auto; }
    h2 { font-size:2.5rem; margin-bottom:2rem; text-align:center; }
    p { font-size:1.1rem; margin-bottom:1rem; }

    /* About Section */
    #about { background:#1a1a1a; border-radius:10px; padding:3rem; }

    /* Artist Section */
    #artist { display:flex; flex-direction:column; align-items:center; text-align:center; }
    #artist img { width:250px; height:250px; border-radius:50%; margin-bottom:1rem; object-fit:cover; border:3px solid #f5c518; }
    .artist-info { max-width:600px; }
    .artist-links { display:flex; gap:1.5rem; justify-content:center; margin:2rem 0; flex-wrap:wrap; }

    /* Releases Section */
    #releases { background:#1a1a1a; border-radius:10px; padding:3rem; display:flex; flex-direction:column; align-items:center; gap:2rem; }
    .release { text-align:center; max-width:600px; }

    iframe { border-radius:10px; max-width:100%; margin:1rem 0; }

    /* Join Label Section */
    #join { text-align:center; background:#1a1a1a; border-radius:10px; padding:3rem; }
    #join form { max-width:500px; margin:0 auto; display:flex; flex-direction:column; gap:1rem; }
    #join input, #join textarea { padding:0.75rem; border-radius:5px; border:none; }
    #join button { padding:0.75rem; border-radius:5px; border:none; background:#f5c518; color:#0f0f0f; font-weight:bold; cursor:pointer; transition:0.3s; }
    #join button:hover { background:#ff0000; color:#fff; }

    /* Contact Section */
    #contact { text-align:center; }

    /* Footer */
    footer { background:#111; text-align:center; padding:2rem; font-size:0.9rem; margin-top:2rem; }

    /* Responsive */
    @media(min-width:768px){
      #artist { flex-direction:row; text-align:left; }
      #artist img { margin-right:3rem; }
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#artist">Artist</a>
    <a href="#releases">Releases</a>
    <a href="#join">Join</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Hero Section -->
  <header id="home">
    <h1>HUSSLE RECORDS 23</h1>
    <p>Empowering the next generation of hip-hop artists</p>
    <a href="#artist" class="cta-btn">Meet Our Artist – YOUNG PENPA</a>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About HUSSLE RECORDS 23</h2>
    <p>Founded in 2023, HUSSLE RECORDS 23 was created to support aspiring artists who struggle to make music and dream of becoming professional musicians. We provide a platform for creative people to collaborate, learn, and release their music.</p>
    <p>Our label is all about growth, community, and giving artists the tools they need to succeed in the music industry.</p>
  </section>

  <!-- Artist Section -->
  <section id="artist">
    <img src="https://via.placeholder.com/250" alt="YOUNG PENPA">
    <div class="artist-info">
      <h2>YOUNG PENPA</h2>
      <p>Hip-hop / Rap artist under HUSSLE RECORDS 23, bringing energy, real stories, and a fresh voice to the scene.</p>
      <div class="artist-links">
        <a href="https://www.instagram.com/young_penpa?igsh=MXIzc2EwZ2J4YjA5Ng==" target="_blank">Instagram</a>
        <a href="https://youtube.com/@youngpenpa?si=_FClLAC2QSuR3ib6" target="_blank">YouTube</a>
        <a href="https://open.spotify.com/artist/7iZfNXWHFwb95WodnvaH41?si=h1SPyqBkQQqcTQAwle3tXw" target="_blank">Spotify</a>
        <a href="https://music.apple.com/fr/album/wrong-single/1774856935?l=en-GB" target="_blank">Apple Music</a>
      </div>
    </div>
  </section>

  <!-- Releases Section -->
  <section id="releases">
    <h2>Releases</h2>
    <div class="release">
      <h3>Latest Release: WRONG</h3>
      <iframe width="300" height="380" src="https://open.spotify.com/embed/track/7iZfNXWHFwb95WodnvaH41" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/ET4MDgmVFUs" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <!-- Join Label Section -->
  <section id="join">
    <h2>Join HUSSLE RECORDS 23</h2>
    <p>If you’re an aspiring artist and want to join our label, fill out the form below and we’ll get in touch!</p>
    <form action="https://formspree.io/f/xkopgezn" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <input type="text" name="instagram" placeholder="Instagram / Social Link">
      <input type="text" name="music" placeholder="Music Link (Spotify, YouTube, SoundCloud)">
      <textarea name="bio" placeholder="Short Bio / Artist Description" rows="4"></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>For collaborations or inquiries, reach us via Instagram:</p>
    <a href="https://www.instagram.com/husslerecords23?igsh=MTFhdDl4N3A3cmlhcA%3D%3D&utm_source=qr" target="_blank">@husslerecords23</a>
  </section>

  <!-- Footer -->
  <footer>
    ©️ All reserved under HUSSLE RECORDS 23
  </footer>

</body>
</html>