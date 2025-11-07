<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Himeku Jilbab — Koleksi Modern & Elegan</title>
  <meta name="description" content="Koleksi jilbab modern, nyaman, dan elegan. Temukan warna & bahan yang cocok untuk aktivitas sehari-hari atau acara spesial." />
  <style>
    :root{
      --bg:#fff9f7;
      --accent:#b56576;
      --muted:#6b6b6b;
      --card:#ffffff;
      --glass: rgba(255,255,255,0.7);
      --maxw:1100px;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#fff);color:#222}
    .container{max-width:var(--maxw);margin:0 auto;padding:36px 20px}
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#f7b7c1);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:18px}
    nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 480px;gap:32px;align-items:center;padding:28px 0}
    .badge{display:inline-block;background:var(--accent);color:white;padding:6px 12px;border-radius:999px;font-weight:600}
    h1{font-size:36px;margin:12px 0 8px;line-height:1.05}
    p.lead{color:var(--muted);margin:0 0 18px}
    .cta{display:flex;gap:12px}
    .btn{padding:12px 18px;border-radius:12px;border:0;font-weight:700;cursor:pointer}
    .btn-primary{background:var(--accent);color:white}
    .btn-ghost{background:transparent;border:2px solid rgba(0,0,0,0.06)}
    /* card image */
    .hero-card{background:var(--card);border-radius:18px;padding:10px;box-shadow:0 8px 30px rgba(20,20,20,0.06)}
    .hero-card img{width:100%;height:420px;object-fit:cover;border-radius:12px}
    /* products */
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:28px}
    @media (max-width:980px){.hero{grid-template-columns:1fr;}.grid{grid-template-columns:repeat(2,1fr)}.hero-card img{height:300px}}
    @media (max-width:600px){.grid{grid-template-columns:1fr}header{flex-direction:column;align-items:flex-start}nav{margin-top:10px}}
    .product{background:var(--card);padding:12px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04);}
    .product img{width:100%;height:220px;object-fit:cover;border-radius:10px}
    .product .meta{display:flex;justify-content:space-between;align-items:center;margin-top:10px}
    .pill{background:var(--glass);padding:6px 8px;border-radius:8px;font-weight:600}
    .about{display:flex;gap:18px;margin-top:40px;align-items:center}
    .about img{width:320px;height:220px;object-fit:cover;border-radius:12px}
    .testi{margin-top:32px;display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
    .testi .card{background:linear-gradient(180deg,#fff,#fff);padding:14px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.04)}
    footer{margin-top:40px;padding:28px 0;color:var(--muted);text-align:center}
    /* small helpers */
    .price{font-weight:800}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">HJ</div>
        <div>
          <div style="font-weight:800">Aisya Jilbab</div>
          <div style="font-size:12px;color:var(--muted)">Elegan • Nyaman • Modern</div>
        </div>
      </div>
      <nav>
        <a href="#products">Produk</a>
        <a href="#about">Tentang</a>
        <a href="#contact">Kontak</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <span class="badge">New Arrival</span>
        <h1>Koleksi Jilbab Modern — Ringan & Bahannya Nyaman</h1>
        <p class="lead">Temukan jilbab dengan potongan yang rapi, bahan adem, dan warna-warna yang mudah dipadupadankan. Cocok untuk keseharian dan acara formal.</p>
        <div class="cta">
          <button class="btn btn-primary">Belanja Sekarang</button>
          <button class="btn btn-ghost">Lihat Katalog</button>
        </div>

        <div class="grid" style="margin-top:22px">
          <div class="product">
            <img src="https://i.pinimg.com/736x/45/e2/91/45e291b2a9ded0a12da23b98745dbc11.jpg" alt="Jilbab - soft pink">
            <div class="meta">
              <div>
                <div style="font-weight:700">Jilbab Soft Pink</div>
                <div style="font-size:13px;color:var(--muted)">Voal Premium — 110x110 cm</div>
              </div>
              <div style="text-align:right">
                <div class="price">Rp120.000</div>
                <div class="pill">Stok: 12</div>
              </div>
            </div>
          </div>

          <div class="product">
            <img src="http://i.pinimg.com/736x/8b/20/d8/8b20d8a7c0327e15b52b02167737de89.jpg" alt="Jilbab - cream">
            <div class="meta">
              <div>
                <div style="font-weight:700">Jilbab Classic Cream</div>
                <div style="font-size:13px;color:var(--muted)">Diamond Cotton — 115x115 cm</div>
              </div>
              <div style="text-align:right">
                <div class="price">Rp145.000</div>
                <div class="pill">Stok: 6</div>
              </div>
            </div>
          </div>

          <div class="product">
            <img src="https://i.pinimg.com/736x/17/5f/8b/175f8b5ba5d6cc0aa8659145ae67f8de.jpg" alt="Jilbab - navy">
            <div class="meta">
              <div>
                <div style="font-weight:700">Jilbab Navy Elegan</div>
                <div style="font-size:13px;color:var(--muted)">Silky Chiffon — 110x110 cm</div>
              </div>
              <div style="text-align:right">
                <div class="price">Rp160.000</div>
                <div class="pill">Stok: 4</div>
              </div>
            </div>
          </div>
        </div>

      </div>

      <div class="hero-card">
        <!-- Ganti URL gambar dengan foto produk Anda. Jika ingin menggunakan file lokal: src="images/jilbab-hero.jpg" -->
        <img src="https://i.pinimg.com/1200x/8e/10/05/8e10051605589898981c36bc61805fed.jpg" alt="Model jilbab">
      </div>
    </section>

    <section id="about" class="about">
      <div>
        <h2 style="margin:0 0 10px">Tentang Aisya Jilbab</h2>
        <p style="color:var(--muted);margin-top:0">Himeku Jilbab berdiri dengan misi menghadirkan jilbab berkualitas yang nyaman dipakai seharian. Kami memilih bahan yang adem, potongan yang rapi, dan warna yang timeless sehingga mudah dipadankan untuk berbagai gaya.</p>
        <ul style="color:var(--muted);margin-top:12px">
          <li>Bahan ramah kulit dan tidak mudah kusut</li>
          <li>Garansi 7 hari untuk kerusakan produksi</li>
          <li>Kirim cepat seluruh Indonesia</li>
        </ul>
      </div>
      <img src="https://i.pinimg.com/736x/8d/2e/24/8d2e24a6014ba592a795b7ea26935229.jpg" alt="ilustrasi toko jilbab">
    </section>

    <section class="testi">
      <div class="card">
        <div style="font-weight:800">"Lembut dan tidak membuat gerah"</div>
        <div style="color:var(--muted);margin-top:8px">— Avicenna, Jakarta</div>
      </div>
      <div class="card">
        <div style="font-weight:800">"Warna aslinya sama seperti di foto. Pelayanan cepat"</div>
        <div style="color:var(--muted);margin-top:8px">— Nafesa, Tangerang</div>
      </div>
    </section>

    <section id="contact" style="margin-top:36px">
      <h3>Hubungi Kami</h3>
      <p style="color:var(--muted)">Untuk pemesanan cepat, hubungi via WhatsApp atau isi form berikut.</p>
      <form style="display:flex;gap:10px;flex-wrap:wrap;max-width:760px">
        <input type="text" placeholder="Nama" style="flex:1;padding:12px;border-radius:8px;border:1px solid #eee">
        <input type="email" placeholder="Email" style="flex:1;padding:12px;border-radius:8px;border:1px solid #eee">
        <input type="text" placeholder="Pesan / Alamat" style="flex-basis:100%;padding:12px;border-radius:8px;border:1px solid #eee">
        <button class="btn btn-primary" type="submit">Kirim Pesan</button>
      </form>
    </section>

    <footer>
      © 2025 Aisya Jilbab • Dibuat dengan cinta
    </footer>
  </div>
</body>
</html>
