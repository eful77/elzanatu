# elzanatu
website
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Elzanatu — Selamat datang</title>
  <meta name="description" content="Elzanatu — layanan & produk terbaik. Hubungi kami untuk info lebih lanjut." />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='20' fill='%23007ACC'/%3E%3Ctext x='50' y='58' font-size='48' text-anchor='middle' fill='white' font-family='Arial'%3EE%3C/text%3E%3C/svg%3E">
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#007ACC;--muted:#9aa6b2;--glass: rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;background:linear-gradient(180deg,#071021 0%,#071626 60%);color:#e6eef6;line-height:1.45}
    .container{max-width:1100px;margin:0 auto;padding:28px}
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 0}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;background:var(--accent);display:grid;place-items:center;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.45)}
    .logo strong{font-size:22px}
    nav a{color:var(--muted);text-decoration:none;margin-left:18px}
    nav a:hover{color:var(--accent)}

    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;margin:36px 0}
    .hero h1{font-size:40px;margin:0 0 12px}
    .hero p{color:var(--muted);margin:0 0 20px}
    .cta{display:inline-block;padding:12px 18px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#00b3ff);color:white;text-decoration:none;font-weight:600}

    .card{background:var(--card);padding:18px;border-radius:14px;box-shadow:0 6px 24px rgba(2,6,23,0.6);}
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:18px}
    .feature{background:var(--glass);padding:14px;border-radius:10px;text-align:center}
    .feature h3{margin:8px 0 6px;font-size:16px}
    .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:14px}
    .thumb{height:120px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:600}

    .contact-section{display:grid;grid-template-columns:1fr 420px;gap:20px;margin:36px 0}
    form label{display:block;margin-bottom:6px;color:var(--muted)}
    input,textarea{width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit}
    button{padding:10px 14px;border-radius:10px;border:0;background:var(--accent);color:white;font-weight:600;cursor:pointer}
    footer{padding:22px 0;color:var(--muted);font-size:14px;border-top:1px solid rgba(255,255,255,0.03)}

    /* Responsive */
    @media (max-width:900px){.hero,.contact-section{grid-template-columns:1fr} .features{grid-template-columns:repeat(2,1fr)} .gallery{grid-template-columns:repeat(2,1fr)} }
    @media (max-width:520px){.features{grid-template-columns:1fr} .gallery{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true"><strong>E</strong></div>
        <div>
          <div style="font-weight:700">Elzanatu</div>
          <div style="font-size:13px;color:var(--muted)">elzanatu.com</div>
        </div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#about">Tentang</a>
        <a href="#services">Layanan</a>
        <a href="#contact">Kontak</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div>
          <h1>Selamat datang di Elzanatu</h1>
          <p>Website resmi Elzanatu. Kami menyediakan produk dan layanan berkualitas. Jelajahi, kontak, dan mulai proyek Anda bersama kami.</p>
          <a class="cta" href="#contact">Hubungi Sekarang</a>

          <div class="card" style="margin-top:18px">
            <h3 id="about">Tentang Kami</h3>
            <p style="color:var(--muted);margin-top:8px">Elzanatu berdedikasi untuk memberikan layanan terbaik dengan fokus pada kepuasan pelanggan. Sesuaikan isi ini sesuai kebutuhan brand Anda.</p>
            <div class="features">
              <div class="feature"><div style="font-size:20px">✔</div><h3>Profesional</h3><div style="color:var(--muted);font-size:13px">Tim ahli & berpengalaman</div></div>
              <div class="feature"><div style="font-size:20px">⚡</div><h3>Cepat</h3><div style="color:var(--muted);font-size:13px">Pelayanan responsif</div></div>
              <div class="feature"><div style="font-size:20px">🔒</div><h3>Aman</h3><div style="color:var(--muted);font-size:13px">Privasi & keamanan</div></div>
            </div>
          </div>
        </div>

        <aside>
          <div class="card">
            <h3>Layanan Unggulan</h3>
            <ul style="color:var(--muted);margin-top:8px;padding-left:18px">
              <li>Desain & Pengembangan Web</li>
              <li>Branding & Desain Grafis</li>
              <li>Support & Pemeliharaan</li>
            </ul>
            <div style="margin-top:12px">
              <strong>Mulai dari:</strong>
              <div style="font-size:20px;margin-top:6px">Rp — (sesuaikan)</div>
            </div>
          </div>

          <div class="card" style="margin-top:14px">
            <h4>Galeri</h4>
            <div class="gallery">
              <div class="thumb">Gambar 1</div>
              <div class="thumb">Gambar 2</div>
              <div class="thumb">Gambar 3</div>
            </div>
          </div>
        </aside>
      </section>

      <section id="services">
        <div class="card" style="margin-top:6px">
          <h3>Layanan Lengkap</h3>
          <p style="color:var(--muted);">Kami menawarkan paket-paket yang dapat disesuaikan. Hubungi kami untuk diskusi lebih lanjut.</p>
        </div>
      </section>

      <section class="contact-section" id="contact">
        <div class="card">
          <h3>Hubungi Kami</h3>
          <p style="color:var(--muted)">Isi formulir di samping atau kirim email ke <a href="mailto:hello@elzanatu.com" style="color:var(--accent)">hello@elzanatu.com</a></p>
          <div style="margin-top:12px">
            <strong>Alamat</strong>
            <div style="color:var(--muted);margin-top:6px">(Alamat Anda di sini)</div>
          </div>
        </div>

        <form class="card" onsubmit="handleSubmit(event)">
          <label for="name">Nama</label>
          <input id="name" name="name" required placeholder="Nama Anda" />

          <label for="email" style="margin-top:10px">Email</label>
          <input id="email" name="email" type="email" required placeholder="nama@contoh.com" />

          <label for="message" style="margin-top:10px">Pesan</label>
          <textarea id="message" name="message" rows="5" required placeholder="Tulis pesan Anda..."></textarea>

          <div style="display:flex;gap:10px;margin-top:12px;align-items:center">
            <button type="submit">Kirim Pesan</button>
            <div id="formStatus" style="color:var(--muted);font-size:13px"></div>
          </div>
        </form>
      </section>

    </main>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© <span id="year"></span> Elzanatu. Semua hak cipta dilindungi.</div>
        <div style="color:var(--muted)">Made with ♥ — sesuaikan konten ini</div>
      </div>
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    function handleSubmit(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const message = document.getElementById('message').value.trim();
      const status = document.getElementById('formStatus');
      if(!name||!email||!message){ status.textContent = 'Lengkapi semua kolom.'; return }

      // Simulasi pengiriman. Untuk produksi: gunakan Formspree, Netlify Forms, atau endpoint server Anda.
      status.textContent = 'Mengirim...';
      setTimeout(()=>{
        status.textContent = 'Pesan berhasil dikirim — terima kasih!';
        e.target.reset();
      },900);
    }
  </script>
</body>
</html>
S. Customize text, images, and colors as needed.
-->

