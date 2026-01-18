<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <title>Bərbərxana</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #111;
      color: white;
      padding: 30px;
      text-align: center;
    }
    section {
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }
    .services, .contact {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
    }
    img {
      width: 100%;
      border-radius: 8px;
    }
    a.button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #111;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: white;
    }
  </style>
</head>
<body>

<header>
  <h1>Bərbərxana</h1>
  <p>Peşəkar Saç və Saqqal Qulluğu</p>
</header>

<section>
  <h2>Xidmətlərimiz</h2>
  <div class="services">
    <div class="card">
      <h3>Saç Kəsimi</h3>
      <p>Təmiz və müasir saç kəsimi</p>
      <strong>10 AZN</strong>
    </div>
    <div class="card">
      <h3>Saqqal Düzəlişi</h3>
      <p>Peşəkar saqqal düzəlişi</p>
      <strong>5 AZN</strong>
    </div>
    <div class="card">
      <h3>Saç + Saqqal</h3>
      <p>Tam qulluq xidməti</p>
      <strong>13 AZN</strong>
    </div>
  </div>
</section>

<section>
  <h2>Qalereya</h2>
  <img src="https://images.unsplash.com/photo-1517836357463-d25dfeac3438" alt="Bərbər şəkli">
</section>

<section>
  <h2>Əlaqə</h2>
  <div class="contact">
    <div class="card">
      <h3>WhatsApp</h3>
      <a class="button" href="https://wa.me/994XXXXXXXX">Mesaj göndər</a>
    </div>
    <div class="card">
      <h3>Instagram</h3>
      <a class="button" href="https://instagram.com/USERNAME">İnstagram profilinə bax</a>
    </div>
    <div class="card">
      <h3>Telefon</h3>
      <p>0XX XXX XX XX</p>
    </div>
  </div>
</section>

<footer>
  <p>📍 Bakı, Azərbaycan</p>
</footer>

</body>
</html>
