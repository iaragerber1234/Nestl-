<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nestlé Café</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      color: #333;
    }
    header {
      background: #f3f3f3;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #444;
      font-weight: bold;
    }
    .hero {
      background-image: url('https://images.unsplash.com/photo-1509042239860-f550ce710b93');
      background-size: cover;
      background-position: center;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
    }
    .hero-content {
      background: rgba(0, 0, 0, 0.6);
      padding: 40px;
      border-radius: 10px;
    }
    .hero-content h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    .hero-content button {
      padding: 10px 20px;
      font-size: 1em;
      background: #00704a;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .categories, .recommendations, .culture {
      padding: 60px 20px;
      text-align: center;
    }
    .categories h2, .recommendations h2, .culture h2 {
      margin-bottom: 20px;
    }
    .items {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }
    .card {
      background: #fff;
      border: 1px solid #ddd;
      padding: 20px;
      border-radius: 10px;
      width: 200px;
    }
    .card img {
      width: 100%;
      border-radius: 10px;
    }
    .card h3 {
      margin: 10px 0;
    }
    .footer {
      background: #222;
      color: #ccc;
      padding: 40px 20px;
      text-align: center;
    }
    .footer a {
      color: #ccc;
      margin: 0 10px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Nestlé Café</h1>
    <nav>
      <a href="#">Inicio</a>
      <a href="#">Regalos</a>
      <a href="#">Pedidos</a>
      <a href="#">Café</a>
      <a href="#">Tienda</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>ARTESANAL Y ÚNICO</h1>
      <p>Descubrí nuestra amplia variedad de cafés artesanales.</p>
      <button>Pedir Ahora</button>
    </div>
  </section>

  <section class="categories">
    <h2>Curaciones Nestlé Café</h2>
    <div class="items">
      <div class="card"><h3>Más Vendidos</h3></div>
      <div class="card"><h3>Bebidas</h3></div>
      <div class="card"><h3>Comidas</h3></div>
      <div class="card"><h3>Merchandising</h3></div>
      <div class="card"><h3>Café en Casa</h3></div>
    </div>
  </section>

  <section class="recommendations">
    <h2>Recomendaciones del Barista</h2>
    <div class="items">
      <div class="card">
        <img src="https://source.unsplash.com/200x150/?frappuccino" alt="Frappuccino">
        <h3>Café Frappé Nestlé</h3>
        <p>$15.20</p>
        <button>Agregar</button>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/200x150/?americano" alt="Americano">
        <h3>Americano Nestlé</h3>
        <p>$10.30</p>
        <button>Agregar</button>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/200x150/?iced-coffee" alt="Café Frío">
        <h3>Café Frío Nestlé</h3>
        <p>$11.00</p>
        <button>Agregar</button>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/200x150/?mocha" alt="Mocha">
        <h3>Mocha Chocolate</h3>
        <p>$11.20</p>
        <button>Agregar</button>
      </div>
    </div>
  </section>

  <section class="culture">
    <h2>Cómo el café Nestlé despierta los sentidos</h2>
    <p>Desde el grano hasta tu taza, descubrí la historia que hay en cada sorbo.</p>
    <button>Descubrí Más</button>
  </section>

  <footer class="footer">
    <p>&copy; 2025 Nestlé Café</p>
    <p>
      <a href="#">Accesibilidad</a> |
      <a href="#">Privacidad</a> |
      <a href="#">Términos</a> |
      <a href="#">Contacto</a>
    </p>
    <p>Síguenos: Facebook | Instagram | X</p>
  </footer>
</body>
</html>




