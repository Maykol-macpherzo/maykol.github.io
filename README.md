```html
<!DOCTYPE html>
<html lang="es">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>INACAP Sede Iquique</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Segoe UI',Tahoma,Geneva,Verdana,sans-serif;
background:#f4f6f9;
color:#333;
line-height:1.7;
}

header{
background:#002c5f;
color:white;
text-align:center;
padding:50px 20px;
}

.logo{
width:180px;
margin-bottom:15px;
}

header h1{
font-size:2.5rem;
margin-bottom:10px;
}

.container{
max-width:1100px;
margin:auto;
padding:35px 20px;
}

.card{
background:white;
padding:30px;
margin-bottom:25px;
border-radius:15px;
box-shadow:0 3px 12px rgba(0,0,0,0.1);
}

.card:hover{
transform:translateY(-3px);
transition:0.3s;
}

h2{
color:#002c5f;
margin-bottom:15px;
border-left:5px solid orange;
padding-left:12px;
}

.info-grid,
.team-grid,
.iniciativas-grid{

display:grid;
gap:20px;
margin-top:20px;

}

.info-grid{
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
}

.team-grid{
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
}

.iniciativas-grid{
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
}

.info-item,
.team-member{
background:#f8fafc;
padding:20px;
border-radius:12px;
}

.team-member{
text-align:center;
border:1px solid #ddd;
}

.team-member h4{
color:#002c5f;
}

.team-member span{
font-size:14px;
color:#666;
}

.areas-list{
display:flex;
flex-wrap:wrap;
gap:10px;
margin-top:15px;
}

.area-tag{
background:#002c5f;
color:white;
padding:8px 15px;
border-radius:20px;
}

.iniciativa{
background:#fff7ed;
padding:20px;
border-radius:12px;
border:1px solid #fed7aa;
}

.iniciativa h4{
color:#c2410c;
margin-bottom:10px;
}

footer{
background:#002c5f;
color:white;
text-align:center;
padding:30px;
margin-top:30px;
}

footer span{
color:orange;
font-weight:bold;
}

@media(max-width:768px){

header h1{
font-size:2rem;
}

.logo{
width:130px;
}

}

</style>

</head>

<body>

<header>

<img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Inacap_logo.png"
alt="Logo INACAP"
class="logo">

<h1>INACAP Sede Iquique</h1>

<p>Instituto Profesional y Centro de Formación Técnica - Región de Tarapacá</p>

</header>

<div class="container">

<div class="card">

<h2>Ubicación y Contacto</h2>

<div class="info-grid">

<div class="info-item">
<strong>Dirección:</strong><br>
Av. La Tirana 4310, Iquique.
</div>

<div class="info-item">
<strong>Teléfono:</strong><br>
(57) 2544900
</div>

<div class="info-item">
<strong>Email:</strong><br>
iquique@inacap.cl
</div>

<div class="info-item">
<strong>CREA Empresa:</strong><br>
Espacios gratuitos con WiFi, cursos y asesorías.
</div>

</div>

</div>

<div class="card">

<h2>Sobre la Sede</h2>

<p>
INACAP Iquique impulsa innovación, emprendimiento,
sustentabilidad y nuevas tecnologías mediante Hub INACAP
y Fábrica 4.0.
</p>

<p>
Posee infraestructura moderna y fuerte relación con empresas
y sectores productivos de Tarapacá.
</p>

</div>

<div class="card">

<h2>Áreas de Estudio</h2>

<div class="areas-list">

<span class="area-tag">Administración</span>
<span class="area-tag">Tecnología</span>
<span class="area-tag">Logística</span>
<span class="area-tag">Energía</span>
<span class="area-tag">Industria Digital</span>

</div>

</div>

<div class="card">

<h2>Comité Ejecutivo</h2>

<div class="team-grid">

<div class="team-member">
<h4>Nevenka Araya Castro</h4>
<span>Vicerrectora</span>
</div>

<div class="team-member">
<h4>Mitzy Avilán Rocca</h4>
<span>Directora Académica</span>
</div>

<div class="team-member">
<h4>José Araya Contreras</h4>
<span>Director Innovación</span>
</div>

</div>

</div>

<div class="card">

<h2>Iniciativas Destacadas</h2>

<div class="iniciativas-grid">

<div class="iniciativa">
<h4>Emplea Chile INACAP</h4>
<p>Conecta personas con oportunidades laborales.</p>
</div>

<div class="iniciativa">
<h4>CREA Empresa</h4>
<p>Apoyo a emprendedores y proyectos.</p>
</div>

<div class="iniciativa">
<h4>NAF</h4>
<p>Asesorías tributarias realizadas por estudiantes.</p>
</div>

</div>

</div>

<div class="card">

<h2>Becas y Beneficios</h2>

<div class="areas-list">

<span class="area-tag">Gratuidad</span>
<span class="area-tag">FUAS</span>
<span class="area-tag">CAE</span>
<span class="area-tag">Becas</span>
<span class="area-tag">TNE</span>

</div>

</div>

</div>

<footer>

<p>Página informativa INACAP Iquique © 2026</p>

<p><span>Creada por Maykol Macpherzo</span></p>

</footer>

</body>
</html>
```
