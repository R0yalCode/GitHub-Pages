<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Peluquería Estilo</title>
    <style>
      /* Reset de estilo */
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      /* Estilos generales */
      body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        background-image: url('https://imagenes.larazon.es/files/image_1900_1069/uploads/2022/12/15/6714520cb26ba.jpeg'); /* Agrega la URL de tu imagen aquí */
        background-size: cover; /* Hace que la imagen cubra toda la pantalla */
        background-position: center; /* Centra la imagen */
        background-attachment: fixed; /* Mantiene la imagen fija al hacer scroll */
        color: white; /* Color de texto blanco para que resalte sobre el fondo */
      }

      /* Cabecera */
      header {
        background-color: rgba(0, 0, 0, 0.5); /* Fondo negro semi-transparente */
        color: white;
        padding: 10px 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
      }

      header .logo h1 {
        font-size: 24px;
      }

      header nav ul {
        list-style: none;
        display: flex;
      }

      header nav ul li {
        margin: 0 15px;
      }

      header nav ul li a {
        color: white;
        text-decoration: none;
        font-size: 16px;
      }

      header nav ul li a:hover {
        text-decoration: underline;
      }

      /* Sección Hero */
      .hero {
        background-color: rgba(0, 0, 0, 0.5); /* Fondo negro semi-transparente */
        padding: 40px 20px;
        text-align: center;
      }

      .hero h2 {
        font-size: 36px;
        margin-bottom: 10px;
      }

      .hero p {
        font-size: 18px;
      }

      /* Sección Cortes de Pelo */
      .cortes {
        padding: 40px 20px;
        text-align: center;
        background-image: url("https://img.freepik.com/foto-gratis/papel-tapiz-peluquero-fondo-marmol-negro_53876-145654.jpg");
      }

      .cortes h2 {
        font-size: 30px;
        margin-bottom: 20px;
      }

      .corte {
        display: inline-block;
        width: 30%;
        margin: 0 15px;
        padding: 20px;
        background-color: white;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        text-align: center;
      }

      .corte h3 {
        font-size: 24px;
        margin-bottom: 10px;
      }

      .corte img {
        width: 100%;
        height: auto;
        border-radius: 8px;
        margin-bottom: 10px;
      }

      .corte p {
        font-size: 16px;
        color: #555;
      }

      /* Pie de página */
      footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px;
        position: fixed;
        width: 100%;
        bottom: 0;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">
        <h1>Peluquería Estilo</h1>
      </div>
      <nav>
        <ul>
          <li><a href="#">Inicio</a></li>
          <li><a href="#cortes">Tipos de Cortes</a></li>
          <li><a href="#">Servicios</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <section class="hero">
      <h2>Bienvenido a Peluquería Estilo</h2>
      <p>Transforma tu look con nuestros cortes de pelo exclusivos.</p>
    </section>

    <section id="cortes" class="cortes">
      <h2>Tipos de Cortes de Pelo</h2>
      <div class="corte">
        <h3>Corte Clásico</h3>
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRyEqHq0PrDWmg7Ieg1aGlZ_I4way-DpQtthw&s"
          alt="Corte Clásico"
        />
        <p>Un corte elegante y atemporal, perfecto para cualquier ocasión.</p>
      </div>
      <div class="corte">
        <h3>Corte Moderno</h3>
        <img
          src="https://www.directvsports.com/__export/1712495992114/sites/dsports/img/2024/04/07/portada_-_da.png_2059630743.png"
          alt="Corte Moderno"
        />
        <p>El estilo más actual, ideal para quienes siguen las tendencias.</p>
      </div>
      <div class="corte">
        <h3>Corte de diseño de autor</h3>
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-4wtqd3WtYnxd_RontTHBAQbqpgvg7KsZPA&s"
          alt="Corte Pixie"
        />
        <p>Un corte corto y atrevido para una transformación total.</p>
      </div>
    </section>

    <footer>
      <p>&copy; 2024 Peluquería Estilo | Todos los derechos reservados</p>
    </footer>
  </body>
</html>
