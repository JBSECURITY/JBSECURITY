<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JB-Security - Venta e Instalación de Equipos de Seguridad</title>
  <meta name="description" content="JB-Security ofrece la mejor venta e instalación de equipos de seguridad para hogar y negocio.">
  <meta name="keywords" content="seguridad, cámaras de seguridad, alarmas, acceso biométrico, motores para portones">
  <meta name="author" content="JOSE ABEL">
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      color: #333;
      background-image: url('imagenes nueva.jpeg'); /* Reemplaza esta ruta con la ruta de tu imagen */
      background-size: cover;
      background-attachment: fixed;
      background-position: center;
      background-repeat: no-repeat;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: rgba(0, 0, 0, 0.7); /* Usamos rgba para agregar transparencia */
      padding: 20px 40px;
    }
    .logo img {
      width: 150px;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }
    nav ul li a {
      color: #ece9e9;
      text-decoration: none;
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    nav ul li a:hover {
      background-color: #f53030;
    }
    .contact-info {
      display: flex;
      align-items: center;
      gap: 10px;
      color: white;
    }
    .whatsapp-icon {
      width: 25px;
      height: 25px;
    }
    .section {
      display: none;
      padding: 60px 20px;
      text-align: center;
      background-color: rgba(255, 255, 255, 0.8); /* Fondo blanco semi-transparente para mejor legibilidad */
      border-radius: 10px;
      margin: 20px;
    }
    .hero {
      display: block;
      padding: 60px 20px;
      background-color: rgba(0, 0, 0, 0.7); /* Fondo oscuro semi-transparente */
      color: white;
      border-radius: 10px;
      margin: 20px;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2em;
    }
    .hero .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #6c7574;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    .hero .btn:hover {
      background-color: #004d40;
    }
    footer {
      background-color: rgba(0, 0, 0, 0.7); /* Fondo oscuro semi-transparente */
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    .footer-content .social a {
      margin: 0 10px;
    }
    .footer-content .social img {
      width: 35px;
      height: 35px;
    }
    .productos-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .producto {
      width: 220px;
      padding: 20px;
      border: 1px solid #ccc;
      background-color: white;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .producto img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }
    .producto:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    }
    .producto h3 {
      margin-top: 10px;
      font-size: 1.2em;
    }
    .producto .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #00796b;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    .producto .btn:hover {
      background-color: #004d40;
    }
    .form-container {
      max-width: 600px;
      margin: auto;
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }
    .form-container input, .form-container textarea, .form-container select, .form-container button {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .form-container button {
      background-color: #00796b;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .form-container button:hover {
      background-color: #004d40;
    }
    
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <img src="imagen/gif.gif" alt="Logo JB-Security">
    </div>
    <nav>
      <ul>
        <li><a href="#inicio" class="menu-link" data-target="inicio">Inicio</a></li>
        <li><a href="#servicios" class="menu-link" data-target="servicios">Servicios</a></li>
        <li><a href="#acerca" class="menu-link" data-target="acerca">Acerca de</a></li>
        <li><a href="#productos" class="menu-link" data-target="productos">Productos</a></li>
        <li><a href="#cotizacion" class="menu-link" data-target="cotizacion">Cotización</a></li>
        <li><a href="#contacto" class="menu-link" data-target="contacto">Contacto</a></li>
      </ul>
    </nav>
    <div class="contact-info">
      <span>Llámanos: 809-254-4899</span>
      <a href="https://wa.me/18092544899" target="_blank">
        <img src="imagen/what.png" alt="WhatsApp" class="whatsapp-icon">
      </a>
    </div>
  </header>

  <!-- Secciones -->
  <section class="hero section" id="inicio">
    <h1>Protegiendo lo que más te importa</h1>
    <div class="mission-vision">
      <h2>Nuestra Misión</h2>
      <p>En JB-Security nos comprometemos a proporcionar soluciones de seguridad integrales, innovadoras y confiables para proteger hogares y negocios, garantizando la tranquilidad y seguridad de nuestros clientes.</p>
      <h2>Nuestra Visión</h2>
      <p>Convertirnos en líderes reconocidos en el sector de seguridad, ofreciendo tecnología de vanguardia y servicios excepcionales que superen las expectativas de nuestros clientes.</p>
    </div>
    <a href="#productos" class="btn">Ver Productos</a>
  </section>

  <section class="productos section" id="productos">
    <h2>Nuestros Productos</h2>
    <div class="productos-container">
      <div class="producto">
        <h3>Cámara de Seguridad HD</h3>
        <img src="imagen/images.jpeg" alt="Cámara de Seguridad" onclick="openModal(this)">
        <a class="btn" onclick="toggleDescription(this)">Ver más</a>
        <p class="descripcion-producto"style="display: none;">Cámara de seguridad HD con visión nocturna avanzada para una vigilancia óptima en todo momento.</p>
      </div>
      <div class="producto">
        <h3>Sistema de Alarma Inteligente</h3>
        <img src="imagen/Alrama nuevo.jpeg" alt="Sistema de Alarma" onclick="openModal(this)">
        <a class="btn" onclick="toggleDescription(this)">Ver más</a>
        <p class="descripcion-producto"style="display: none;">Sistema de alarma inteligente con monitoreo 24/7 y notificaciones instantáneas para proteger tu hogar o negocio.</p>
      </div>
      <div class="producto">
        <h3>Sistema de Acceso Biométrico</h3>
        <img src="imagen/images (1) vxzS.jpeg" alt="Sistema de Acceso" onclick="openModal(this)">
        <a class="btn" onclick="toggleDescription(this)">Ver más</a>
        <p class="descripcion-producto"style="display: none;">Sistema de acceso biométrico con reconocimiento facial y huella digital para una seguridad avanzada y sin complicaciones.</p>
      </div>
      <div class="producto">
        <h3>Kit de Motores para Portones</h3>
        <img src="imagen/Motores Electricos.png" alt="Kit de Motores para Portones" onclick="openModal(this)">
        <a class="btn" onclick="toggleDescription(this)">Ver más</a>
        <p class="descripcion-producto"style="display: none;">Kit de motores eléctricos para portones automáticos, con tecnología silenciosa y eficiente para facilitar el acceso vehicular.</p>
      </div>
    </div>
  </section>

  <section class="servicios section" id="servicios">
    <h2>Nuestros Servicios</h2>
    <p>En JB-Security nos especializamos en ofrecer una amplia gama de servicios diseñados para garantizar tu seguridad y tranquilidad:</p>
    <ul>
      <li>Instalación y mantenimiento de cámaras de seguridad de alta definición.</li>
      <li>Sistemas avanzados de alarmas inteligentes con monitoreo 24/7.</li>
      <li>Control de acceso biométrico para una protección robusta.</li>
      <li>Automatización de portones con kits de motores de última generación.</li>
    </ul>
    <p>Nuestro equipo de expertos está comprometido con tu seguridad y satisfacción, ofreciendo soluciones personalizadas y tecnología de punta para proteger lo que más valoras.</p>
    <a href="#contacto" class="btn">Contáctanos</a>
  </section>

  <section class="acerca section" id="acerca">
    <h2>Acerca de JB-Security Solution</h2>
    <p>En JB-Security Solutions, nos dedicamos a ofrecer soluciones integrales de seguridad para hogares y negocios. Con más de cinco años de experiencia en el sector, nos hemos consolidado como una empresa líder en la venta e instalación de equipos de seguridad de última generación.</p>
    <p>Nuestra misión es proporcionar tranquilidad y protección a nuestros clientes mediante productos y servicios de alta calidad, adaptados a sus necesidades específicas. Creemos en la innovación constante y en la atención personalizada para garantizar la satisfacción total de nuestros clientes.</p>
    <p>Contamos con un equipo de profesionales altamente capacitados que están comprometidos con la excelencia y la seguridad. Desde cámaras de seguridad hasta sistemas de alarma inteligentes, ofrecemos una amplia gama de productos diseñados para mantener lo que más te importa a salvo.</p>
    <p>Gracias por confiar en JB-Security. Estamos aquí para proteger tu hogar y negocio con la tecnología más avanzada y el mejor servicio.</p>
  </section>

  <section class="contacto section" id="contacto">
    <h2>Contacto</h2>
    <div class="form-container">
      <form id="contact-form">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo electrónico" required>
        <textarea name="mensaje" placeholder="Tu mensaje" required></textarea>
        <button type="submit">Enviar</button>
      </form>
      <p>Para más información, contáctanos al 809-254-4899 o visita nuestras redes sociales.</p>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3794.5420551471437!2d-70.65617462507324!3d19.42046984643109!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8eaf88d1d7b88d95%3A0x2b8935a9e8fbc19e!2sBaitoa%2C%20Santiago%20De%20Los%20Caballeros%2C%20Dominican%20Republic!5e0!3m2!1sen!2sdo!4v1690982051377!5m2!1sen!2sdo" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>
    </div>
  </section>

  <section class="cotizacion section" id="cotizacion">
    <h2>Solicita una Cotización</h2>
    <div class="form-container">
      <form id="quote-form">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo electrónico" required>
        <select name="producto" required>
          <option value="" disabled selected>Selecciona un producto</option>
          <option value="motor_portones">Motor para portones</option>
          <option value="alarmas">Alarmas</option>
          <option value="camaras">Cámaras de seguridad</option>
          <option value="biometrico">Acceso biométrico</option>
          <option value="biometrico">Control de acceso</option>
        </select>
        <textarea name="mensaje" placeholder="Detalles adicionales" required></textarea>
        <button type="submit">Solicitar Cotización</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="footer-content">
      <p>&copy; 2024 JB-Security. Todos los derechos reservados.</p>
      <div class="social">
        <a href="https://wa.me/18092544899" target="_blank">
          <img src="imagen/what.png" alt="WhatsApp">
        </a>
        <a href="https://www.instagram.com/Abel.beato" target="_blank">
          <img src="imagen/download.jpg" alt="Instagram">
        </a>
        <a href="https://www.facebook.com/JBSEcurity" target="_blank">
          <img src="imagen/downloadF.png" alt="Facebook">
        </a>
      </div>
    </div>
  </footer>

  <!-- Script JavaScript -->
  <script>
    document.addEventListener('DOMContentLoaded', function() {
      const sections = document.querySelectorAll('.section');
      const menuLinks = document.querySelectorAll('.menu-link');
      const btnVerProductos = document.querySelector('.hero .btn');

      // Función para mostrar la sección objetivo y ocultar las demás
      function showSection(targetId) {
        sections.forEach(section => {
          section.style.display = section.id === targetId ? 'block' : 'none';
        });
      }

      // Evento de clic para los enlaces del menú
      menuLinks.forEach(link => {
        link.addEventListener('click', function(event) {
          event.preventDefault();
          const target = this.getAttribute('data-target');
          showSection(target);
        });
      });

      // Evento de clic para el botón "Ver Productos"
      btnVerProductos.addEventListener('click', function(event) {
        event.preventDefault();
        showSection('productos');
      });

      // Mostrar la sección de inicio por defecto
      showSection('inicio');
    });
  </script>
<script>


// JavaScript para alternar la visibilidad de las descripciones de los productos
function toggleDescription(button) {
  const description = button.nextElementSibling;
  if (description.style.display === "none" || description.style.display === "") {
    description.style.display = "block";
    button.textContent = "Ver menos";
  } else {
    description.style.display = "none";
    button.textContent = "Ver más";
  }
}

// Función para abrir el modal con la imagen en tamaño completo
function openModal(imgElement) {
  const modal = document.createElement("div");
  modal.style.position = "fixed";
  modal.style.top = "0";
  modal.style.left = "0";
  modal.style.width = "100%";
  modal.style.height = "100%";
  modal.style.backgroundColor = "rgba(0, 0, 0, 0.8)";
  modal.style.display = "flex";
  modal.style.justifyContent = "center";
  modal.style.alignItems = "center";
  modal.style.zIndex = "1000";

  const img = document.createElement("img");
  img.src = imgElement.src;
  img.style.maxWidth = "90%";
  img.style.maxHeight = "90%";
  img.style.border = "5px solid white";
  img.style.borderRadius = "10px";

  modal.appendChild(img);
  modal.addEventListener("click", () => {
    document.body.removeChild(modal);
  });

  document.body.appendChild(modal);
}

</script>
<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.12.3/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.12.3/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyCe4rnElCzIOv8nbNV5FeRpd7tVpe4vd3Q",
    authDomain: "jb-security.firebaseapp.com",
    projectId: "jb-security",
    storageBucket: "jb-security.appspot.com",
    messagingSenderId: "762073368278",
    appId: "1:762073368278:web:2fe4c4d0aee4440349eb77",
    measurementId: "G-NKN77G2Y6F"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
</body>
</html>

