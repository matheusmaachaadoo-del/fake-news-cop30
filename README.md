```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>g1 | COP30</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800;900&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Montserrat',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f3f4f6;
color:#111827;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
background:#c4170c;
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 40px;
z-index:999;
box-shadow:0 4px 20px rgba(0,0,0,.2);
}

.logo{
background:white;
color:#c4170c;
padding:8px 18px;
border-radius:14px;
font-size:34px;
font-weight:900;
cursor:pointer;
transition:.3s;
}

.logo:hover{
transform:scale(1.05);
}

nav{
display:flex;
gap:24px;
}

nav a{
color:white;
text-decoration:none;
font-weight:700;
font-size:16px;
}

.hero{
margin-top:85px;
height:95vh;
background:url('https://images.unsplash.com/photo-1493246507139-91e8fad9978e?q=80&w=1600&auto=format&fit=crop') center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
position:relative;
}

.hero::after{
content:'';
position:absolute;
inset:0;
background:rgba(0,0,0,.72);
}

.hero-content{
position:relative;
z-index:2;
max-width:1000px;
padding:20px;
color:white;
animation:fade 1.2s ease;
}

@keyframes fade{
from{
opacity:0;
transform:translateY(30px);
}
to{
opacity:1;
transform:translateY(0);
}
}

.hero-content h1{
font-size:68px;
line-height:1.1;
margin-bottom:30px;
font-weight:900;
}

.hero-content p{
font-size:25px;
line-height:1.8;
}

.container{
max-width:1200px;
margin:auto;
padding:70px 20px;
}

.card{
background:white;
border-radius:28px;
overflow:hidden;
margin-bottom:60px;
box-shadow:0 10px 30px rgba(0,0,0,.1);
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:420px;
object-fit:cover;
}

.card-content{
padding:40px;
}

.tag{
display:inline-block;
background:#c4170c;
color:white;
padding:10px 20px;
border-radius:999px;
font-weight:800;
margin-bottom:22px;
}

.card h2{
font-size:42px;
margin-bottom:24px;
line-height:1.2;
}

.card p{
font-size:21px;
line-height:1.9;
color:#374151;
margin-bottom:30px;
}

.btn{
background:#c4170c;
color:white;
border:none;
padding:18px 30px;
font-size:18px;
font-weight:800;
border-radius:18px;
cursor:pointer;
transition:.3s;
}

.btn:hover{
transform:scale(1.07);
}

.hidden{
display:none;
margin-top:25px;
padding:25px;
background:#f9fafb;
border-left:6px solid #c4170c;
border-radius:18px;
font-size:19px;
line-height:1.8;
animation:fade .5s ease;
}

.comments{
background:white;
padding:50px;
border-radius:28px;
box-shadow:0 10px 30px rgba(0,0,0,.1);
}

.comments h2{
font-size:40px;
margin-bottom:40px;
}

.comment{
margin-bottom:30px;
padding-bottom:25px;
border-bottom:1px solid #ddd;
}

.comment h3{
font-size:22px;
margin-bottom:10px;
}

.comment p{
font-size:20px;
line-height:1.8;
color:#374151;
}

.floating{
position:fixed;
bottom:25px;
right:25px;
background:#c4170c;
color:white;
border:none;
padding:20px 28px;
font-size:18px;
font-weight:900;
border-radius:999px;
cursor:pointer;
box-shadow:0 10px 25px rgba(0,0,0,.3);
transition:.3s;
}

.floating:hover{
transform:scale(1.08);
}

footer{
background:#111827;
color:white;
text-align:center;
padding:40px;
margin-top:50px;
}

footer h3{
font-size:28px;
margin-bottom:12px;
}

@media(max-width:900px){

.hero-content h1{
font-size:42px;
}

.hero-content p{
font-size:20px;
}

.card h2{
font-size:30px;
}

.card p{
font-size:18px;
}

nav{
display:none;
}

}

</style>
</head>

<body>

<header>

<div class="logo" onclick="window.scrollTo({top:0,behavior:'smooth'})">
g1
</div>

<nav>
<a href="#cop30">COP30</a>
<a href="#kyoto">Kyoto</a>
<a href="#onu">ONU</a>
</nav>

</header>

<section class="hero">

<div class="hero-content">

<h1>
COP30 e ONU estariam preparando acordo climático global com novas restrições econômicas até 2035
</h1>

<p>
Publicações compartilhadas nas redes sociais afirmam que representantes internacionais ligados à ONU e à COP30 estariam discutindo novas medidas ambientais capazes de afetar diretamente setores de energia, agricultura e transporte em diversos países.
</p>

</div>
</section>

<div class="container">

<div class="card" id="cop30">

<img src="https://images.unsplash.com/photo-1517048676732-d65bc937f952?q=80&w=1400&auto=format&fit=crop">

<div class="card-content">

<div class="tag">
URGENTE
</div>

<h2>
Documentos vazados da COP30 indicariam novas restrições energéticas globais
</h2>

<p>
Supostos documentos compartilhados em fóruns internacionais afirmam que representantes da COP30 discutiriam medidas para acelerar o abandono de combustíveis fósseis nos próximos anos.
</p>

<button class="btn" onclick="toggleText('texto1')">
Ver documentos vazados
</button>

<div class="hidden" id="texto1">
Os documentos compartilhados nas redes sociais afirmam que reuniões privadas da COP30 discutiriam novas metas ambientais envolvendo energia e circulação de veículos.
</div>

</div>
</div>

<div class="card" id="kyoto">

<img src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=1400&auto=format&fit=crop">

<div class="card-content">

<div class="tag" style="background:#2563eb;">
RELATÓRIO INTERNACIONAL
</div>

<h2>
Protocolo de Kyoto teria iniciado plano internacional de controle ambiental
</h2>

<p>
Relatórios compartilhados em fóruns internacionais afirmam que o Protocolo de Kyoto teria sido o primeiro passo para políticas climáticas globais mais rígidas.
</p>

<button class="btn" style="background:#2563eb;" onclick="toggleText('texto2')">
Abrir relatório secreto
</button>

<div class="hidden" id="texto2">
Usuários afirmam que antigos acordos climáticos internacionais abriram caminho para novas políticas econômicas globais.
</div>

</div>
</div>

<div class="card" id="onu">

<img src="https://images.unsplash.com/photo-1560250097-0b93528c311a?q=80&w=1400&auto=format&fit=crop">

<div class="card-content">

<div class="tag" style="background:#15803d;">
ONU AO VIVO
</div>

<h2>
Representantes internacionais defenderiam ampliação imediata das metas climáticas
</h2>

<p>
Declarações recentes de representantes ligados à ONU aumentaram debates nas redes sociais após discursos envolvendo aceleração das metas ambientais globais.
</p>

<button class="btn" style="background:#15803d;" onclick="toggleText('texto3')">
Assistir entrevista
</button>

<div class="hidden" id="texto3">
Especialistas divulgados nas redes sociais afirmam que novas metas climáticas internacionais poderiam afetar setores agrícolas e industriais.
</div>

</div>
</div>

</div>

<script>

function toggleText(id){

const texto = document.getElementById(id);

if(texto.style.display === 'block'){
texto.style.display = 'none';
}else{
texto.style.display = 'block';
}

}

</script>

</body>
</html>
```
