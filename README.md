<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blog Basis Data - UBP Karawang</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #d7ccc8, #fbe9e7);
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #6d4c41, #f3e5ab);
      color: white;
      padding: 20px;
      text-align: center;
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    header h1 {
      font-size: 48px;
      color: #ffffff;
      text-align: center;
      text-shadow: 
        2px 2px 0 #6d4c41,
        -2px -2px 0 #ffccbc,
        2px -2px 0 #ffccbc,
        -2px  2px 0 #6d4c41;
    }

    header p {
      display: inline-block;
      background:#917e78;
      color: #fff;
      padding: 3px 10px;
      border-radius: 12px;
      font-size: 12px;
      text-decoration: none;
    }


    nav {
      background: #ffccbc;
      padding: 12px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    nav a {
      color: #6f42c1;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: all 0.3s ease;
    }

    nav a:hover {
      color: #d63384;
      text-shadow: 0px 0px 8px rgba(214, 51, 132, 0.6);
    }

    .hero {text-align: center;margin-top: 20px;}
    .hero iframe {width: 100%;
      max-width: 720px;
      height: 405px;
      border-radius: 12px;
      border: none;
      box-shadow: var(--card-shadow);
    }
    .container {
      max-width: 900px;
      margin: 25px auto;
      background: white;
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0px 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .container:hover {
      transform: translateY(-5px);
      box-shadow: 0px 8px 18px rgba(0,0,0,0.15);
    }

    h2 {
      color: #6d4c41;
      border-left: 5px solid #ffccbc;
      padding-left: 10px;
    }

    ul {
      margin: 10px 0;
      padding-left: 20px;
    }

    pre {
      background: #f3e5f5;
      padding: 10px;
      border-radius: 10px;
      overflow-x: auto;
      color: #6f42c1;
      font-weight: bold;
    }

    footer {
      background: linear-gradient(135deg, #f3e5ab, #6d4c41);
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
      border-top-left-radius: 30px;
      border-top-right-radius: 30px;
    }

    footer a {
      color: #ffe6f9;
      text-decoration: none;
      font-weight: bold;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Blog Basis Data</h1>
    <p>Nama : Nayssila Putri Pramudiani</p>
    <p>NIM : 24416255201128</p>
    <p>if24.nayssilapramudiana@mhs.ubpkarawang.ac.id</p>
  </header>

  <nav>
    <a href="#post1"></a>
    <a href="#post2"></a>
    <a href="#post3"></a>
    <a href="#post4"></a>
  </nav>

    <div class="hero">
        <iframe src="https://www.youtube.com/embed/-y6ugF8VtNA?si=WI_b9PyVkplMh9q3" 
      title="YouTube video" allowfullscreen></iframe>
    </div>

  <div class="container" id="post1">
    <h2>Post 2: Apa itu Attribute, Entitas, dan Relasi dalam ERD?</h2>
    <p>Dalam <em>Entity Relationship Diagram (ERD)</em>, ada tiga komponen utama yang digunakan untuk memodelkan data:</p>
      <ul>
        <li><strong>Atribut (Attribute)</strong> → Atribut adalah ciri atau informasi yang dimiliki entitas.  
          <br>Contoh:</li>
          <p>Produk → <strong>ID Produk, Nama Produk, Harga, Stok</strong></p> 
          <p>Pelanggan → <strong>Pelanggan, Nama, Email, Alamat</strong></p>
          <p>Pesanan → <strong>Pesanan, Tanggal Pesan, Total Harga</strong></p>
        <li><strong>Entitas (Entity)</strong> → Entitas adalah objek nyata atau konsep yang datanya ingin disimpan.  
          <br>Contoh di toko online : <em>Produk, Pelanggan, Pesanan.</em>.</li>
          <p>Produk = barang yang dijual.</p> 
          <p>Pelanggan = orang yang membeli.</p> 
          <p>Pesanan = transaksi pembelian.</p>
        <li><strong>Relasi (Relationship)</strong> → Relasi adalah hubungan antar entitas.  
          <br>Contoh:</li>
          <p>1. Pelanggan membuat Pesanan</p> 
          <p>2. Pesanan berisi Produk</p> 
      </ul>
  </div>

  <footer>
    <p>© 2025 Blog Basis Data | <a href="https://www.ubpkarawang.ac.id" target="_blank">UBP Karawang</a></p>
  </footer>

</body>
</html>
