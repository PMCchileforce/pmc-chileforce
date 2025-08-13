
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PMC CHILEFORCE SPA - Contratista Multinacional</title>
  <meta name="description" content="Contratista multinacional de servicios nacionales e internacionales: recursos humanos, seguridad, tecnologías y logística.">
  <style>
    :root {
      --azul:#0a1f44;
      --azul2:#142850;
      --gris:#f1f3f5;
      --dorado:#d4af37;
      --texto:#333;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: Arial, Helvetica, sans-serif;
      color: var(--texto);
      background: #f8f9fa;
      line-height: 1.6;
    }
    a { color: inherit; text-decoration: none; }
    header.hero {
      background: linear-gradient(rgba(10,31,68,.6),rgba(10,31,68,.6)),
                  url('https://images.unsplash.com/photo-1504384308090-c894fdcc538d') center/cover no-repeat;
      color: #fff;
      text-align: center;
      padding: 100px 20px;
    }
    header.hero h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }
    header.hero p {
      font-size: 18px;
      margin-bottom: 20px;
    }
    .cta {
      background: var(--dorado);
      color: #000;
      padding: 12px 18px;
      border-radius: 999px;
      font-weight: bold;
      display: inline-block;
    }
    nav {
      background: var(--azul2);
      display: flex;
      gap: 20px;
      justify-content: center;
      padding: 12px;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      color: #fff;
      font-weight: bold;
      transition: color 0.2s;
    }
    nav a:hover { color: var(--dorado); }
    section {
      max-width: 1100px;
      margin: auto;
      padding: 50px 20px;
    }
    h2 { color: var(--azul); margin-bottom: 20px; }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px,1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      border-radius: 14px;
      box-shadow: 0 6px 20px rgba(0,0,0,.06);
      padding: 20px;
      transition: transform .25s, box-shadow .25s;
    }
    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 28px rgba(0,0,0,.12);
    }
    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 12px;
    }
    footer {
      background: var(--azul);
      color: #fff;
      text-align: center;
      padding: 24px;
    }
    .whatsapp-btn {
      position: fixed;
      right: 18px;
      bottom: 18px;
      background: #25d366;
      color: #fff;
      width: 52px;
      height: 52px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 26px;
      box-shadow: 0 8px 22px rgba(0,0,0,.25);
    }
  </style>
</head>
<body>

<header class="hero">
  <h1>PMC CHILEFORCE SPA</h1>
  <p>Contratista multinacional de servicios nacionales e internacionales: Recursos Humanos, Seguridad, Tecnologías y Logística.</p>
  <a class="cta" href="#contacto">Solicitar presupuesto</a>
</header>

<nav>
  <a href="#quienes">Quiénes somos</a>
  <a href="#servicios">Servicios</a>
  <a href="#mision">Misión & Visión</a>
  <a href="#certificaciones">Certificaciones</a>
  <a href="#cobertura">Cobertura</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="quienes">
  <h2>Quiénes somos</h2>
  <p>Desde el año 2000, nuestro fundador David Gil Barak inició estudios de mercado para responder a la creciente necesidad de personal calificado a nivel nacional e internacional. En 2014 se fundó Gomverg Ltda. y en 2022 evolucionamos a <strong>PMC CHILEFORCE SPA</strong>, consolidándonos como una empresa multinacional de servicios con presencia en múltiples sectores. Contamos con escuela de formación y laboratorio de innovación para garantizar la calidad, ética y profesionalismo de nuestro personal.</p>
</section>

<section id="servicios">
  <h2>Áreas de Servicio</h2>
  <div class="cards">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1581091215360-6c2c9bdfbc46" alt="Recursos Humanos" loading="lazy">
      <h3>Recursos Humanos</h3>
      <p>Selección, capacitación y suministro de personal en todas las áreas: industria, construcción, minería, salud, hotelería, logística, retail y eventos.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1599058917212-d750089bc07a" alt="Seguridad" loading="lazy">
      <h3>Seguridad</h3>
      <p>Seguridad física e industrial, eventos, transporte de valores, vigilancia electrónica, drones, K-9 y ciberseguridad.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1618328932548-d5f7c639e6f8" alt="Tecnologías" loading="lazy">
      <h3>Tecnologías</h3>
      <p>CCTV, control de acceso, mallas electrificadas, sistemas inteligentes y soluciones digitales.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1529078155058" alt="Logística" loading="lazy">
      <h3>Logística</h3>
      <p>Transporte especializado, suministro de personal operativo y apoyo en operaciones nacionales e internacionales.</p>
    </div>
  </div>
</section>

<section id="mision">
  <h2>Misión, Visión y Política</h2>
  <p><strong>Misión:</strong> Exceder expectativas ofreciendo servicios integrales de recursos humanos, seguridad y tecnología, con transparencia y compromiso.</p>
  <p><strong>Visión:</strong> Afianzarnos como referente multinacional combinando tradición, modernidad y responsabilidad social.</p>
  <p><strong>Política de Seguridad:</strong> Cumplir con normativas OS-10, ISO 45001 y estándares internacionales para salvaguardar personas, bienes y operaciones.</p>
</section>

<section id="certificaciones">
  <h2>Certificaciones</h2>
  <ul>
    <li>OS-10 Carabineros de Chile</li>
    <li>Mutual de Seguridad IST</li>
    <li>ISO 45001</li>
    <li>Cumplimiento Ley N° 16.744</li>
  </ul>
</section>

<section id="cobertura">
  <h2>Cobertura</h2>
  <p>Presencia en la zona centro y sur de Chile, con proyección internacional.</p>
  <ul>
    <li>Quilpué – Fundo El Sauce, Parcela N° 23</li>
    <li>Melipilla – Santa Rosa de Esmeralda, Parcela N° 27</li>
  </ul>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p><strong>Representante Legal:</strong> David Gil Barak — 📞 +56 9 6563 8785 — ✉️ mijailbarak79k02company@gmail.com / gilbarak1979@gmail.com</p>
  <p><strong>Socio Gerente de Transporte y Maquinaria Pesada:</strong> Rafael Silva Lobos — 📞 +56 9 7125 4621</p>
  <p><strong>Supervisor General de Operaciones:</strong> Pablo Espinoza — 📞 +56 9 7866 9077 — ✉️ pablo_andres_1970@hotmail.com</p>
  <p><strong>Supervisores AG. PPI:</strong> Hernán Calderón — 📞 +56 9 9004 3694 | David Meza — 📞 +56 9 4053 2662 | Fernanda Navarro — 📞 +56 9 4876 1864</p>
  <p><strong>Supervisor ITO Mantención:</strong> Jaime Carreño — 📞 +56 9 4052 1781</p>
</section>

<a class="whatsapp-btn" href="https://wa.me/56965638785" target="_blank" aria-label="WhatsApp">💬</a>

<footer>
  <p>&copy; 2025 PMC CHILEFORCE SPA — Todos los derechos reservados.</p>
</footer>

</body>
</html>
