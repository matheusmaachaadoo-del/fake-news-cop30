<html>
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
overflow-x:hidden;
}

img{
max-width:100%;
display:block;
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
flex-wrap:wrap;
gap:15px;
}

.logo{
background:white;
color:#c4170c;
padding:8px 18px;
border-radius:14px;
font-size:34px;
font-weight:900;
cursor:pointer;
}

nav{
display:flex;
gap:24px;
flex-wrap:wrap;
}

nav a{
color:white;
text-decoration:none;
font-weight:700;
font-size:16px;
}

.hero{
margin-top:95px;
min-height:100vh;
background:url('https://images.unsplash.com/photo-1569163139394-de4e4f43e4e5?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
position:relative;
padding:60px 20px;
overflow:hidden;
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
max-width:1100px;
width:100%;
padding:20px;
color:white;
animation:fade 1s ease;
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
font-size:clamp(38px,6vw,78px);
line-height:1.1;
margin-bottom:35px;
font-weight:900;
word-break:break-word;
}

.hero-content p{
font-size:clamp(22px,2.5vw,30px);
line-height:1.8;
max-width:980px;
margin:auto;
}

.container{
max-width:1250px;
margin:auto;
padding:80px 20px;
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
height:500px;
object-fit:cover;
}

.card-content{
padding:45px;
}

.tag{
display:inline-block;
background:#c4170c;
color:white;
padding:12px 22px;
border-radius:999px;
font-weight:800;
margin-bottom:25px;
font-size:18px;
}

.card h2{
font-size:clamp(32px,4vw,50px);
margin-bottom:30px;
line-height:1.2;
}

.card p{
font-size:clamp(20px,2vw,26px);
line-height:2;
color:#374151;
margin-bottom:25px;
}

.warning{
background:#fff3cd;
border-left:6px solid #ffb703;
padding:20px;
border-radius:18px;
font-size:18px;
line-height:1.8;
margin-top:20px;
}

footer{
background:#111827;
color:white;
text-align:center;
padding:45px 20px;
}

footer h3{
font-size:32px;
margin-bottom:12px;
}

footer p{
font-size:18px;
line-height:1.8;
}

@media(max-width:900px){

header{
padding:15px 20px;
justify-content:center;
}

.hero{
margin-top:120px;
padding:40px 15px;
}

.card img{
height:280px;
}

.card-content{
padding:28px;
}

nav{
justify-content:center;
}

}

</style>
</head>

<body>

<header>
<div class="logo">g1</div>

<nav>
<a href="#cop30">COP30</a>
<a href="#onu">ONU</a>
<a href="#clima">Clima</a>
</nav>
</header>

<section class="hero">

<div class="hero-content">

<h1>
COP30 e ONU estariam discutindo novas medidas climáticas globais, afirmam publicações virais
</h1>

<p>
Mensagens compartilhadas em redes sociais alegam que representantes internacionais ligados à COP30 e à Organização das Nações Unidas estariam avaliando possíveis mudanças ambientais e econômicas envolvendo energia, agricultura e transporte em diversos países.
</p>

</div>
</section>

<section class="container">

<div class="card" id="cop30">
<img src="https://images.unsplash.com/photo-1517457373958-b7bdd4587205?q=80&w=1600&auto=format&fit=crop">

<div class="card-content">
<span class="tag">COP30</span>

<h2>
Reuniões internacionais sobre mudanças climáticas movimentam debates nas redes
</h2>

<p>
Nos últimos dias, diversos perfis compartilharam conteúdos afirmando que autoridades internacionais estariam planejando novas regras ambientais para serem aplicadas gradualmente até 2035. Entre os temas mais citados nas publicações aparecem possíveis restrições relacionadas ao consumo de combustíveis fósseis, emissão de carbono e metas de sustentabilidade.
</p>

<p>
As mensagens ganharam força principalmente após o aumento das discussões sobre a COP30, conferência climática que reunirá representantes de vários países para debater políticas ambientais e acordos internacionais relacionados ao clima.
</p>

<div class="warning">
⚠️ Este site é apenas um exemplo visual fictício inspirado em páginas jornalísticas e não deve ser utilizado para divulgar informações falsas como se fossem reais.
</div>

</div>
</div>

<div class="card" id="onu">
<img src="https://images.unsplash.com/photo-1529107386315-e1a2ed48a620?q=80&w=1600&auto=format&fit=crop">

<div class="card-content">
<span class="tag">ONU</span>

<h2>
Publicações mencionam possíveis impactos econômicos em setores globais
</h2>

<p>
Segundo os conteúdos compartilhados online, áreas como agricultura, energia e transporte seriam diretamente afetadas por futuras decisões internacionais ligadas à sustentabilidade. As postagens afirmam ainda que alguns países poderiam adotar medidas mais rígidas para atingir metas climáticas nos próximos anos.
</p>

<p>
Especialistas lembram, porém, que muitas informações publicadas nas redes sociais acabam sendo divulgadas sem contexto completo ou confirmação oficial, aumentando a circulação de boatos e interpretações equivocadas.
</p>

</div>
</div>

<div class="card" id="clima">
<img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1600&auto=format&fit=crop">

<div class="card-content">
<span class="tag">Clima</span>

<h2>
Debates ambientais seguem entre os assuntos mais comentados do cenário internacional
</h2>

<p>
A realização de eventos globais sobre meio ambiente tem gerado forte repercussão nas redes sociais, principalmente entre usuários interessados em temas econômicos e políticos. O aumento do compartilhamento de conteúdos relacionados ao clima também fez crescer a preocupação com desinformação digital e notícias sem verificação.
</p>

<p>
Organizações internacionais e agências de checagem recomendam sempre consultar fontes confiáveis antes de compartilhar conteúdos virais sobre política, economia ou acordos globais.
</p>

</div>
</div>

</section>

<footer>
<h3>Portal Demonstrativo</h3>
<p>
Projeto visual fictício criado apenas para fins de estudo de layout e design.
</p>
</footer>

</body>
</html>
