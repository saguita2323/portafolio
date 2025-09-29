<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portafolio UX/UI</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Fondo futurista -->
  <div class="background"></div>

  <!-- Landing -->
  <header class="landing">
    <h1>Hola, soy Sharon</h1>
    <p>Diseñadora UX/UI enfocada en experiencias digitales minimalistas y efectivas.</p>
  </header>

  <!-- Servicios -->
  <section id="servicios" class="section">
    <h2>Servicios</h2>
    <div class="services-grid">
      <div class="card">Diseño UX</div>
      <div class="card">Diseño UI</div>
      <div class="card">Prototipado</div>
    </div>
  </section>

  <!-- Proyectos -->
  <section id="proyectos" class="section">
    <h2>Proyectos</h2>
    <div class="grid">
      <div class="card"><a href="proyecto1.html" class="btn-proyecto">Proyecto 1</a></div>
      <div class="card"><a href="proyecto2.html" class="btn-proyecto">Proyecto 2</a></div>
      <div class="card"><a href="proyecto3.html" class="btn-proyecto">Proyecto 3</a></div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="section">
    <h2>Contacto</h2>
    <form id="contactForm">
      <input type="text" id="nombre" placeholder="Tu nombre" required />
      <input type="email" id="email" placeholder="Tu email" required />
      <textarea id="mensaje" placeholder="Tu mensaje" required></textarea>
      <button type="submit" class="btn-proyecto">Enviar</button>
    </form>
  </section>

  <script src="script.js"></script>
</body>
</html>


