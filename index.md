<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wahyu Barokah</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      line-height: 1.6;
      color: #1a1a1a;
      background-color: #ffffff;
    }

    header {
      background-color: transparent;
      color: white;
      padding: 16px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 999;
      transition: background-color 0.3s ease, box-shadow 0.3s ease;
    }

    header.scrolled {
      background-color: #00002b;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
    }

    .logo {
      font-weight: 700;
      font-size: 20px;
    }

    nav ul {
      display: flex;
      gap: 24px;
      list-style: none;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #FFD700;
    }

    .hero {
      background-color: #00002b;
      color: white;
      padding: 160px 20px 60px;
      text-align: center;
      border-bottom-left-radius: 2rem;
      border-bottom-right-radius: 2rem;
      position: relative;
      z-index: 1;
      margin-top: -80px;
    }

    .hero img.hero-image {
      width: 160px;
      margin-bottom: 1.5rem;
    }

    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      color: rgba(255, 255, 255, 0.65);
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
      font-weight: 600;
    }

    .hero h1 .highlight {
      background: yellow;
      color: black;
      padding: 0.2rem 0.6rem;
      border-radius: 6px;
    }

    .hero p {
      font-size: 1.1rem;
      color: #e0e0e0;
      margin-top: 0.5rem;
    }

    .highlight {
      background-color: #FFD700;
      color: #000;
      padding: 4px 8px;
      border-radius: 4px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    .h2 {
      color: #00002b;
      margin-bottom: 16px;
      font-size: 1.5em;
    }

    .section p1:hover {
      margin-bottom: 50px;
      background-color: #00002b;
      color: white;
      transition: background-color 0.3s ease;
      padding:0px;
      border-radius: 0px;
    }

    .section.contactaa p:hover {
      transition: background-color 0.3s ease;
      padding: 1rem;
      border-radius: 10px;
    }

    .section.contacta {
      background-color: #00002b;
      color: #ffffff;
      padding: 30px 20px;
      font-size: 18px;
      text-align: center;
      border-radius: 6px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    .section.contacta:hover {
      background-color: #000040;
      color: #ffffff;
    }

    .ul {
      padding-left: 20px;
    }

    .img-section {
      text-align: center;
      margin: 30px 0;
    }

    .img-section img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .contact {
      background-color: #f0f0f0;
      padding: 30px 20px;
      border-left: 5px solid #00002b;
    }

    .site-footer {
      background-color: #00002b;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 15px;
      font-weight: 500;
    }

    .site-footer img {
      height: 24px;
      margin: 0 6px;
      vertical-align: middle;
    }

    .custom-header .container {
      max-width: 1140px;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 1.5rem;
    }

    .custom-header {
      background-color: #030233;
      color: white;
      position: sticky;
      top: 0;
      z-index: 9999;
      margin-left: 1px; /* atau padding-left: 1px; */
      border-bottom-left-radius: 2rem;
      border-bottom-right-radius: 2rem;
    }

    .custom-header .logo {
      font-weight: bold;
      font-size: 1.2rem;
      color: white;
    }

    .custom-header .main-nav a {
      color: white;
      text-decoration: none;
      margin-left: 2rem;
      transition: 0.3s;
    }

    .custom-header .main-nav a:hover {
      background-color: #ffdd00;
      color: black;
      padding: 0.3rem 0.6rem;
      border-radius: 5px;
    }

    iframe {
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      nav ul {
        flex-direction: column;
        gap: 12px;
        align-items: flex-start;
      }

      .hero h1 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>

<header id="navbar" class="custom-header">
  <div class="container">
    <div class="logo">Wahyu Barokah</div>
    <nav class="main-nav">
      <a href="">Beranda</a>
      <a href="">Artikel</a>
      <a href="">Produk & Layanan</a>
    </nav>
  </div>
</header>

<div class="hero">
  <img src="" alt="Ilustrasi Hero" class="hero-image">
  <h1><span class="soft-text">Selamat Datang di</span> <span class="highlight">Wahyu Barokah</span></h1>
  <p>UMKM makanan dan minuman sehat, siap menerima pesanan anda</p>
</div>

<div class="container">
  <div class="section">
    <h2>Tentang Kami</h2>
    <p1>Kami adalah UMKM yang menyediakan aneka jajanan ringan dan minuman buatan sendiri. kami juga siap melayani pemesanan aneka masakan sesuai kebutuhan anda</p1>
  </div>

  <div class="container">
   <div class="section">
        <h2>Visi & Misi</h2>
        <p><strong>Visi:</strong> Penyedia Jajanan dan minuman rumahan yang lezat di konsumsi ketika lapar</p>
        <p><strong>Misi:</strong> Memberikan rasa terbaik di setiap olahan kami</p>
  </div>

  <div class="section">
    <h2>Produk Unggulan</h2>
    <ul>
      <li><strong>Es Timun Serut</strong>:<p>.</p></li>
    </ul>
  </div>

<div class="section contact">
    <h2>Informasi Kontak</h2>
    <p><strong>Alamat:</strong><br>
     Panjang Jiwo SDI gang Tembusan No. 5 RT 004 RW 002 Surabaya.</p>
    <p><strong>WhatsApp:08128793585</strong></p>
  </div>

</div>

    <footer class="site-footer">
      <p>
        &copy;
        <img src="" alt="Logo MarkasBot">
        abhia 2025
      </p>
    </footer>

</body>
</html>


