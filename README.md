<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nomad Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:'Poppins',sans-serif;
background:#0f172a;
color:white;
line-height:1.7;
}

header{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(135deg,#0f172a,#1e3a8a);
padding:20px;
}

header h1{
font-size:4rem;
margin-bottom:20px;
}

header p{
font-size:1.4rem;
opacity:.85;
}

.btn{
display:inline-block;
margin-top:40px;
padding:15px 40px;
background:#38bdf8;
color:white;
text-decoration:none;
border-radius:50px;
transition:.3s;
}

.btn:hover{
transform:translateY(-3px);
background:#0ea5e9;
}

section{
max-width:1100px;
margin:auto;
padding:100px 30px;
}

h2{
font-size:2.4rem;
margin-bottom:30px;
color:#38bdf8;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:60px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}

.skill{
background:#1e293b;
padding:25px;
border-radius:15px;
text-align:center;
transition:.3s;
}

.skill:hover{
transform:translateY(-5px);
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.card{
background:#1e293b;
border-radius:20px;
overflow:hidden;
transition:.3s;
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card div{
padding:25px;
}

.card:hover{
transform:translateY(-10px);
}

.travel{
display:flex;
flex-wrap:wrap;
gap:15px;
}

.country{
padding:12px 25px;
background:#2563eb;
border-radius:30px;
}

footer{
text-align:center;
padding:60px;
opacity:.7;
}

@media(max-width:800px){

.about{
grid-template-columns:1fr;
}

header h1{
font-size:2.5rem;
}

}

</style>
</head>

<body>

<header>

<div>

<h1>こんにちは、私は世界を旅するノマドワーカー。</h1>

<p>
旅をしながらWeb制作・UIデザイン・開発を行っています。<br>
どこにいても、価値あるプロダクトを届けます。
</p>

<a href="#projects" class="btn">
Portfolio
</a>

</div>

</header>

<section id="about">

<h2>About Me</h2>

<div class="about">

<div>

<p>

自由な働き方を選び、世界各国を巡りながらリモートで活動しています。

旅を通して得た経験をデザインやプロダクト開発へ活かし、
シンプルで使いやすいWebサービスを制作しています。

</p>

</div>

<img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=900" alt="Nomad">

</div>

</section>

<section>

<h2>Skills</h2>

<div class="skills">

<div class="skill">
<h3>HTML/CSS</h3>
</div>

<div class="skill">
<h3>JavaScript</h3>
</div>

<div class="skill">
<h3>React</h3>
</div>

<div class="skill">
<h3>Next.js</h3>
</div>

<div class="skill">
<h3>UI / UX</h3>
</div>

<div class="skill">
<h3>Figma</h3>
</div>

</div>

</section>

<section>

<h2>Countries Visited</h2>

<div class="travel">

<div class="country">🇯🇵 Japan</div>
<div class="country">🇹🇭 Thailand</div>
<div class="country">🇮🇩 Indonesia</div>
<div class="country">🇻🇳 Vietnam</div>
<div class="country">🇰🇷 Korea</div>
<div class="country">🇸🇬 Singapore</div>
<div class="country">🇪🇸 Spain</div>
<div class="country">🇵🇹 Portugal</div>

</div>

</section>

<section id="projects">

<h2>Projects</h2>

<div class="projects">

<div class="card">

<img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=900">

<div>

<h3>Travel Blog</h3>

<p>

旅の記録を発信するWebメディア。

</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1518770660439-4636190af475?w=900">

<div>

<h3>Remote Work App</h3>

<p>

ノマド向けタスク管理アプリ。

</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=900">

<div>

<h3>Portfolio Design</h3>

<p>

クリエイター向けポートフォリオ制作。

</p>

</div>

</div>

</div>

</section>

<section>

<h2>Contact</h2>

<p>

Email<br>

hello@example.com

</p>

</section>

<footer>

© 2026 Nomad Portfolio

</footer>

</body>
</html>
