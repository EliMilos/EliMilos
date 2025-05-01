## Hi there 👋
Soy Elian Mancero, estudiante de la carrera de Tecnologías de la Información con experiencia en lenguajes como C#, JavaScript y SQL. Me especializo en el desarrollo de aplicaciones tanto frontend como backend, con una base sólida en el diseño, gestión y optimización de bases de datos. Además, tengo interés en el análisis de datos, aplicando técnicas para extraer información útil que apoye la toma de decisiones. Me enfoco en construir soluciones eficientes, bien estructuradas y alineadas con las necesidades reales de los proyectos.

<!--
Soy Elian Mancero, desarrollador con experiencia en lenguajes como C#, JavaScript y SQL. Me especializo en el desarrollo de aplicaciones tanto frontend como backend, con una base sólida en el diseño, gestión y optimización de bases de datos. Además, tengo interés en el análisis de datos, aplicando técnicas para extraer información útil que apoye la toma de decisiones. Me enfoco en construir soluciones eficientes, bien estructuradas y alineadas con las necesidades reales de los proyectos.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<section>
  <h2 id="typewriter"></h2>
</section>

<section>
    <h2>Lenguajes y Tecnologías</h2>
    <ul>
      <li><strong>Lenguajes:</strong> C#, JavaScript, SQL</li>
      <li><strong>Frontend:</strong> HTML5, JavaScript</li>
      <li><strong>Bases de Datos:</strong> SQL Server, MySQL</li>
      <li><strong>Herramientas:</strong> Git, GitHub, Visual Studio, VS Code</li>
    </ul>
  </section>

  <section>
    <h2>Áreas de Interés</h2>
    <ul>
      <li>Desarrollo web full stack</li>
      <li>Diseño y optimización de bases de datos</li>
      <li>Análisis de datos y visualización</li>
      <li>Automatización de procesos con scripts</li>
    </ul>
  </section>

  <section>
    <h2>Proyectos Destacados</h2>
    <ul>
      <li>Sistema de punto de venta con ASP.NET y SQL Server</li>
      <li>Dashboard interactivo para análisis de datos con Python y Plotly</li>
      <li>Aplicaciones web responsivas con React</li>
    </ul>
  </section>

  <section>
    <h2>Más sobre mí</h2>
    <p>
      Fuera del mundo del desarrollo, disfruto aprender sobre nuevas tecnologías, participar en comunidades de código abierto y explorar datos por curiosidad.
    </p>
    <p><strong>Pasatiempos:</strong> Lectura, videojuegos, streams.</p>
    <p><strong>Gustos musicales:</strong> Rock alternativo, Pop</p>
  </section>

  <footer>
    <p>Gracias por visitar mi perfil. ¡Conectemos y creemos algo genial!</p>
  </footer>

  <script>
  const text = "💻 Bienvenido a mi perfil de GitHub...";
  let i = 0;
  function typeWriter() {
    if (i < text.length) {
      document.getElementById("typewriter").innerHTML += text.charAt(i);
      i++;
      setTimeout(typeWriter, 75);
    }
  }
  window.onload = typeWriter;
</script>

