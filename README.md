# DharmaWanitaSby
High School
# DharmaWanitaSby
High School
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SMP DHARMA WANITA SURABAYA</title>
  <meta name="description" content="Profil resmi SMP Dharma Wanita Surabaya: deskripsi sekolah, fasilitas, dan kontak." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <!-- Navbar -->
  <header class="header">
    <div class="container nav">
      <a class="brand" href="#home">SMP DHARMA WANITA SURABAYA</a>
      <nav class="menu">
        <a href="#home">Beranda</a>
        <a href="#deskripsi">Deskripsi</a>
        <a href="#fasilitas">Fasilitas</a>
        <a href="#kontak">Contact Us</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="hero">
    <div class="container hero-inner">
      <h1>SMP DHARMA WANITA SURABAYA</h1>
      <p>Sekolah menengah pertama yang berkomitmen pada pendidikan berkarakter, prestasi akademik, dan kegiatan berkarya.</p>
      <a href="#kontak" class="btn primary">Hubungi Kami</a>
    </div>
  </section>

  <!-- Deskripsi Sekolah -->
  <section id="deskripsi" class="section">
    <div class="container grid-two">
      <div>
        <h2>Deskripsi sekolah</h2>
        <p>
          SMP Dharma Wanita Surabaya menyediakan lingkungan belajar yang aman, inklusif, dan mendukung
          pengembangan potensi peserta didik. Dengan tenaga pendidik profesional dan program ekstrakurikuler
          yang beragam, kami mendorong siswa untuk berprestasi di bidang akademik, seni, olahraga, dan karakter.
        </p>
        <p>
          Kurikulum dirancang seimbang antara teori dan praktik, dengan pemanfaatan teknologi pembelajaran
          untuk meningkatkan kreativitas, kolaborasi, dan kemampuan problem solving.
        </p>
      </div>
      <div class="card highlight">
        <h3>Visi & Misi</h3>
        <ul>
          <li>Menumbuhkan siswa berkarakter, berintegritas, dan berprestasi.</li>
          <li>Mengembangkan kompetensi literasi, numerasi, dan digital.</li>
          <li>Mendorong kolaborasi sekolah–orang tua–masyarakat.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Fasilitas -->
  <section id="fasilitas" class="section alt">
    <div class="container">
      <h2>Fasilitas</h2>
      <div class="cards">
        <article class="card">
          <h3>Ruang kelas nyaman</h3>
          <p>Pencahayaan baik, ventilasi memadai, dan sarana belajar lengkap.</p>
        </article>
        <article class="card">
          <h3>Laboratorium</h3>
          <p>Lab IPA dan Komputer untuk pembelajaran praktikum dan teknologi.</p>
        </article>
        <article class="card">
          <h3>Perpustakaan</h3>
          <p>Koleksi buku pelajaran, referensi, dan literatur pengembangan diri.</p>
        </article>
        <article class="card">
          <h3>Lapangan olahraga</h3>
          <p>Area untuk kegiatan fisik, ekstrakurikuler, dan lomba antar kelas.</p>
        </article>
        <article class="card">
          <h3>Ruang UKS</h3>
          <p>Penanganan pertama kesehatan siswa dengan fasilitas dasar.</p>
        </article>
        <article class="card">
          <h3>Mushola</h3>
          <p>Tempat ibadah yang bersih dan nyaman untuk warga sekolah.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- Contact Us -->
  <section id="kontak" class="section">
    <div class="container">
      <h2>Contact us</h2>

      <div class="grid-two">
        <form class="card form" id="contactForm" novalidate>
          <div class="form-group">
            <label for="nama">Nama</label>
            <input type="text" id="nama" name="nama" placeholder="Nama lengkap" required />
            <small class="error" data-error-for="nama"></small>
          </div>

          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="nama@contoh.com" required />
            <small class="error" data-error-for="email"></small>
          </div>

          <div class="form-group">
            <label for="pesan">Pesan</label>
            <textarea id="pesan" name="pesan" rows="5" placeholder="Tulis pesan kamu..." required></textarea>
            <small class="error" data-error-for="pesan"></small>
          </div>

          <button type="submit" class="btn primary">Kirim</button>
          <p class="note" id="formNote">Kami akan membalas melalui email yang kamu cantumkan.</p>
        </form>

        <div class="card">
          <h3>Info sekolah</h3>
          <ul class="list">
            <li><strong>Nama:</strong> SMP Dharma Wanita Surabaya</li>
            <li><strong>Alamat:</strong> Surabaya, Jawa Timur</li>
            <li><strong>Email:</strong> info@smpdharmawanita.sch.id</li>
            <li><strong>Telepon:</strong> (031) 000000</li>
            <li><strong>Jam operasional:</strong> Senin–Jumat, 07.00–15.00 WIB</li>
          </ul>
          <div class="map-embed">
            <!-- Ganti src Google Maps embed jika ada alamat lengkap -->
            <iframe title="Peta SMP Dharma Wanita Surabaya"
              src="https://maps.google.com/maps?q=Surabaya%20Jawa%20Timur&t=&z=13&ie=UTF8&iwloc=&output=embed"
              loading="lazy"></iframe>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container footer-inner">
      <p>© <span id="year"></span> SMP Dharma Wanita Surabaya. Semua hak cipta.</p>
      <div class="socials">
        <a href="#" aria-label="Facebook">Facebook</a>
        <a href="#" aria-label="Instagram">Instagram</a>
        <a href="#" aria-label="YouTube">YouTube</a>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
