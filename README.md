# index.html

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>g1 | Acordos Climáticos</title>

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
background:#f1f5f9;
color:#111827;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
background:#c4170c;
padding:18px 40px;
display:flex;
align-items:center;
justify-content:space-between;
z-index:999;
box-shadow:0 4px 20px rgba(0,0,0,.2);
}

.logo{
background:white;
color:#c4170c;
padding:8px 18px;
font-size:34px;
font-weight:900;
border-radius:14px;
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
height:90vh;
background:url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1800&auto=format&fit=crop') center/cover;
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
background:rgba(0,0,0,.65);
}

.hero-content{
position:relative;
z-index:2;
max-width:950px;
padding:20px;
color:white;
}

.hero-content h1{
font-size:64px;
font-weight:900;
margin-bottom:28px;
line-height:1.1;
}

.hero-content p{
font-size:24px;
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
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
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
font-size:46px;
margin-bottom:24px;
line-height:1.2;
}

.card p{
font-size:22px;
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
transform:scale(1.05);
}

.extra{
background:#111827;
color:white;
border-radius:28px;
overflow:hidden;
display:grid;
grid-template-columns:1fr 1fr;
margin-bottom:60px;
}

.extra img{
width:100%;
height:100%;
object-fit:cover;
}

.extra-content{
padding:50px;
display:flex;
flex-direction:column;
justify-content:center;
}

.extra h2{
font-size:48px;
margin-bottom:26px;
}

.extra p{
font-size:22px;
line-height:2;
color:#e5e7eb;
}

.comments{
background:white;
padding:50px;
border-radius:28px;
box-shadow:0 10px 30px rgba(0,0,0,.1);
}

.comments h2{
font-size:42px;
margin-bottom:40px;
}

.comment{
margin-bottom:30px;
padding-bottom:25px;
border-bottom:1px solid #ddd;
}

.comment h3{
margin-bottom:10px;
font-size:22px;
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
animation:bounce 2s infinite;
}

@keyframes bounce{
0%,100%{transform:translateY(0)}
50%{transform:translateY(-8px)}
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

.card h2,
.extra h2{
font-size:34px;
}

.card p,
.extra p{
font-size:18px;
}

.extra{
grid-template-columns:1fr;
}

nav{
display:none;
}
}
</style>
</head>

<body>

<header>
<div class="logo" onclick="window.scrollTo({top:0,behavior:'smooth'})">g1</div>

<nav>
<a href="#cop30">COP30</a>
<a href="#kyoto">Kyoto</a>
<a href="#onu">ONU</a>
</nav>
</header>

<section class="hero">
<div class="hero-content">
<h1>
COP30 estaria preparando acordo climático global com novas restrições econômicas
</h1>

<p>
Documentos compartilhados nas redes sociais afirmam que líderes internacionais ligados à ONU estariam preparando um novo acordo climático global durante reuniões da COP30. Segundo os conteúdos divulgados online, as medidas envolveriam aumento de impostos ambientais, restrições energéticas e novas metas obrigatórias para diversos países até 2035.
</p>
</div>
</section>

<div class="container">

<div class="card" id="cop30">
<img src="https://images.unsplash.com/photo-1493246507139-91e8fad9978e?q=80&w=1400&auto=format&fit=crop">

<div class="card-content">
<div class="tag">URGENTE</div>

<h2>
COP30 estaria preparando acordo climático global até 2035
</h2>

<p>
Documentos vazados indicariam que a COP30 prepara um novo acordo internacional capaz de aumentar o controle ambiental sobre países em desenvolvimento. Segundo especialistas independentes divulgados nas redes sociais, líderes globais discutiriam restrições severas ao uso de combustíveis, produção agrícola e circulação de veículos particulares até 2035.
</p>

<button class="btn" onclick="document.getElementById('detalhes1').scrollIntoView({behavior:'smooth'})">
Ver documentos vazados
</button>
</div>
</div>

<div class="card" id="kyoto">
<img src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=1400&auto=format&fit=crop">

<div class="card-content">
<div class="tag" style="background:#2563eb">
RELATÓRIO INTERNACIONAL
</div>

<h2>
Protocolo de Kyoto teria sido o início do plano climático global
</h2>

<p>
Relatórios compartilhados por grupos internacionais afirmam que o Protocolo de Kyoto teria iniciado um plano silencioso para reduzir atividades industriais em diversos países. As novas metas climáticas estariam provocando aumento no preço da energia, fechamento de empresas e crescimento de impostos ambientais em várias regiões do mundo.
</p>

<button class="btn" style="background:#2563eb" onclick="document.getElementById('detalhes2').scrollIntoView({behavior:'smooth'})">
Abrir relatório secreto
</button>
</div>
</div>

<div class="card" id="onu">
<img src="https://images.unsplash.com/photo-1560250097-0b93528c311a?q=80&w=1400&auto=format&fit=crop">

<div class="card-content">
<div class="tag" style="background:#15803d">
ONU AO VIVO
</div>

<h2>
ONU defenderia ampliação imediata dos acordos climáticos
</h2>

<p>
Representantes ligados à ONU teriam defendido durante reuniões privadas a criação de novas regras globais sobre emissão de carbono, consumo de energia e produção agrícola. Segundo os conteúdos compartilhados online, os acordos climáticos avançariam para limitar atividades econômicas consideradas poluentes.
</p>

<button class="btn" style="background:#15803d" onclick="document.getElementById('detalhes3').scrollIntoView({behavior:'smooth'})">
Assistir entrevista completa
</button>
</div>
</div>

<div class="extra" id="detalhes1">
<img src="https://images.unsplash.com/photo-1517048676732-d65bc937f952?q=80&w=1400&auto=format&fit=crop">

<div class="extra-content">
<h2>
Bastidores secretos da COP30
</h2>

<p>
Fontes internacionais afirmam que documentos discutidos nos bastidores da COP30 revelariam planos para acelerar metas climáticas globais. Entre as medidas estariam possíveis limitações ao uso de veículos movidos a combustíveis fósseis, aumento de taxas ambientais e redução gradual de atividades consideradas altamente poluentes.
</p>
</div>
</div>

<div class="extra" id="detalhes2">
<img src="https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?q=80&w=1400&auto=format&fit=crop">

<div class="extra-content">
<h2>
Relatório internacional vazado
</h2>

<p>
Analistas independentes divulgados nas redes sociais afirmam que antigos acordos climáticos internacionais abriram caminho para novas políticas econômicas globais. Segundo os relatórios compartilhados online, governos estariam ampliando medidas ambientais que impactariam diretamente indústrias, energia e transporte.
</p>
</div>
</div>

<div class="extra" id="detalhes3">
<img src="https://images.unsplash.com/photo-1541872703-74c5e44368f9?q=80&w=1400&auto=format&fit=crop">

<div class="extra-content">
<h2>
Entrevista internacional exclusiva
</h2>

<p>
Durante entrevistas recentes, representantes internacionais teriam reforçado a necessidade de acelerar acordos climáticos globais ligados à emissão de carbono e ao consumo energético. As declarações aumentaram debates nas redes sociais sobre possíveis impactos econômicos das novas metas ambientais.
</p>
</div>
</div>

<div class="comments">
<h2>
Comentários em alta
</h2>

<div class="comment">
<h3>Carlos Henrique</h3>
<p>
“Agora faz sentido porque estão acelerando esses acordos climáticos.”
</p>
</div>

<div class="comment">
<h3>Fernanda Souza</h3>
<p>
“Quase ninguém comenta os impactos econômicos dessas decisões globais.”
</p>
</div>

<div class="comment">
<h3>Ricardo Alves</h3>
<p>
“A população precisa entender melhor o que está sendo decidido nessas reuniões.”
</p>
</div>
</div>
</div>

<button class="floating" onclick="alert('🚨 Compartilhado com sucesso!')">
🚨 Compartilhe rápido
</button>

<footer>
<h3>
Projeto escolar • Portal de notícias
</h3>

<p>
Desenvolvido por Matheus Soares e Luiz Tavares
</p>
</footer>

</body>
</html>
```

