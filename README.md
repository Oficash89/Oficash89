<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Oficash | Soluciones POS para tu negocio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      background-color: #f4f6f8;
      color: #333;
    }
    header {
      background-color: #002e5b;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      padding: 60px 20px;
      background: #ffffff;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5em;
      color: #002e5b;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .products, .about {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .card {
      background: white;
      flex: 1 1 300px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    footer {
      background: #002e5b;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    @media (max-width: 768px) {
      .products, .about {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Oficash</h1>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Productos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>
</header>

<section class="hero" id="inicio">
  <h1>Soluciones POS que impulsan tu negocio</h1>
  <p>Equipos, software y soporte especializado para tiendas, ferreterías y farmacias.</p>
</section>

<section class="section" id="servicios">
  <h2>Productos y Servicios</h2>
  <div class="products">
    <div class="card">
      <h3>Equipo POS Completo</h3>
      <p>Incluye computador, impresora térmica, lector, cajón monedero y software.</p>
    </div>
    <div class="card">
      <h3>Software de Punto de Venta</h3>
      <p>Fácil de usar, ideal para pequeños y grandes negocios. Incluye soporte.</p>
    </div>
    <div class="card">
      <h3>Instalación y Soporte</h3>
      <p>Asesoría técnica, configuración remota o presencial en Colombia.</p>
    </div>
  </div>
</section>

<section class="section" id="nosotros">
  <h2>¿Quiénes somos?</h2>
  <div class="about">
    <div class="card">
      <p>Oficash es una empresa dedicada a brindar soluciones tecnológicas de punto de venta. Nuestro compromiso es facilitar la gestión de negocios con herramientas confiables y accesibles.</p>
    </div>
  </div>
</section>

<section class="section" id="contacto">
  <h2>Contacto</h2>
  <p>Correo: contacto@oficash.com | WhatsApp: +57 300 123 4567</p>
  <p>Ubicación: Colombia</p>
</section>

<footer>
  <p>&copy; 2025 Oficash. Todos los derechos reservados.</p>
</footer>

</body>
</html>
