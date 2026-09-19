<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ciclo de Vida del Desarrollo Móvil</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    font-family: Georgia, 'Times New Roman', serif;
    line-height: 1.8;
    color: #2c3e50;
    background: #f0f4f8;
  }
  header {
    background: linear-gradient(135deg, rgba(30,60,114,0.92), rgba(42,82,152,0.85)),
                url('https://images.unsplash.com/photo-1512941937669-90a1b58e7e9c?w=1600&q=80');
    background-size: cover;
    background-position: center;
    color: #fff;
    padding: 90px 20px;
    text-align: center;
  }
  header h1 {
    font-size: 2.8em;
    margin-bottom: 12px;
    letter-spacing: 1px;
    text-shadow: 2px 2px 8px rgba(0,0,0,0.5);
  }
  header p {
    font-size: 1.15em;
    opacity: 0.95;
    font-style: italic;
    text-shadow: 1px 1px 4px rgba(0,0,0,0.5);
  }
  nav {
    background: #1e3c72;
    padding: 15px;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 10;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
  }
  nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 12px;
    font-size: 0.95em;
    font-family: Arial, sans-serif;
    font-weight: bold;
    transition: color 0.3s;
  }
  nav a:hover { color: #ffd166; }
  main {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 20px;
  }
  article {
    background: #fff;
    padding: 35px 40px;
    margin-bottom: 35px;
    border-radius: 12px;
    box-shadow: 0 4px 18px rgba(0,0,0,0.08);
    border-top: 5px solid #2a5298;
    transition: transform 0.3s, box-shadow 0.3s;
  }
  article:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 24px rgba(0,0,0,0.12);
  }
  article#inicio { border-top-color: #06b6d4; }
  article#diseno { border-top-color: #f59e0b; }
  article#desarrollo { border-top-color: #10b981; }
  article#pruebas { border-top-color: #ef4444; }
  article#despliegue { border-top-color: #8b5cf6; }
  article#mantenimiento { border-top-color: #ec4899; }

  article h2 {
    color: #1e3c72;
    font-size: 1.8em;
    margin-bottom: 8px;
    padding-bottom: 8px;
    border-bottom: 3px solid #e0e7ef;
  }
  article .meta {
    font-family: Arial, sans-serif;
    font-size: 0.85em;
    color: #7f8c8d;
    margin-bottom: 20px;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  article h3 {
    color: #2a5298;
    margin: 22px 0 10px;
    font-size: 1.2em;
  }
  article p { margin-bottom: 15px; text-align: justify; }
  article ul, article ol { margin: 10px 0 15px 30px; }
  article li { margin-bottom: 6px; }

  .imagen-blog {
    width: 100%;
    height: 260px;
    object-fit: cover;
    border-radius: 10px;
    margin: 18px 0;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }
  .imagen-blog:hover { opacity: 0.95; }

  .cita {
    border-left: 5px solid #f59e0b;
    background: #fff8e6;
    padding: 15px 22px;
    margin: 20px 0;
    font-style: italic;
    color: #7c5a00;
    border-radius: 0 8px 8px 0;
  }

  .referencias {
    background: #fff;
    padding: 35px 40px;
    border-radius: 12px;
    box-shadow: 0 4px 18px rgba(0,0,0,0.08);
    border-top: 5px solid #1e3c72;
  }
  .referencias h2 {
    color: #1e3c72;
    padding-bottom: 8px;
    margin-bottom: 20px;
    border-bottom: 3px solid #e0e7ef;
  }
  .referencias p {
    text-indent: -30px;
    padding-left: 30px;
    margin-bottom: 12px;
    font-size: 0.95em;
  }

  footer {
    background: #1e3c72;
    color: #fff;
    text-align: center;
    padding: 35px 20px;
    font-family: Arial, sans-serif;
    font-size: 0.9em;
    margin-top: 40px;
  }
  footer p { opacity: 0.9; }

  @media (max-width: 600px) {
    header h1 { font-size: 1.9em; }
    header { padding: 60px 20px; }
    article { padding: 25px 20px; }
    nav a { display: inline-block; margin: 5px 8px; font-size: 0.85em; }
    .imagen-blog { height: 180px; }
  }
</style>
</head>
<body>

<header>
  <h1>📱 Ciclo de Vida del Desarrollo Móvil</h1>
  <p>Un recorrido por las etapas del desarrollo de aplicaciones móviles</p>
</header>

<nav>
  <a href="#intro">Introducción</a>
  <a href="#inicio">Inicio</a>
  <a href="#diseno">Diseño</a>
  <a href="#desarrollo">Desarrollo</a>
  <a href="#pruebas">Pruebas</a>
  <a href="#despliegue">Despliegue</a>
  <a href="#mantenimiento">Mantenimiento</a>
  <a href="#referencias">Referencias</a>
</nav>

<main>

<article id="intro">
  <h2>🚀 Introducción al Ciclo de Vida del Desarrollo Móvil</h2>
  <p class="meta">Publicado en Septiembre 2026</p>
  <img class="imagen-blog" src="https://images.unsplash.com/photo-1522199755839-a2bacb67c546?w=1200&q=80" alt="Desarrollo móvil">
  <p>El ciclo de vida del desarrollo móvil (Mobile Application Development Lifecycle, MADLC) es el conjunto de etapas que se siguen para crear, probar, desplegar y mantener una aplicación móvil. A diferencia del ciclo de vida tradicional de software, el desarrollo móvil debe enfrentar restricciones específicas como la diversidad de dispositivos, sistemas operativos (Android, iOS), tamaños de pantalla y limitaciones de hardware (Rahim et al., 2020).</p>
  <p>Comprender este ciclo permite a los equipos planificar mejor los recursos, reducir riesgos y entregar productos de mayor calidad. A continuación se describen las fases principales.</p>
</article>

<article id="inicio">
  <h2>💡 Fase 1: Inicio o Identificación</h2>
  <p class="meta">Etapa de conceptualización</p>
  <img class="imagen-blog" src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?w=1200&q=80" alt="Ideas y planificación">
  <p>En esta primera etapa se define la idea de la aplicación. Se analiza el mercado, la competencia y las necesidades del usuario objetivo. El resultado principal es un documento de visión que responde preguntas como: ¿qué problema resuelve la app?, ¿quiénes la usarán?, ¿en qué plataformas se publicará?</p>
  <p>Según Pressman y Maxim (2020), esta fase equivale a la ingeniería de requisitos, donde se recopilan las necesidades funcionales y no funcionales del sistema.</p>
  <div class="cita">"La identificación adecuada de los requisitos reduce hasta en un 50% los costos de corrección en etapas posteriores" (Pressman &amp; Maxim, 2020, p. 112).</div>
</article>

<article id="diseno">
  <h2>🎨 Fase 2: Diseño</h2>
  <p class="meta">UX, UI y arquitectura</p>
  <img class="imagen-blog" src="https://images.unsplash.com/photo-1581291518857-4e27b48ff24e?w=1200&q=80" alt="Diseño UX UI">
  <p>El diseño se divide en dos grandes áreas: la experiencia de usuario (UX) y la interfaz de usuario (UI). En UX se definen los flujos de navegación y la arquitectura de la información; en UI se trabaja el aspecto visual, los colores, tipografías e iconografía.</p>
  <h3>Actividades principales</h3>
  <ul>
    <li>Creación de wireframes y prototipos.</li>
    <li>Definición de la arquitectura del sistema (MVC, MVVM, etc.).</li>
    <li>Selección del stack tecnológico (nativo, híbrido o multiplataforma).</li>
    <li>Diseño de la base de datos local y remota.</li>
  </ul>
  <p>Una buena práctica es validar los prototipos con usuarios reales antes de escribir una sola línea de código (Nielsen, 2020).</p>
</article>

<article id="desarrollo">
  <h2>💻 Fase 3: Desarrollo</h2>
  <p class="meta">Construcción del código</p>
  <img class="imagen-blog" src="https://images.unsplash.com/photo-1551650975-87deedd944c3?w=1200&q=80" alt="Programación móvil">
  <p>Es la etapa más extensa del ciclo. Aquí los desarrolladores implementan las funcionalidades definidas en el diseño. Se puede optar por desarrollo nativo (Kotlin/Java para Android, Swift para iOS), híbrido (Ionic, Cordova) o multiplataforma (Flutter, React Native).</p>
  <h3>Buenas prácticas</h3>
  <ol>
    <li>Usar control de versiones (Git).</li>
    <li>Aplicar integración continua (CI).</li>
    <li>Documentar el código.</li>
    <li>Realizar revisiones de código entre pares.</li>
  </ol>
</article>

<article id="pruebas">
  <h2>🧪 Fase 4: Pruebas</h2>
  <p class="meta">Aseguramiento de calidad</p>
  <img class="imagen-blog" src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=1200&q=80" alt="Pruebas de software">
  <p>Las pruebas verifican que la aplicación funcione correctamente en distintos dispositivos, versiones del sistema operativo y condiciones de red. Se realizan pruebas unitarias, de integración, de usabilidad y de rendimiento.</p>
  <ul>
    <li><strong>Pruebas unitarias:</strong> verifican componentes individuales.</li>
    <li><strong>Pruebas de integración:</strong> comprueban la interacción entre módulos.</li>
    <li><strong>Pruebas de usabilidad:</strong> evalúan la experiencia del usuario.</li>
    <li><strong>Pruebas de rendimiento:</strong> miden velocidad y consumo de recursos.</li>
  </ul>
</article>

<article id="despliegue">
  <h2>🚀 Fase 5: Despliegue</h2>
  <p class="meta">Publicación en tiendas</p>
  <img class="imagen-blog" src="https://images.unsplash.com/photo-1607252650355-f7fd0460ccdb?w=1200&q=80" alt="App Store y Google Play">
  <p>Una vez probada, la aplicación se publica en las tiendas oficiales: Google Play Store y Apple App Store. Cada tienda tiene sus propios requisitos de revisión, políticas y tiempos de aprobación.</p>
  <p>Es común usar canales de prueba como beta cerrada o abierta antes del lanzamiento oficial, lo que permite corregir errores con un grupo reducido de usuarios (Google, 2024).</p>
</article>

<article id="mantenimiento">
  <h2>🔧 Fase 6: Mantenimiento</h2>
  <p class="meta">Evolución continua</p>
  <img class="imagen-blog" src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?w=1200&q=80" alt="Mantenimiento de aplicaciones">
  <p>El lanzamiento no es el final. Después de publicar, la app requiere actualizaciones para corregir errores, adaptarse a nuevas versiones de Android/iOS, mejorar el rendimiento y agregar funcionalidades. Esta fase puede durar años y consume una parte importante del presupuesto total del proyecto.</p>
  <p>El mantenimiento se clasifica en correctivo, adaptativo, perfectivo y preventivo (Sommerville, 2020).</p>
</article>

<article class="referencias" id="referencias">
  <h2>📚 Referencias (Normas APA 7.ª edición)</h2>
  <p>Google. (2024). <em>App testing and release best practices</em>. Android Developers. https://developer.android.com/</p>
  <p>Nielsen, J. (2020). <em>Usability engineering</em>. Morgan Kaufmann.</p>
  <p>Pressman, R. S., &amp; Maxim, B. R. (2020). <em>Ingeniería del software: Un enfoque práctico</em> (9.ª ed.). McGraw-Hill.</p>
  <p>Rahim, N. H. A., Ahmad, R., &amp; Ismail, N. (2020). Mobile application development lifecycle: A systematic review. <em>Journal of Software Engineering</em>, 14(2), 45-58.</p>
  <p>Sommerville, I. (2020). <em>Software engineering</em> (10.ª ed.). Pearson.</p>
</article>

</main>

<footer>
  <p>· Ciclo de Vida del Desarrollo Móvil · 2026</p>
  <p>· Alan Ariel Monterroso Dieguez · 3190-23-14991</p>
  <p>· Análisis de sistemas II ·</p>
</footer>

</body>
</html>
