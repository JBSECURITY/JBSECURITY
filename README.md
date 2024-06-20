<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Seguridad Total - Venta e Instalación de Equipos de Seguridad</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <img src="imagen/logo.png.jpg" alt="Logo Seguridad Total">
    </div>
    <nav>
      <ul>
        <li><a href="#inicio" class="menu-link" data-target="inicio">Inicio</a></li>
        <li><a href="#productos" class="menu-link" data-target="productos">Productos</a></li>
        <li><a href="#servicios" class="menu-link" data-target="servicios">Servicios</a></li>
        <li><a href="#acerca" class="menu-link" data-target="acerca">Acerca de</a></li>
        <li><a href="#contacto" class="menu-link" data-target="contacto">Contacto</a></li>
      </ul>
    </nav>
    <div class="contact-info">
      <span>Llámanos: 809-254-4899</span>
      <a href="https://wa.me/18092544899" target="_blank" class="whatsapp-link">
        <img src="imagen/what.png" alt="WhatsApp" class="whatsapp-icon" width="25" height="25">
      </a>
    </div>
  </header>

  <!-- Secciones -->
  <section class="hero section" id="inicio">
    <h1>Protegiendo tu Hogar y Negocio</h1>
    <p>Los mejores equipos de seguridad a tu alcance</p>
  </section>

  <section class="productos section" id="productos">
    <h2>Nuestros Productos</h2>
    <div class="producto">
      <h3>Cámara de Seguridad HD</h3>
      <img src="imagen/Camara 2.jpg" src="imagen/Camara 1.jpg"  alt="Cámara de Seguridad" width="100">
      <a href="#" class="btn">Ver más</a>
    </div>
    <div class="producto">
      <h3>Sistema de Alarma Inteligente</h3>
      <img src="imagen/Alrama.jpg" alt="Sistema de Alarma" width="100">
      <a href="#" class="btn">Ver más</a>
    </div>
    <div class="producto">
      <h3>Sistema de Acceso Biométrico</h3>
      <img src="imagen/Control de Acceso.jpg" alt="Sistema de Acceso" width="100">
      <a href="#" class="btn">Ver más</a>
      <div class="producto">
        <h3>kit de Motores Para portones</h3>
        <img src="imagen/Motores Electricos.png" alt="kit de Motores Para portones" width="100">
        <a href="#" class="btn">Ver más</a>
      </div>
    </div>
  </section>

  <section class="servicios section" id="servicios">
    <h2>Nuestros Servicios</h2>
    <p>Ofrecemos una amplia gama de servicios para garantizar tu seguridad.</p>
    <a href="#servicios" class="btn">Ver Servicios</a>
  </section>

  <section class="contacto section" id="contacto">
    <h2>Contacto</h2>
    <form id="contact-form">
      <label for="nombre">Nombre</label>
      <input type="text" id="nombre" name="nombre" required>
      <label for="telefono">Teléfono</label>
      <input type="tel" id="telefono" name="telefono" required>
      <label for="mensaje">Mensaje</label>
      <textarea id="mensaje" name="mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
    <div class="info-contacto">
      <p>Dirección: Santiago, República Dominicana</p>
      <p>Teléfono: 809-254-4899</p>
      <p>Email: cliente-jb@hotmail.com</p>
      <iframe src="https://maps.google.com/?q=Santiago,+República+Dominicana&z=15&output=embed" width="300" height="100" style="border:0;"></iframe>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="footer-content" target="_blank">
      <p>&copy; 2024 Seguridad Total. Todos los derechos reservados. Creado por : JOSE ABEL </p>
      <div class="social">
        <a href="https://wa.me/18092544899" target="_blank">
          <img src="imagen/what.png" alt="WhatsApp" width="35" height="35">
        </a>
        <a href="https://www.instagram.com/Abel.beato" target="_blank">
          <img src="imagen/download.jpg" alt="Instagram" width="35" height="35">
        </a>
        <a href="https://www.facebook.com/JB SEcurity" target="_blank">
          <img src="imagen/downloadF.png" alt="Facebook" width="35" height="35">
        </a>
      </div>
    </div>
  </footer>

  <script>
    // Manejar la visibilidad de las secciones
    document.addEventListener('DOMContentLoaded', function() {
      const sections = document.querySelectorAll('.section');
      const menuLinks = document.querySelectorAll('.menu-link');

      // Ocultar todas las secciones al cargar la página
      sections.forEach(section => section.style.display = 'none');
      
      // Mostrar solo la sección correspondiente al enlace del menú clicado
      menuLinks.forEach(link => {
        link.addEventListener('click', function(event) {
          event.preventDefault();
          const target = this.getAttribute('data-target');
          sections.forEach(section => {
            if (section.id === target) {
              section.style.display = 'block';
            } else {
              section.style.display = 'none';
            }
          });
        });
      });

      // Mostrar la primera sección (Inicio) al cargar la página
      document.getElementById('inicio').style.display = 'block';
    });

    // Enviar datos del formulario a WhatsApp
    document.getElementById('contact-form').addEventListener('submit', function(event) {
      event.preventDefault();
      
      const nombre = document.getElementById('nombre').value;
      const telefono = document.getElementById('telefono').value;
      const mensaje = document.getElementById('mensaje').value;

      const whatsappMessage = `https://wa.me/18092544899?text=${encodeURIComponent(
        `Nombre: ${nombre}\nTeléfono: ${telefono}\nMensaje: ${mensaje}`
      )}`;

      window.open(whatsappMessage, '_blank');
    });
  </script>
</body>
</html>
