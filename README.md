<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lilita+One&family=Poppins:wght@300;400;500;600;700&family=Teko:wght@400;500;600&display=swap" rel="stylesheet">
  <title>Portofolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav class="navbar">
      <div class="logo">Portofolio</div>
      <div class="menu-toggle" id="menu-toggle">&#9776;</div>
      <ul class="nav-links" id="nav-links">
        <li><a href="#beranda">Beranda</a></li>
        <li><a href="#tentang">Tentang Saya</a></li>
        <li><a href="#skill">Skill</a></li>
        <li><a href="#project">Project</a></li>
        <li><a href="#contact">Kontak</a></li>
      </ul>
    </nav>
  </header>  <section id="beranda" class="beranda">
    <div class="teks-content">
      <p class="sapa">Halo, saya</p>
      <h1 class="nama">Atsal Hafid</h1>
      <h4 class="bakat">Web Developer</h4>
      <p class="deskripsi-profil">Saya adalah seorang pengembang web yang berfokus pada desain antarmuka yang responsif dan pengalaman pengguna yang optimal.</p>
      <div class="btn-profil">
        <button type="button" class="utama">Tentang Saya</button>
      </div>
    </div>
  </section>  <section id="tentang" class="tentang">
    <div class="judul-halaman">
      <h1>Tentang Saya</h1>
    </div>
    <div class="container-tentang">
      <img src="info.jpg" alt="profilku">
      <div class="box-tentang">
        <p>Saya memiliki minat besar dalam dunia teknologi, terutama dalam pengembangan web, desain antarmuka pengguna, dan fotografi sebagai hobi visual saya.</p>
      </div>
      <div class="skill-tentang">
        <div class="skill-bar">
          <span>Photography</span>
          <div class="progress-bar">
            <div class="progress yellow" style="width: 85%;"></div>
          </div>
          <span class="percent">85%</span>
        </div>
        <div class="skill-bar">
          <span>Development</span>
          <div class="progress-bar">
            <div class="progress red" style="width: 95%;"></div>
          </div>
          <span class="percent">95%</span>
        </div>
        <div class="skill-bar">
          <span>UI/UX Design</span>
          <div class="progress-bar">
            <div class="progress blue" style="width: 70%;"></div>
          </div>
          <span class="percent">70%</span>
        </div>
      </div>
    </div><div class="group-riwayat">
  <div class="item-riwayat">
    <div class="atas">
      <i class="fa-solid fa-table-list"></i>
      <h1>29</h1>
    </div>
    <div class="bawah">
      <p>Jumlah proyek</p>
    </div>
  </div>
  <div class="item-riwayat">
    <div class="atas">
      <i class="fa-solid fa-thumbs-up"></i>
      <h1>20</h1>
    </div>
    <div class="bawah">
      <p>Proyek selesai</p>
    </div>
  </div>
  <div class="item-riwayat">
    <div class="atas">
      <i class="fa-solid fa-clock"></i>
      <h1>9</h1>
    </div>
    <div class="bawah">
      <p>Proyek tertunda</p>
    </div>
  </div>
  <div class="item-riwayat">
    <div class="atas">
      <i class="fa-solid fa-mug-saucer"></i>
      <h1>83</h1>
    </div>
    <div class="bawah">
      <p>Secangkir susu</p>
    </div>
  </div>
</div>

  </section>  <section id="skill" class="skill">
    <div class="judul-halaman">
      <h1>Skill</h1>
    </div>
    <div class="group-skill">
      <div class="item-skill" id="biru">
        <div class="ikon-skill">
          <i class="fa-solid fa-pen-nib"></i>
        </div>
        <div class="judul-skill">
          <h1>UI/UX Design</h1>
        </div>
        <div class="deskripsi-skill">
          <p>Saya merancang antarmuka yang menarik dan intuitif untuk memberikan pengalaman pengguna yang mudah dan menyenangkan.</p>
        </div>
      </div>
      <div class="item-skill" id="kuning">
        <div class="ikon-skill">
          <i class="fa-solid fa-code"></i>
        </div>
        <div class="judul-skill">
          <h1>Web Development</h1>
        </div>
        <div class="deskripsi-skill">
          <p>Saya membangun website modern dengan teknologi terkini dan memastikan performa yang optimal di berbagai perangkat.</p>
        </div>
      </div>
      <div class="item-skill" id="merah">
        <div class="ikon-skill">
          <i class="fa-solid fa-camera-retro"></i>
        </div>
        <div class="judul-skill">
          <h1>Photography</h1>
        </div>
        <div class="deskripsi-skill">
          <p>Fotografi adalah hobi yang saya tekuni untuk menangkap momen visual yang estetik dan penuh cerita.</p>
        </div>
      </div>
    </div>
  </section>  <section id="project" class="project">
    <div class="judul-halaman">
      <h1>Project</h1>
    </div>
    <div class="group-project">
      <div class="item-project">
        <div class="foto-project">
          <img src="proyek1.jpg" alt="Kelas Desain">
          <div class="judul-project">
            <h1>Kelas Desain</h1>
            <p>Platform interaktif untuk kursus desain UI/UX, lengkap dengan modul video dan studi kasus nyata.</p>
          </div>
        </div>
      </div>
      <div class="item-project">
        <div class="foto-project">
          <img src="proyek2.jpg" alt="Got Talent">
          <div class="judul-project">
            <h1>Got Talent</h1>
            <p>Aplikasi kompetisi bakat online yang memudahkan peserta mengunggah video dan mendapatkan voting juri.</p>
          </div>
        </div>
      </div>
      <div class="item-project">
        <div class="foto-project">
          <img src="proyek3.jpg" alt="Portfolio">
          <div class="judul-project">
            <h1>Portfolio</h1>
            <p>Website portofolio personal untuk menampilkan karya dan pengalaman dengan desain responsif.</p>
          </div>
        </div>
      </div>
      <div class="item-project">
        <div class="foto-project">
          <img src="proyek4.jpg" alt="Travel">
          <div class="judul-project">
            <h1>Travel</h1>
            <p>Situs travel dengan galeri destinasi wisata lengkap dan fitur booking online.</p>
          </div>
        </div>
      </div>
      <div class="item-project">
        <div class="foto-project">
          <img src="proyek5.jpg" alt="Toko Jam">
          <div class="judul-project">
            <h1>Toko Jam</h1>
            <p>Platform e-commerce penjualan jam tangan dengan tampilan produk interaktif dan keranjang belanja.</p>
          </div>
        </div>
      </div>
    </div>
  </section>  <section class="contact-section" id="contact">
    <div class="contact-container">
      <h2>Hubungi Kami</h2>
      <form id="contactForm">
        <input type="text" name="name" placeholder="Nama Anda" required />
        <input type="email" name="email" placeholder="Email Anda" required />
        <textarea name="message" placeholder="Tulis pesan Anda..." required></textarea>
        <button type="submit">Kirim Pesan</button>
      </form>
    </div><!-- Pop-up Ceklis -->
<div class="popup" id="popup">
  <div class="popup-content">
    <div class="checkmark">✓</div>
    <p>Pesan berhasil dikirim</p>
    <div class="admin-reply">
      Terima kasih telah menghubungi kami! Kami akan segera membalas pesan Anda.
    </div>
    <button id="okButton">Oke</button>
  </div>
</div>

  </section>  <script>
    const toggle = document.getElementById('menu-toggle');
    const navLinks = document.getElementById('nav-links');
    toggle.addEventListener('click', () => {
      navLinks.classList.toggle('active');
    });
  </script>  <script src="contact.js"></script></body>
</html>
