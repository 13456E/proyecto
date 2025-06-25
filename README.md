<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Embellecimiento de Áreas Verdes</title>

  <style>
    :root {
      --verde: #4caf50;
      --claro: #f0fdf4;
      --blanco: #ffffff;
      --gris: #444;
      --sombra: rgba(0, 0, 0, 0.06);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: var(--claro);
      color: var(--gris);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #388e3c, var(--verde));
      color: var(--blanco);
      text-align: center;
      padding: 2rem 1rem;
    }

    header h1 {
      font-size: 2rem;
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 2rem 1rem;
    }

    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
    }

    .galeria img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 2px 8px var(--sombra);
      object-fit: cover;
      height: 150px;
      transition: transform 0.2s ease;
    }

    .galeria img:hover {
      transform: scale(1.03);
    }

    footer {
      background: #2e7d32;
      color: white;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      .galeria img {
        height: 120px;
      }
    }
  </style>

  <style>
    :root {
      --verde: #4caf50;
      --verde-claro: #dcedc8;
      --gris-claro: #f9f9f9;
      --gris-oscuro: #333;
      --blanco: #ffffff;
      --sombra: rgba(0, 0, 0, 0.08);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--gris-claro);
      color: var(--gris-oscuro);
      line-height: 1.6;
    }

    header {
      background-image: linear-gradient(to right, var(--verde), #81c784);
      color: var(--blanco);
      padding: 3rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 2rem 1rem;
    }

    section {
      background: var(--blanco);
      margin-bottom: 2rem;
      padding: 2rem;
      border-radius: 16px;
      box-shadow: 0 4px 12px var(--sombra);
      transition: transform 0.2s ease;
    }

    section:hover {
      transform: translateY(-3px);
    }

    section h2 {
      color: var(--verde);
      margin-bottom: 1rem;
      font-size: 1.8rem;
    }

    section ul {
      padding-left: 1.2rem;
    }

    section ul li {
      margin-bottom: 0.5rem;
    }

    footer {
      background-color: #2e7d32;
      color: var(--blanco);
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      section {
        padding: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Embellecimiento de Áreas Verdes</h1>
    <p>Transformando espacios con la fuerza de la comunidad</p>
  </header>

  <main>
    <section>
      <h2>🌿 Planeación del Proyecto</h2>
      <p>Antes de comenzar con las labores de mejora, se llevó a cabo una evaluación del terreno. Se realizaron cálculos precisos para definir el sistema de riego y se midió cuidadosamente el área a intervenir para una organización efectiva.</p>
      <p>Con el apoyo voluntario de la comunidad escolar, se reunieron fondos para adquirir los materiales necesarios: tuberías, plantas ornamentales y herramientas de jardinería.
<section>
 
  <h2>🎥 Video del Proyecto</h2>
  <div style="max-width: 350px; margin: auto;">
    <video src="video.mp4" controls style="width: 100%; height: auto; border-radius: 12px; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);"></video>
  </div>


</section>
</p>
    </section>

    <section>
      <h2>📸 Imagen del Proyecto</h2>
      <p>Fotografía de cómo lucía el área antes, durante y después de la intervención.
<div class="galeria">
      <img src="7.jpeg" alt="Foto 7">
 <img src="3.jpeg" alt="Foto 3">
<img src="1.jpeg" alt="Foto 1">
 </div>
</p>
    </section>

    <section>
      <h2>🌱 Actividades Realizadas</h2>
      <ul>
        <li>Separación y recolección de residuos.</li>
        <li>Colocación de letreros con mensajes ecológicos.</li>
        <li>Plantación de arbustos y flores, incluyendo durantas.</li>
        <li>Decoración con piedras naturales.</li>
        <li>Instalación de un sistema de riego funcional.</li>
        <li>Mantenimiento continuo del espacio verde.</li>
      </ul>
    </section>

    <section>
      <h2>🌼 Importancia del Espacio Verde</h2>
      <ul>
        <li>Mejora la salud ambiental del entorno escolar.</li>
        <li>Fomenta el sentido de pertenencia y la responsabilidad ecológica.</li>
        <li>Reduce focos de infección y evita acumulación de desechos.</li>
        <li>Promueve valores ecológicos en los estudiantes.</li>
      </ul>
    </section>

    <section>
      <h2>🤝 Trabajo en Comunidad</h2>
      <p>La coordinación previa y el compromiso de estudiantes, docentes y voluntarios fueron clave en el éxito del proyecto. Gracias al esfuerzo colectivo, se logró transformar un espacio común en un entorno limpio, armonioso y útil para todos.</p>
      <p>El resultado refleja el poder de la colaboración y el impacto positivo que puede tener una comunidad unida por el cuidado del medio ambiente.</p>
    </section>
  </main>
<center><button onclick="location.href='galeria.html'" 
        style="padding: 10px 20px; background-color: #4caf50; color: white; border: none; border-radius: 8px; cursor: pointer; font-size: 1rem;">
  Galería de Fotos
</button></center>

  <footer>
    Embellecimiento de áreas verdes | Nahomy Rene Bustamante Andrade
  </footer>
</body>
</html>

