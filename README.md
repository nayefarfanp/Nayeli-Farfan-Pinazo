
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Página de Nayeli</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #f2f2f2, #e6ecf3);
      margin: 0;
      padding: 0;
      color: #112d4e;
    }
    header {
      background-color: #4682B4;
      color: white;
      padding: 30px 20px;
      text-align: center;
      position: relative;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
    }
    .foto-esquina {
      position: absolute;
      top: 15px;
      right: 15px;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid white;
      box-shadow: 0 0 12px rgba(0, 0, 0, 0.3);
    }
    .contenido {
      max-width: 900px;
      margin: 40px auto;
      background-color: #f9f9f9;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }
    section h2, section h3 {
      color: #3f72af;
      margin-top: 25px;
    }
    a {
      color: #2c3e50;
      text-decoration: none;
    }
    a:hover {
      color: #4682B4;
      text-decoration: underline;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }
    @media (max-width: 600px) {
      .foto-esquina {
        width: 70px;
        height: 70px;
        top: 10px;
        right: 10px;
      }
      header h1 {
        font-size: 1.8em;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>¡Hola! Soy Nayeli</h1>
    <p>Bienvenido/a a mi página web</p>
    <img src="foto.jpg" alt="Mi foto" class="foto-esquina">
  </header>

  <section class="contenido">
    <h2>Sobre mí:</h2>
    <p>Soy Angeles Nayeli Farfan Pinazo. Actualmente soy estudiante de la <a href="https://ucsp.edu.pe/">Universidad Católica San Pablo</a> y me encuentro en el quinto semestre de la carrera de <a href="https://ucsp.edu.pe/carreras/administracion-negocios/">Administración de Negocios</a>.</p>
    <p>Soy una persona creativa, honesta y adaptable, tanto en el trabajo como en mi vida personal.</p>
    <h2>Trayectoria</h2>
    <p><strong>Formación:</strong></p>
    <ul>
      <li><a href="https://cnspilar.edu.pe/">Colegio Nuestra Señora del Pilar</a> (inicial-primaria-secundaria)</li>
      <li><a href="https://ucsp.edu.pe/">Universidad Católica San Pablo</a> (educación superior - actualidad)</li>
    </ul>
    <h3>Estoy Cursando:</h3>
    <ul>
      <li>Análisis financiero</li>
      <li>Macroeconomía</li>
      <li>Teología II</li>
      <li>Moral</li>
      <li>Introducción a Ciencia de la Computación (profesor: <a href="https://www.linkedin.com/in/ecuadrosv/">Ernesto Cuadros</a>)</li>
    </ul>
    <h3>Idiomas:</h3>
    <ul>
      <li>Francés (avanzado)</li>
      <li>Inglés (intermedio)</li>
      <li>Español (nativo)</li>
    </ul>
    <h3>Compañeros:</h3>
    <ul>
      <li><a href="https://mariapazgonzalesleon.github.io/">Maria Paz Gonzales</a></li>
      <li><a href="https://josuemontenegro.com/">Josue Montenegro</a></li>
      <li><a href="https://ariana6240.github.io/ArianaMicaelaFernandezCarpio/">Ariana Fernandez</a></li>
      <li><a href="https://mariaquintog.github.io/">Maria Alessandra Quinto</a></li>
      <li><a href="https://kiacondo.github.io/mipaginawebdma/">Danamaris Condo</a></li>
    </ul>
    <h3>Contacto:</h3>
    <ul>
      <li><a href="https://www.linkedin.com/in/angeles-nayeli-farfan-pinazo-575523359/">LinkedIn</a></li>
      <li><a href="https://github.com/nayefarfanp">GitHub</a></li>
    </ul>
  </section>
  <footer>
    © 2025 Nayeli Farfan - Todos los derechos reservados
  </footer>
</body>
</html>

