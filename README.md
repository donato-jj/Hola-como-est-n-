<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Hotel Etoile | Mar del Plata</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0B1C2D;
      color: #FFFFFF;
    }
    header {
      height: 100vh;
      background: linear-gradient(rgba(11,28,45,0.7), rgba(11,28,45,0.9)),
                  url('hero-hotel.jpg') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.2rem;
      margin: 20px 0;
    }
    .btn {
      padding: 12px 30px;
      background: #4FC3F7;
      color: #0B1C2D;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 600;
      transition: 0.3s;
    }
    .btn:hover {
      box-shadow: 0 0 15px #4FC3F7;
    }
    section {
      padding: 80px 10%;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 30px;
    }
    .card {
      background: rgba(255,255,255,0.05);
      padding: 30px;
      border-radius: 15px;
      text-align: center;
      transition: 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 20px rgba(79,195,247,0.3);
    }
    footer {
      background: #081421;
      text-align: center;
      padding: 40px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <div>
    <h1>Hotel Etoile ⭐⭐⭐</h1>
    <p>Confort moderno en el corazón de Mar del Plata</p>
    <a href="#" class="btn">Reservar ahora</a>
  </div>
</header>

<section>
  <h2>Servicios</h2>
  <div class="services">
    <div class="card">🛏️ Habitaciones confortables</div>
    <div class="card">📶 Wi-Fi alta velocidad</div>
    <div class="card">🕒 Recepción 24 hs</div>
    <div class="card">☕ Desayuno incluido</div>
  </div>
</section>

<footer>
  <p>📍 Santiago del Estero 1869, Mar del Plata</p>
  <p>📞 0223 493-4968</p>
  <p>Hotel Etoile © 2025</p>
</footer>

</body>
</html>

