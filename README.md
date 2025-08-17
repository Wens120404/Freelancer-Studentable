# Freelancer-Studentable
A simple website for academic journal reviews, perfect for students, researchers, and reviewers.
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kang Wen Freelancer</title>
  <meta name="description" content="Portofolio Freelancer Ramah Mahasiswa oleh Kang Wen. Layanan: Editing, Copywriting, Data Entry, Dokumentasi.">
  <link rel="stylesheet" href="style.css">
  <!-- Ikon Lucide -->
  <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar">
    <div class="container">
      <h1 class="logo">Kang Wen</h1>
      <ul class="nav-links">
        <li><a href="#about">Tentang</a></li>
        <li><a href="#services">Layanan</a></li>
        <li><a href="#portfolio">Portofolio</a></li>
        <li><a href="#testi">Testimoni</a></li>
        <li><a href="#contact">Kontak</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero -->
  <header class="hero">
    <div class="container">
      <h2>Freelancer Ramah Mahasiswa & Profesional</h2>
      <p>Saya membantu membuat desain, copywriting, data entry, dan dokumentasi dengan cepat, rapi, dan sesuai kebutuhan Anda.</p>
      <a href="https://wa.me/6285183376862" class="btn primary">Hubungi Saya</a>
      <a href="https://forms.gle/xxx" class="btn">Form Project</a>
    </div>
  </header>

  <!-- About -->
  <section id="about" class="section">
    <div class="container grid grid-2">
      <div>
        <img src="images/kangwen.jpg" alt="Foto Kang Wen" class="foto">
      </div>
      <div>
        <h2>Tentang Saya</h2>
        <p>Saya Muhammad Wendy Pratama (Kang Wen), mahasiswa Sosiologi UB yang aktif di bidang kreatif dan sosial. Berpengalaman di editing, copywriting, data entry, dan dokumentasi.</p>
        <div class="stack">
          <span class="chip">Editing</span>
          <span class="chip">Copywriting</span>
          <span class="chip">Fotografi</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="section services">
    <div class="container">
      <h2>Layanan</h2>
      <p class="sub">Apa yang bisa saya bantu?</p>
      <div class="grid grid-3">
        <div class="card">
          <i data-lucide="pen-tool"></i>
          <h3>Editor Canva</h3>
          <p>Desain logo, poster, banner, CV, dan kebutuhan visual lainnya.</p>
        </div>
        <div class="card">
          <i data-lucide="type"></i>
          <h3>Copywriter</h3>
          <p>Copywriting untuk sosial media, caption IG, hingga artikel.</p>
        </div>
        <div class="card">
          <i data-lucide="database"></i>
          <h3>Data Entry</h3>
          <p>Input dan pengolahan data dengan rapi dan tepat waktu.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio" class="section portfolio">
    <div class="container">
      <h2>Portofolio</h2>
      <div class="grid grid-3">
        <img src="images/porto1.jpg" alt="Desain Poster oleh Kang Wen">
        <img src="images/porto2.jpg" alt="Copywriting Instagram">
        <img src="images/porto3.jpg" alt="Dokumentasi Event">
      </div>
    </div>
  </section>

  <!-- Testimoni -->
  <section id="testi" class="section testi">
    <div class="container">
      <h2>Testimoni</h2>
      <div class="grid grid-2">
        <div class="card quote">
          <p>“Desain posternya cepat, rapi, dan langsung bisa dipakai. Mantap!”</p>
          <strong>– Andi, Ketua Panitia Event</strong>
        </div>
        <div class="card quote">
          <p>“Tulisan copy IG bikin engagement naik, recommended banget!”</p>
          <strong>– Rina, Online Shop Owner</strong>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="section contact">
    <div class="container">
      <h2>Kontak</h2>
      <p class="sub">Hubungi saya untuk kolaborasi atau project baru.</p>
      <form action="mailto:muhammadwendypratama07@gmail.com" method="post" enctype="text/plain" class="card form">
        <input type="text" name="nama" placeholder="Nama" required>
        <input type="email" name="email" placeholder="Email" required>
        <textarea name="pesan" rows="4" placeholder="Pesan" required></textarea>
        <button class="btn primary" type="submit">Kirim Pesan</button>
      </form>
    </div>
  </section>

  <footer>
    <p>© 2025 Kang Wen Freelancer. Dibuat dengan ❤️</p>
  </footer>

  <script>
    lucide.createIcons();
  </script>
</body>
</html>
:root {
  --primary: #2563eb;
  --bg: #f9fafb;
  --text: #1f2937;
  --card: #fff;
  --ring: #d1d5db;
