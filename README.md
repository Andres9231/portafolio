<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gustavo Barraza | Portafolio</title>

  <!-- Fuente principal -->
  <link href="https://fonts.googleapis.com/css2?family=Mea+Culpa&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&display=swap" rel="stylesheet">

  <!-- Estilos personalizados -->
  <link rel="stylesheet" href="estilo.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>

<body>
  <header>
    <h1>Gustavo Barraza - Riwi Developer</h1>
    <img src="IMG_20231225_142030_388.jpg" alt="Foto de perfil" class="imagen-circular">
  </header>

  <nav>
    <a href="#sobre-mi">Sobre mí</a>
    <a href="#habilidades">Habilidades</a>
    <a href="#proyectos">Proyectos</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="sobre-mi">
    <h2>Sobre Mí</h2>
    <p>Hola, soy Gustavo Barraza, un apasionado por el aprendizaje constante y la mejora personal</p>
    <p>Me desempeño como auxiliar contable desde hace varios años, lo que me ha permitido desarrollar una gran atencion al detalle, habilidades analiticas y una solida etica de trabajo</p>
    <p>Actualmente, estoy formandome como desarrollador web frontend, explorando el mundo del HTML, CSS JavaScript y Python. Creo fielmente en el poder de la tecnologia como herramienta para tansformar ideas en soluciones prácticas y visuales.</p>
    <p>Mi objetivo es combinar mis conocimientosadministrativos y contables en el desarrollo web para aportar valor a proyectos que marquen la diferencia.</p>
  </section>

  <section id="habilidades">
    <h2>Habilidades Técnicas</h2>
    <ul>
      <li>Contabilidad General</li>
      <li>Administración y Gestión Documental</li>
      <li>Manejo de Software Ofimático</li>
      <li>Redacción de Documentos Institucionales</li>
      <li>Desarrollo de Contenido para Emprendimientos</li>
      <li>Programación en Python</li>
      <li>Desarrollo Web Frontend</li>
    </ul>
  </section>

  <section id="proyectos">
    <h2>Mis Proyectos</h2>
    <div class="proyecto">
      <img src="descarga.jpeg" alt="Proyecto Inventario">
      <h3>Inventario en Python</h3>
      <p>Aplicación de consola para gestionar productos en una tienda. Incluye funciones de búsqueda, actualización y cálculo de valor total.</p>
    </div>
    <div class="proyecto">
      <img src="Captura desde 2025-05-22 15-22-30.png" alt="Proyecto Portafolio">
      <h3>Diseño de Página de Portafolio</h3>
      <p>Página web en HTML y CSS para mostrar información personal, proyectos y datos de contacto.</p>
    </div>
  </section>
  <section id="proyectos">
    <h2>Mis Proyectos</h2>
  
    <table class="tabla-proyectos">
      <thead>
        <tr>
          <th>Nombre del Proyecto</th>
          <th>Descripción</th>
          <th>Enlace</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Inventario en Python</td>
          <td>Aplicación de consola para gestionar productos, búsqueda, actualización y total.</td>
          <td><a href="https://github.com/Andres9231/gestion-de-inventario/blob/main/Prueba%20de%20desempe%C3%B1o2.0%20.py" target="_blank">Ver proyecto</a></td>
        </tr>
        <tr>
          <td>Portafolio Web</td>
          <td>Diseño web personal en HTML y CSS para mostrar perfil profesional.</td>
          <td><a href="https://github.com/Andres9231/portafolio" target="_blank">Ver proyecto</a></td>
        </tr>
      </tbody>
    </table>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <form action="/send" method="post">
      <label for="name">Nombre:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Correo electrónico:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Mensaje:</label>
      <textarea id="message" name="message" rows="4" required></textarea>

      <input type="submit" value="Enviar">
    </form>
  </section>

  <div class="redes">
    <a href="https://www.facebook.com/andybarrazae" target="_blank">
      <i class="fab fa-facebook fa-2x"></i>
    </a>
    <a href="https://www.instagram.com/andybarrazae/" target="_blank">
      <i class="fab fa-instagram fa-2x"></i>      
    </a>   
    <a href="https:https://github.com/Andres9231" target="_blank">
      <i class="fab fa-github fa-2x"></i>  
    </div>

  </section>

  <footer>
    <p>&copy; 2025 Gustavo Barraza. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
