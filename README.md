<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wibsate – Viral Video & Game Keren 2026</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    :root {
      --bg: #0f0f0f;
      --text: #e1e1e1;
      --card: #1a1a1a;
      --accent: #ff3366;
      --accent-dark: #cc1a47;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: system-ui, -apple-system, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.5;
    }

    header {
      background: linear-gradient(to right, #111, #1a1a1a);
      padding: 1.2rem 5%;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 4px 15px rgba(0,0,0,0.7);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: 800;
      color: var(--accent);
      text-decoration: none;
    }

    nav a {
      color: var(--text);
      margin-left: 1.8rem;
      text-decoration: none;
      font-weight: 500;
      transition: 0.3s;
    }

    nav a:hover {
      color: var(--accent);
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1557683316-973673baf926?w=1600');
      background-size: cover;
      background-position: center;
      height: 60vh;
      min-height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 5%;
    }

    .hero-content h1 {
      font-size: clamp(2.5rem, 7vw, 5.5rem);
      margin-bottom: 1rem;
      text-shadow: 0 4px 20px rgba(0,0,0,0.9);
    }

    .hero-content p {
      font-size: 1.3rem;
      max-width: 700px;
      margin: 0 auto 2rem;
    }

    .btn {
      display: inline-block;
      background: var(--accent);
      color: white;
      padding: 0.9rem 2.2rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s;
    }

    .btn:hover {
      background: var(--accent-dark);
      transform: translateY(-3px);
      box-shadow: 0 10px 25px rgba(255,51,102,0.4);
    }

    .container {
      max-width: 1400px;
      margin: 0 auto;
      padding: 3rem 5%;
    }

    h2.section-title {
      font-size: 2.4rem;
      margin-bottom: 2rem;
      text-align: center;
      position: relative;
      display: inline-block;
    }

    h2.section-title::after {
      content: '';
      position: absolute;
      width: 80px;
      height: 4px;
      background: var(--accent);
      bottom: -12px;
      left: 50%;
      transform: translateX(-50%);
      border-radius: 2px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
      gap: 1.8rem;
    }

    .card {
      background: var(--card);
      border-radius: 14px;
      overflow: hidden;
      transition: all 0.35s;
      cursor: pointer;
      border: 1px solid #333;
    }

    .card:hover {
      transform: translateY(-12px);
      box-shadow: 0 20px 40px rgba(0,0,0,0.6);
      border-color: var(--accent);
    }

    .thumbnail {
      position: relative;
      height: 180px;
      overflow: hidden;
    }

    .thumbnail img, .thumbnail iframe {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.4s;
    }

    .card:hover .thumbnail img {
      transform: scale(1.08);
    }

    .info {
      padding: 1.3rem;
    }

    .info h3 {
      font-size: 1.15rem;
      margin-bottom: 0.6rem;
      line-height: 1.4;
    }

    .meta {
      color: #aaa;
      font-size: 0.9rem;
      display: flex;
      justify-content: space-between;
    }

    footer {
      background: #0a0a0a;
      text-align: center;
      padding: 3rem 1rem 2rem;
      margin-top: 4rem;
      border-top: 1px solid #222;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        gap: 1rem;
      }
      nav a {
        margin: 0 1rem;
      }
      .hero {
        height: 50vh;
      }
    }
  </style>
</head>
<body>

  <header>
    <a href="#" class="logo">WIBSATE 🔥</a>
    <nav>
      <a href="#video">Video Viral</a>
      <a href="#game">Game Viral</a>
      <a href="#">Trending</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>TEMUKAN KONTEN PALING VIRAL<br>HARI INI!</h1>
      <p>Kumpulan video & game paling heboh, lucu, absurd, dan bikin ketagihan se-Indonesia Raya 2026</p>
      <a href="#video" class="btn">Lihat Sekarang →</a>
    </div>
  </section>

  <div class="container">

    <h2 class="section-title" id="video">Video Viral Minggu Ini</h2>
    <div class="grid">

      <!-- Contoh video embed YouTube / TikTok -->
      <div class="card">
        <div class="thumbnail">
          <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ?mute=1&autoplay=0&controls=0" frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="info">
          <h3>Rick Astley vs Gen Z Dance Challenge 2026</h3>
          <div class="meta">
            <span>12 juta views</span>
            <span>3 hari lalu</span>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="thumbnail">
          <img src="https://i.ytimg.com/vi_webp/VIDEO_ID/maxresdefault.webp" alt="thumbnail">
        </div>
        <div class="info">
          <h3>Kamera Slow-mo Kucing Marah Dikasih Timun Lagi</h3>
          <div class="meta">
            <span>8.4 juta views</span>
            <span>1 minggu lalu</span>
          </div>
        </div>
      </div>

      <!-- Tambah card lain sesuai kebutuhan -->
      <div class="card">
        <div class="thumbnail">
          <img src="https://picsum.photos/seed/video3/500/300" alt="viral">
        </div>
        <div class="info">
          <h3>Cowok Bisa Nyanyi Sambil Jongkok 3 Jam Nonstop</h3>
          <div class="meta">
            <span>5.1 juta views</span>
          </div>
        </div>
      </div>

    </div>

    <h2 class="section-title" id="game" style="margin-top: 5rem;">Game Viral Sekarang</h2>
    <div class="grid">

      <div class="card">
        <div class="thumbnail">
          <img src="https://picsum.photos/seed/game1/500/300" alt="game viral">
        </div>
        <div class="info">
          <h3>Only Up! Indonesia Edition – Bikin Kesel Tapi Nagih</h3>
          <div class="meta">
            <span>Play di browser • 4.8★</span>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="thumbnail">
          <img src="https://picsum.photos/seed/game2/500/300" alt="game">
        </div>
        <div class="info">
          <h3>Wordle Bahasa Gaul 2026 – Susah Banget Bro</h3>
          <div class="meta">
            <span>Main sekarang • Gratis</span>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="thumbnail">
          <img src="https://picsum.photos/seed/game3/500/300" alt="game viral">
        </div>
        <div class="info">
          <h3>Geometry Dash Remake Versi Indonesia (Tahu Bulat Mode)</h3>
          <div class="meta">
            <span>1.2 juta player</span>
          </div>
        </div>
      </div>

    </div>

  </div>

  <footer>
    <p>© 2026 Wibsate • Kumpulan Konten Viral Indonesia • Made with ❤️ + Kopi</p>
    <p style="margin-top:1rem; font-size:0.9rem; color:#777;">
      Disclaimer: Semua konten berasal dari sumber publik. Kami tidak menyimpan/mengupload video.
    </p>
  </footer>

</body>
</html>
