```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Estudio Jurídico Serrano | Asesoramiento Legal</title>

  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      color: #1f2937;
      background: #f4f6f8;
      line-height: 1.6;
    }

    header {
      min-height: 90vh;
      background:
        linear-gradient(rgba(8, 20, 36, 0.82), rgba(8, 20, 36, 0.82)),
        url("https://images.unsplash.com/photo-1589829545856-d10d557cf95f?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
      color: white;
      display: flex;
      align-items: center;
      text-align: center;
      padding: 30px;
    }

    .hero {
      max-width: 950px;
      margin: auto;
    }

    .hero h1 {
      font-size: 52px;
      margin-bottom: 10px;
      letter-spacing: 1px;
    }

    .hero h2 {
      font-size: 24px;
      font-weight: 400;
      color: #d6b46c;
      margin-bottom: 25px;
    }

    .hero p {
      font-size: 19px;
      max-width: 800px;
      margin: 0 auto 30px;
    }

    .btn {
      display: inline-block;
      padding: 14px 28px;
      background: #c9a24d;
      color: #0b1f3a;
      text-decoration: none;
      border-radius: 4px;
      font-weight: 700;
      margin: 8px;
    }

    .btn.secundario {
      background: transparent;
      color: white;
      border: 2px solid white;
    }

    nav {
      background: #0b1f3a;
      padding: 15px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 14px;
      font-weight: 600;
    }

    section {
      max-width: 1200px;
      margin: auto;
      padding: 70px 25px;
    }

    .titulo {
      text-align: center;
      margin-bottom: 45px;
    }

    .titulo h2 {
      font-size: 36px;
      color: #0b1f3a;
      margin-bottom: 10px;
    }

    .titulo p {
      color: #6b7280;
      font-size: 18px;
    }

    .grid-2 {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 35px;
      align-items: center;
    }

    .card, .servicio, .valor {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    }

    .imagen {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }

    .servicios {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
    }

    .servicio {
      border-top: 5px solid #c9a24d;
    }

    .servicio h3 {
      color: #0b1f3a;
      margin-top: 0;
    }

    .franja {
      background:
        linear-gradient(rgba(11, 31, 58, 0.9), rgba(11, 31, 58, 0.9)),
        url("https://images.unsplash.com/photo-1450101499163-c8848c66ca85?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      max-width: none;
      padding: 80px 25px;
    }

    .franja h2 {
      font-size: 36px;
      margin-bottom: 15px;
    }

    .valores {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .valor h3 {
      color: #0b1f3a;
    }

    .contacto {
      background: #ffffff;
      border-radius: 10px;
      padding: 40px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    }

    input, textarea {
      width: 100%;
      padding: 14px;
      margin-bottom: 15px;
      border: 1px solid #d1d5db;
      border-radius: 5px;
      font-size: 16px;
    }

    textarea {
      height: 130px;
    }

    footer {
      background: #061426;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    footer p {
      margin: 5px;
    }

    @media (max-width: 700px) {
      .hero h1 {
        font-size: 36px;
      }

      nav a {
        display: inline-block;
        margin: 8px;
      }
    }
  </style>
</head>

<body>

<header id="inicio">
  <div class="hero">
    <h1>Estudio Jurídico Serrano</h1>
    <h2>Asesoramiento legal serio, profesional y estratégico</h2>
    <p>
      Brindamos soluciones jurídicas integrales para personas, familias,
      trabajadores, empresas y emprendedores, con atención personalizada,
      responsabilidad profesional y absoluta confidencialidad.
    </p>
    <a class="btn" href="#contacto">Solicitar consulta</a>
    <a class="btn secundario" href="#servicios">Ver servicios</a>
  </div>
</header>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#nosotros">Nosotros</a>
  <a href="#servicios">Servicios</a>
  <a href="#valores">Valores</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="nosotros">
  <div class="titulo">
    <h2>Sobre el Estudio</h2>
    <p>Compromiso jurídico con enfoque humano y profesional.</p>
  </div>

  <div class="grid-2">
    <div>
      <img class="imagen" src="https://images.unsplash.com/photo-1521791055366-0d553872125f?auto=format&fit=crop&w=900&q=80" alt="Reunión profesional">
    </div>

    <div class="card">
      <h3>Defensa, asesoramiento y acompañamiento legal</h3>
      <p>
        En Estudio Jurídico Serrano trabajamos con responsabilidad, ética y
        dedicación para proteger los derechos e intereses de nuestros clientes.
        Cada caso es analizado de manera particular, buscando soluciones claras,
        eficientes y ajustadas a la normativa vigente.
      </p>
      <p>
        Nuestro servicio se basa en la comunicación transparente, el estudio
        detallado de cada situación y la planificación de estrategias legales
        orientadas a obtener los mejores resultados posibles.
      </p>
    </div>
  </div>
</section>

<section id="servicios">
  <div class="titulo">
    <h2>Áreas de Práctica</h2>
    <p>Servicios jurídicos para distintas necesidades legales.</p>
  </div>

  <div class="servicios">
    <div class="servicio">
      <h3>Derecho Civil</h3>
      <p>
        Contratos, obligaciones, reclamos, daños y perjuicios, sucesiones,
        desalojos, cobros de deuda y asesoramiento civil en general.
      </p>
    </div>

    <div class="servicio">
      <h3>Derecho de Familia</h3>
      <p>
        Divorcios, asistencia alimentaria, régimen de relacionamiento,
        filiación, guarda, acuerdos familiares y protección de derechos.
      </p>
    </div>

    <div class="servicio">
      <h3>Derecho Laboral</h3>
      <p>
        Despidos, liquidaciones, reclamos salariales, contratos laborales,
        conflictos entre trabajador y empleador, y asesoramiento preventivo.
      </p>
    </div>

    <div class="servicio">
      <h3>Derecho Comercial</h3>
      <p>
        Asesoramiento a empresas, emprendedores y comerciantes. Contratos,
        cobros, documentos comerciales y prevención de riesgos legales.
      </p>
    </div>

    <div class="servicio">
      <h3>Redacción de Documentos</h3>
      <p>
        Elaboración y revisión de contratos, acuerdos privados, intimaciones,
        escritos, solicitudes y documentos legales personalizados.
      </p>
    </div>

    <div class="servicio">
      <h3>Consultoría Legal</h3>
      <p>
        Orientación jurídica clara para tomar decisiones informadas antes de
        iniciar reclamos, firmar documentos o resolver conflictos.
      </p>
    </div>
  </div>
</section>

<section class="franja">
  <h2>Atención personalizada y confidencial</h2>
  <p>
    Cada consulta es tratada con seriedad, reserva profesional y compromiso.
    Nuestro objetivo es brindar tranquilidad y soluciones jurídicas efectivas.
  </p>
  <a class="btn" href="#contacto">Contactar ahora</a>
</section>

<section id="valores">
  <div class="titulo">
    <h2>Nuestros Valores</h2>
    <p>Principios que guían nuestro trabajo profesional.</p>
  </div>

  <div class="valores">
    <div class="valor">
      <h3>Confidencialidad</h3>
      <p>Tratamos cada caso con absoluta reserva y respeto por la privacidad del cliente.</p>
    </div>

    <div class="valor">
      <h3>Responsabilidad</h3>
      <p>Analizamos cada situación con seriedad, precisión y compromiso profesional.</p>
    </div>

    <div class="valor">
      <h3>Claridad</h3>
      <p>Explicamos las opciones legales de forma comprensible para facilitar decisiones.</p>
    </div>

    <div class="valor">
      <h3>Compromiso</h3>
      <p>Acompañamos al cliente durante todo el proceso con atención personalizada.</p>
    </div>
  </div>
</section>

<section id="contacto">
  <div class="titulo">
    <h2>Contacto</h2>
    <p>Solicite una consulta legal.</p>
  </div>

  <div class="grid-2">
    <div class="contacto">
      <h3>Datos de contacto</h3>
      <p><strong>Email:</strong> estudiojuridicoserranopy@gmail.com</p>
      <p><strong>Ubicación:</strong> Paraguay</p>
      <p><strong>Atención:</strong> Consultas jurídicas presenciales y online</p>

      <a class="btn" href="mailto:estudiojuridicoserranopy@gmail.com">
        Enviar correo
      </a>
    </div>

    <div class="contacto">
      <h3>Formulario de consulta</h3>

      <form action="mailto:estudiojuridicoserranopy@gmail.com" method="post" enctype="text/plain">
        <input type="text" name="Nombre" placeholder="Nombre completo" required>
        <input type="email" name="Email" placeholder="Correo electrónico" required>
        <input type="text" name="Telefono" placeholder="Teléfono o WhatsApp">
        <textarea name="Consulta" placeholder="Escriba brevemente su consulta legal"></textarea>
        <button class="btn" type="submit">Enviar consulta</button>
      </form>
    </div>
  </div>
</section>

<footer>
  <p><strong>Estudio Jurídico Serrano</strong></p>
  <p>Asesoramiento legal profesional en Paraguay</p>
  <p>© 2026 Estudio Jurídico Serrano. Todos los derechos reservados.</p>
</footer>

</body>
</html>
```

