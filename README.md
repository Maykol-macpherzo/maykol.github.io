<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INACAP Sede Iquique</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f4f6f9;
            color: #333;
            line-height: 1.7;
        }

        header {
            background: #002c5f;
            color: white;
            text-align: center;
            padding: 60px 20px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.2);
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .card {
            background: white;
            border-radius: 16px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h2 {
            color: #002c5f;
            font-size: 1.8rem;
            margin-bottom: 15px;
            border-left: 5px solid #ff6b00;
            padding-left: 15px;
        }

        .card p {
            margin-bottom: 12px;
            text-align: justify;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .info-item {
            background: #f8fafc;
            border-radius: 12px;
            padding: 20px;
            border-left: 4px solid #ff6b00;
        }

        .info-item strong {
            color: #002c5f;
            display: block;
            margin-bottom: 5px;
        }

        .areas-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }

        .area-tag {
            background: #002c5f;
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .team-member {
            background: #f8fafc;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            border: 1px solid #e2e8f0;
        }

        .team-member h4 {
            color: #002c5f;
            margin-bottom: 5px;
        }

        .team-member span {
            color: #64748b;
            font-size: 0.85rem;
        }

        .team-member p {
            margin-top: 8px;
            font-size: 0.85rem;
            color: #475569;
        }

        .iniciativas-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .iniciativa {
            background: #fff7ed;
            border-radius: 12px;
            padding: 20px;
            border: 1px solid #fed7aa;
        }

        .iniciativa h4 {
            color: #c2410c;
            margin-bottom: 8px;
        }

        .iniciativa p {
            font-size: 0.9rem;
            color: #7c2d12;
        }

        .footer-credit {
            background: #002c5f;
            color: white;
            text-align: center;
            padding: 30px 20px;
            margin-top: 40px;
            font-size: 1.1rem;
        }

        .footer-credit span {
            color: #ff6b00;
            font-weight: bold;
        }

        .map-placeholder {
            background: #e2e8f0;
            border-radius: 12px;
            height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #64748b;
            font-size: 1.1rem;
            margin-top: 15px;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>INACAP Sede Iquique</h1>
        <p>Instituto Profesional y Centro de Formación Técnica - Región de Tarapacá</p>
    </header>

    <div class="container">

        <div class="card">
            <h2>Ubicación y Contacto</h2>
            <div class="info-grid">
                <div class="info-item">
                    <strong>Dirección</strong>
                    Av. La Tirana #4310, Iquique<br>Región de Tarapacá, Chile
                </div>
                <div class="info-item">
                    <strong>Teléfono</strong>
                    (57) 2 544900
                </div>
                <div class="info-item">
                    <strong>Correo Electrónico</strong>
                    iquique@inacap.cl
                </div>
                <div class="info-item">
                    <strong>Red Crea Empresa</strong>
                    Espacios de uso gratuito con WiFi, cursos y asesoría para emprendimientos
                </div>
            </div>
        </div>

        <div class="card">
            <h2>Sobre la Sede</h2>
            <p>
                INACAP Sede Iquique, por medio del <strong>Hub INACAP</strong> y la <strong>Fábrica 4.0</strong>, se ha posicionado como un actor relevante en el quehacer educativo de la Región de Tarapacá. Fomenta en sus estudiantes, docentes y administrativos una cultura de <strong>innovación, emprendimiento, sustentabilidad y globalización</strong>, a través de la difusión, actualización y perfeccionamiento en nuevas competencias, tecnologías y recursos alineados con las tendencias y necesidades del territorio y el Sello Institucional.
            </p>
            <p>
                Con la incorporación de <strong>más de 5.000 m²</strong> a sus dependencias, la Sede Iquique cuenta con una estrecha vinculación con el sector productivo y de servicios de la región, impartiendo programas de estudio en diversos sectores estratégicos.
            </p>
        </div>

        <div class="card">
            <h2>Áreas de Estudio</h2>
            <p>La Sede Iquique imparte programas de estudio en los siguientes sectores:</p>
            <div class="areas-list">
                <span class="area-tag">Administración y Servicios</span>
                <span class="area-tag">Energía y Sustentabilidad</span>
                <span class="area-tag">Mantenimiento y Logística</span>
                <span class="area-tag">Tecnología Aplicada</span>
                <span class="area-tag">Diseño e Industria Digital</span>
            </div>
        </div>

        <div class="card">
            <h2>Comité Ejecutivo</h2>
            <div class="team-grid">
                <div class="team-member">
                    <h4>Nevenka Araya Castro</h4>
                    <span>Vicerrectora de Sede</span>
                    <p>naraya@inacap.cl<br>(57) 254 4905</p>
                </div>
                <div class="team-member">
                    <h4>Mitzy Avilán Rocca</h4>
                    <span>Directora Académica</span>
                    <p>mavilan@inacap.cl<br>(57) 254 4907</p>
                </div>
                <div class="team-member">
                    <h4>Alberto Chong Kwork</h4>
                    <span>Director de Educación Continua</span>
                    <p>achong@inacap.cl<br>(57) 254 4909</p>
                </div>
                <div class="team-member">
                    <h4>Fanny Letelier Muñoz</h4>
                    <span>Directora de Administración y Finanzas</span>
                    <p>fletelierm@inacap.cl<br>+56 57 254 4908</p>
                </div>
                <div class="team-member">
                    <h4>José Araya Contreras</h4>
                    <span>Director de Innovación y Vinculación con el Medio</span>
                    <p>j_arayac@inacap.cl<br>(57) 254 5633</p>
                </div>
                <div class="team-member">
                    <h4>Danitza Tapia Ramos</h4>
                    <span>Directora de Asuntos Estudiantiles</span>
                    <p>dtapiar@inacap.cl<br>(57) 254 4904</p>
                </div>
                <div class="team-member">
                    <h4>Diego Rojas Ceballos</h4>
                    <span>Director de Admisión y Comunicaciones</span>
                    <p>d_rojas@inacap.cl<br>(57) 254 5602</p>
                </div>
            </div>
        </div>

        <div class="card">
            <h2>Iniciativas Destacadas</h2>
            <div class="iniciativas-grid">
                <div class="iniciativa">
                    <h4>Emplea Chile INACAP</h4>
                    <p>Red laboral gratuita que conecta personas con oportunidades reales de empleo mediante Inteligencia Artificial y acompañamiento personalizado.</p>
                </div>
                <div class="iniciativa">
                    <h4>CREA Empresa INACAP</h4>
                    <p>Espacios de CoWork de uso gratuito con WiFi, cursos y asesoría para potenciar el desarrollo de emprendimientos y su formalización.</p>
                </div>
                <div class="iniciativa">
                    <h4>Consejo Productivo Regional Tarapacá</h4>
                    <p>Articula el ecosistema territorial para alcanzar una Formación Técnico Profesional pertinente para las metas y desafíos del territorio.</p>
                </div>
                <div class="iniciativa">
                    <h4>Núcleo de Apoyo Fiscal (NAF)</h4>
                    <p>Módulos de atención gratuita donde estudiantes asesoran a pequeños contribuyentes en temáticas tributarias, complementando el servicio del SII.</p>
                </div>
                <div class="iniciativa">
                    <h4>RED Exalumnos Destacados</h4>
                    <p>Red de titulados reconocidos como líderes y portadores del Sello INACAP, transformando el mundo y siendo referentes para nuevas generaciones.</p>
                </div>
                <div class="iniciativa">
                    <h4>Revista INACAP Iquique</h4>
                    <p>Espacio que muestra el quehacer institucional en todas sus áreas académicas y la relación con empresas públicas y sector privado de la región.</p>
                </div>
            </div>
        </div>

        <div class="card">
            <h2>Becas y Beneficios</h2>
            <p>INACAP Sede Iquique es una institución adscrita a la <strong>Gratuidad</strong>. Además, los estudiantes pueden acceder a diversos beneficios:</p>
            <div class="areas-list" style="margin-top: 15px;">
                <span class="area-tag">Gratuidad</span>
                <span class="area-tag">Postulación FUAS</span>
                <span class="area-tag">Becas</span>
                <span class="area-tag">Convenios</span>
                <span class="area-tag">CAE</span>
                <span class="area-tag">TNE</span>
            </div>
        </div>

        <div class="card">
            <h2>Admisión</h2>
            <p>INACAP cuenta con un <strong>sistema de admisión sin rendición de PAES</strong>, facilitando el acceso a la educación superior técnico-profesional. Para más información:</p>
            <div class="info-grid" style="margin-top: 15px;">
                <div class="info-item">
                    <strong>Teléfono Admisión</strong>
                    800 20 25 20
                </div>
                <div class="info-item">
                    <strong>Correo Admisión</strong>
                    informaciones@inacap.cl
                </div>
            </div>
        </div>

    </div>

    <div class="footer-credit">
        Página informativa sobre INACAP Sede Iquique | &copy; 2026<br><br>
        <span>Creada por Maykol Macpherzo</span>
    </div>

</body>
</html>
