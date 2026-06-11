```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Estudio Jurídico Serrano | Abogados en Paraguay</title>
  <meta name="description" content="Estudio Jurídico Serrano. Asesoramiento legal profesional en Paraguay. Derecho civil, laboral, familia, comercial y consultoría jurídica.">

  <style>
    :root {
      --azul: #07182e;
      --azul2: #0d2747;
      --dorado: #c8a45d;
      --gris: #f4f6f8;
      --texto: #1f2937;
      --blanco: #ffffff;
    }

    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Georgia, "Times New Roman", serif;
      color: var(--texto);
      background: var(--gris);
      line-height: 1.7;
    }

    a {
      text-decoration: none;
    }

    .topbar {
      background: #020b16;
      color: white;
      padding: 10px 8%;
      font-size: 14px;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 10px;
    }

    nav {
      background: rgba(7, 24, 46, 0.96);
      padding: 18px 8%;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 6px 20px rgba(0,0,0,0.2);
    }

    .logo {
      color: white;
      font-size: 22px;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .logo span {
      color: var(--dorado);
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 22px;
      margin: 0;
      padding: 0;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      font-size: 15px;
      font-weight: bold;
    }

    header {
      min-height: 88vh;
      background:
        linear-gradient(rgba(3, 12, 25, 0.78), rgba(3, 12, 25, 0.82)),
        url("https://images.unsplash.com/photo-1589994965851-a8f479c573a9?auto=format&fit=crop&w=1800&q=80");
      background-size: cover;
      background-position: center;
      color: white;
      display: flex;
      align-items: center;
      padding: 80px 8%;
    }

    .hero {
      max-width: 850px;
    }

    .hero .etiqueta {
      color: var(--dorado);
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
      font-size: 14px;
    }

    .hero h1 {
      font-size: 58px;
      line-height: 1.15;
      margin: 15px 0;
    }

    .hero p {
      font-size: 20px;
      max-width: 750px;
      margin-bottom: 30px;
    }

    .botones {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    .btn {
      background: var(--dorado);
      color: #07182e;
      padding: 14px 28px;
      border-radius: 3px;
      font-weight: bold;
      display: inline-block;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }

    .btn-sec {
      border: 2px solid white;
      color: white;
      padding: 12px 26px;
      border-radius: 3px;
      font-weight: bold;
    }

    section {
      padding: 80px 8%;
    }

    .titulo {
      max-width: 800px;
      margin: 0 auto 50px;
      text-align: center;
    }

    .titulo .sub {
      color: var(--dorado);
      text-transform: uppercase;
      font-weight: bold;
      letter-spacing: 2px;
      font-size: 14px;
    }

    .titulo h2 {
      color: var(--azul);
      font-size: 40px;
      margin: 10px 0;
    }

    .titulo p {
      color: #5b6472;
      font-size: 18px;
    }

    .grid-2 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 40px;
      align-items: center;
    }

    .card {
      background: white;
      padding: 35px;
      border-radius: 8px;
      box-shadow: 0 12px 35px rgba(0,0,0,0.08);
    }

    .card h3 {
      color: var(--azul);
      font-size: 26px;
      margin-top: 0;
    }

    .foto {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 15px 35px rgba(0,0,0,0.18);
    }

    .estadisticas {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      margin-top: -60px;
      position: relative;
      z-index: 5;
      padding: 0 8% 40px;
    }

    .stat {
      background: white;
      padding: 30px;
      text-align: center;
      border-bottom: 5px solid var(--dorado);
      box-shadow: 0 10px 30px rgba(0,0,0,0.12);
    }

    .stat h3 {
      color: var(--azul);
      font-size: 34px;
      margin: 0;
    }

    .stat p {
      margin: 8px 0 0;
      color: #5b6472;
    }

    .servicios {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .servicio {
      background: white;
      padding: 32px;
      border-radius: 8px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.07);
      border-top: 4px solid var(--dorado);
    }

    .servicio h3 {
      color: var(--azul);
      font-size: 24px;
      margin-top: 0;
    }

    .servicio p {
      color: #4b5563;
    }

    .oscuro {
      background:
        linear-gradient(rgba(7, 24, 46, 0.94), rgba(7, 24, 46, 0.94)),
        url("https://images.unsplash.com/photo-1450101499163-c8848c66ca85?auto=format&fit=crop&w=1800&q=80");
      background-size: cover;
      background-position: center;
      color: white;
    }

    .oscuro .titulo h2,
    .oscuro .titulo p {
      color: white;
    }

    .proceso {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .paso {
      background: rgba(255,255,255,0.08);
      padding: 30px;
      border: 1px solid rgba(255,255,255,0.15);
      border-radius: 8px;
    }

    .paso span {
      color: var(--dorado);
      font-size: 36px;
      font-weight: bold;
    }

    .valores {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .valor {
      background: white;
      padding: 30px;
      border-radius: 8px;
      text-align: center;
      box-shadow: 0 10px 25px rgba(0,0,0,0.07);
    }

    .valor h3 {
      color: var(--azul);
    }

    .faq {
      max-width: 900px;
      margin: auto;
    }

    details {
      background: white;
      margin-bottom: 15px;
      padding: 22px;
      border-radius: 6px;
      box-shadow: 0 8px 22px rgba(0,0,0,0.06);
    }

    summary {
      font-weight: bold;
      color: var(--azul);
      cursor: pointer;
      font-size: 18px;
    }

    .contacto {
      background: white;
      border-radius: 10px;
      padding: 40px;
      box-shadow: 0 12px 35px rgba(0,0,0,0.08);
    }

    input, textarea {
      width: 100%;
      padding: 15px;
      margin-bottom: 15px;
      border: 1px solid #cfd6df;
      border-radius: 4px;
      font-size: 16px;
      font-family: Arial, sans-serif;
    }

    textarea {
      min-height: 130px;
    }

    .whatsapp {
      position: fixed;
      right: 20px;
      bottom: 20px;
      background: #25d366;
      color: white;
      padding: 15px 20px;
      border-radius: 50px;
      font-weight: bold;
      box-shadow: 0 8px 25px rgba(0,0,0,0.25);
      z-index: 2000;
      font-family: Arial, sans-serif;
    }

    footer {
      background: #020b16;
      color: white;
      padding: 40px 8%;
      text-align: center;
    }

    .aviso {
      font-size: 13px;
      color: #b8c0cc;
      max-width: 900px;
      margin: 20px auto 0;
    }

    @media (max-width: 768px) {
      nav {
        display: block;
        text-align: center;
      }

      nav ul {
        justify-content: center;
        margin-top: 15px;
      }

      .hero h1 {
        font-size: 38px;
      }

      .hero p {
        font-size: 18px;
      }

      .topbar {
        text-align: center;
        justify-content: center;
      }
    }
  </style>
</head>

<body>

<div class="topbar">
  <div>📍 Paraguay</div>
  <div>✉️ estudiojuridicoserranopy@gmail.com</div>
</div>

<nav>
  <div class="logo">Estudio Jurídico <span>Serrano</span></div>
  <ul>
    <li><a href="#inicio">Inicio</a></li>
    <li><a href="#estudio">El Estudio</a></li>
    <li><a href="#areas">Áreas</a></li>
    <li><a href="#proceso">Proceso</a></li>
    <li><a href="#contacto">Contacto</a></li>
  </ul>
</nav>

<header id="inicio">
  <div class="hero">
    <div class="etiqueta">Asesoramiento legal profesional</div>
    <h1>Soluciones jurídicas serias, claras y estratégicas</h1>
    <p>
      En Estudio Jurídico Serrano brindamos acompañamiento legal integral
      con responsabilidad, ética profesional y compromiso con cada cliente.
      Analizamos cada situación con precisión para ofrecer respuestas legales
      claras y efectivas.
    </p>

    <div class="botones">
      <a class="btn" href="#contacto">Solicitar consulta</a>
      <a class="btn-sec" href="#areas">Conocer servicios</a>
    </div>
  </div>
</header>

<div class="estadisticas">
  <div class="stat">
    <h3>100%</h3>
    <p>Atención personalizada</p>
  </div>
  <div class="stat">
    <h3>24h</h3>
    <p>Recepción de consultas</p>
  </div>
  <div class="stat">
    <h3>+6</h3>
    <p>Áreas de asesoramiento</p>
  </div>
  <div class="stat">
    <h3>PY</h3>
    <p>Servicios en Paraguay</p>
  </div>
</div>

<section id="estudio">
  <div class="titulo">
    <div class="sub">Nuestro enfoque</div>
    <h2>Un estudio jurídico orientado a resultados</h2>
    <p>
      Asistencia legal con trato humano, confidencialidad y estrategia jurídica.
    </p>
  </div>

  <div class="grid-2">
    <div class="card">
      <h3>Compromiso, análisis y defensa de sus derechos</h3>
      <p>
        Cada caso requiere una evaluación seria. Por eso escuchamos al cliente,
        estudiamos los antecedentes, identificamos los riesgos y proponemos
        alternativas legales concretas.
      </p>
      <p>
        Nuestro objetivo es brindar tranquilidad, seguridad jurídica y una
        orientación clara para que cada persona pueda tomar decisiones informadas.
      </p>
      <p>
        Trabajamos con estricta reserva profesional, comunicación transparente
        y acompañamiento durante todas las etapas del proceso legal.
      </p>
    </div>

    <img class="foto" src="https://images.unsplash.com/photo-1521791055366-0d553872125f?auto=format&fit=crop&w=1200&q=80" alt="Asesoramiento jurídico profesional">
  </div>
</section>

<section id="areas">
  <div class="titulo">
    <div class="sub">Áreas de práctica</div>
    <h2>Servicios jurídicos integrales</h2>
    <p>
      Asesoramiento para particulares, familias, trabajadores, empresas y emprendedores.
    </p>
  </div>

  <div class="servicios">
    <div class="servicio">
      <h3>Derecho Civil</h3>
      <p>Contratos, obligaciones, daños y perjuicios, desalojos, cobros, sucesiones y conflictos civiles.</p>
    </div>

    <div class="servicio">
      <h3>Derecho de Familia</h3>
      <p>Divorcio, asistencia alimentaria, régimen de relacionamiento, filiación, guarda y acuerdos familiares.</p>
    </div>

    <div class="servicio">
      <h3>Derecho Laboral</h3>
      <p>Despidos, liquidaciones, reclamos salariales, conflictos laborales y asesoramiento preventivo.</p>
    </div>

    <div class="servicio">
      <h3>Derecho Comercial</h3>
      <p>Contratos comerciales, cobros, asesoramiento a empresas, documentos y prevención de riesgos legales.</p>
    </div>

    <div class="servicio">
      <h3>Documentos Legales</h3>
      <p>Redacción y revisión de contratos, intimaciones, acuerdos privados, escritos y solicitudes.</p>
    </div>

    <div class="servicio">
      <h3>Consultoría Jurídica</h3>
      <p>Orientación legal para prevenir conflictos, evaluar alternativas y tomar decisiones seguras.</p>
    </div>
  </div>
</section>

<section class="oscuro" id="proceso">
  <div class="titulo">
    <div class="sub">Forma de trabajo</div>
    <h2>Proceso de atención</h2>
    <p>Un método claro para analizar cada consulta con seriedad.</p>
  </div>

  <div class="proceso">
    <div class="paso">
      <span>01</span>
      <h3>Consulta inicial</h3>
      <p>Escuchamos el caso, identificamos el problema y reunimos la información principal.</p>
    </div>

    <div class="paso">
      <span>02</span>
      <h3>Análisis jurídico</h3>
      <p>Estudiamos los documentos, antecedentes, riesgos y posibles caminos legales.</p>
    </div>

    <div class="paso">
      <span>03</span>
      <h3>Estrategia</h3>
      <p>Proponemos alternativas claras, explicando ventajas, límites y próximos pasos.</p>
    </div>

    <div class="paso">
      <span>04</span>
      <h3>Acompañamiento</h3>
      <p>Brindamos seguimiento profesional durante el trámite, negociación o proceso.</p>
    </div>
  </div>
</section>

<section>
  <div class="titulo">
    <div class="sub">Principios</div>
    <h2>Valores profesionales</h2>
  </div>

  <div class="valores">
    <div class="valor">
      <h3>Confidencialidad</h3>
      <p>Reserva absoluta en el tratamiento de cada consulta.</p>
    </div>

    <div class="valor">
      <h3>Responsabilidad</h3>
      <p>Estudio serio y detallado de cada situación legal.</p>
    </div>

    <div class="valor">
      <h3>Claridad</h3>
      <p>Explicaciones comprensibles y orientación transparente.</p>
    </div>

    <div class="valor">
      <h3>Compromiso</h3>
      <p>Acompañamiento profesional enfocado en soluciones.</p>
    </div>
  </div>
</section>

<section>
  <div class="titulo">
    <div class="sub">Preguntas frecuentes</div>
    <h2>Información útil antes de consultar</h2>
  </div>

  <div class="faq">
    <details>
      <summary>¿La primera consulta puede realizarse online?</summary>
      <p>Sí. Las consultas pueden coordinarse de forma presencial u online, según disponibilidad y necesidad del cliente.</p>
    </details>

    <details>
      <summary>¿Qué documentos debo presentar?</summary>
      <p>Depende del caso. Es recomendable contar con contratos, mensajes, recibos, notificaciones, documentos personales o cualquier antecedente relacionado.</p>
    </details>

    <details>
      <summary>¿Atienden asuntos familiares, laborales y civiles?</summary>
      <p>Sí. El estudio brinda orientación en distintas áreas jurídicas, incluyendo derecho civil, familia, laboral, comercial y asesoramiento documental.</p>
    </details>

    <details>
      <summary>¿La información de mi caso es confidencial?</summary>
      <p>Sí. Toda consulta es tratada con reserva profesional y respeto por la privacidad del cliente.</p>
    </details>
  </div>
</section>

<section id="contacto">
  <div class="titulo">
    <div class="sub">Contacto</div>
    <h2>Solicite asesoramiento legal</h2>
    <p>Complete el formulario o escriba directamente por correo electrónico.</p>
  </div>

  <div class="grid-2">
    <div class="contacto">
      <h3>Datos de contacto</h3>
      <p><strong>Estudio:</strong> Estudio Jurídico Serrano</p>
      <p><strong>Email:</strong> estudiojuridicoserranopy@gmail.com</p>
      <p><strong>Ubicación:</strong> Paraguay</p>
      <p><strong>Modalidad:</strong> Atención presencial y online</p>

      <a class="btn" href="mailto:estudiojuridicoserranopy@gmail.com">Enviar correo</a>
    </div>

    <div class="contacto">
      <h3>Formulario de consulta</h3>

      <form action="mailto:estudiojuridicoserranopy@gmail.com" method="post" enctype="text/plain">
        <input type="text" name="Nombre" placeholder="Nombre completo" required>
        <input type="email" name="Correo" placeholder="Correo electrónico" required>
        <input type="text" name="Telefono" placeholder="Teléfono o WhatsApp">
        <input type="text" name="Area" placeholder="Área de consulta: civil, laboral, familia, etc.">
        <textarea name="Consulta" placeholder="Describa brevemente su consulta legal"></textarea>
        <button class="btn" type="submit">Enviar consulta</button>
      </form>
    </div>
  </div>
</section>

<a class="whatsapp" href="https://wa.me/595981000000" target="_blank">
  WhatsApp
</a>

<footer>
  <p><strong>Estudio Jurídico Serrano</strong></p>
  <p>Asesoramiento legal profesional en Paraguay</p>
  <p>© 2026 Estudio Jurídico Serrano. Todos los derechos reservados.</p>

  <p class="aviso">
    La información publicada en este sitio tiene carácter meramente informativo
    y no constituye asesoramiento legal específico. Para una orientación adecuada,
    cada caso debe ser analizado de forma particular por un profesional.
  </p>
</footer>

</body>
</html>
```
