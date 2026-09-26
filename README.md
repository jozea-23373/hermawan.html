<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Keluarga Hermawan</title>
<style>
:root{
  --bg:#f6f3ee; --card:#ffffff; --ink:#2b2620; --sub:#6b6257;
  --accent:#a9744f; --accent2:#5c7a63; --line:#e6dfd4;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#1c1a17; --card:#242119; --ink:#efe9df; --sub:#a89d8d;
    --accent:#d99a6c; --accent2:#8fb79a; --line:#3a352c;
  }
}
:root[data-theme="dark"]{
  --bg:#1c1a17; --card:#242119; --ink:#efe9df; --sub:#a89d8d;
  --accent:#d99a6c; --accent2:#8fb79a; --line:#3a352c;
}
*{box-sizing:border-box;}
html{scroll-padding-top:env(safe-area-inset-top,0px);}
body{
  margin:0; background:var(--bg); color:var(--ink);
  font-family:"Georgia","Iowan Old Style",serif;
  min-height:100%;
}
header{
  text-align:center; padding:56px 20px 28px;
}
header .eyebrow{
  letter-spacing:.18em; text-transform:uppercase; font-size:.72rem;
  color:var(--accent); font-family:Verdana,sans-serif;
}
header h1{ font-size:2.1rem; margin:.4em 0 .2em; }
header p{ color:var(--sub); font-family:Verdana,sans-serif; font-size:.9rem; }

.wrap{max-width:920px; margin:0 auto; padding:0 20px 60px;}

.grid{
  display:grid; grid-template-columns:repeat(2,1fr); gap:20px;
}
@media (max-width:640px){ .grid{grid-template-columns:1fr;} }

.card{
  background:var(--card); border:1px solid var(--line); border-radius:14px;
  padding:26px 24px; position:relative; overflow:hidden;
}
.card::before{
  content:""; position:absolute; top:0; left:0; width:6px; height:100%;
  background:var(--accent);
}
.card.mama::before, .card.given::before{ background:var(--accent2); }

.role{
  font-family:Verdana,sans-serif; font-size:.68rem; letter-spacing:.14em;
  text-transform:uppercase; color:var(--sub);
}
.name{ font-size:1.35rem; margin:.25em 0 .5em; }
.status{
  font-family:Verdana,sans-serif; font-size:.88rem; color:var(--ink);
  display:flex; gap:8px; align-items:flex-start; line-height:1.4;
}
.dot{
  width:8px; height:8px; border-radius:50%; background:var(--accent);
  margin-top:6px; flex:none;
}
.given .dot, .mama .dot{ background:var(--accent2); }

.tree{
  margin-top:34px; text-align:center;
}
.tree .line1, .tree .line2{
  font-family:Verdana,sans-serif; color:var(--sub); font-size:.85rem;
}
.tree svg{ margin:14px auto; display:block; }

footer{
  text-align:center; color:var(--sub); font-family:Verdana,sans-serif;
  font-size:.75rem; padding-bottom:20px;
}
</style>
</head>
<body>
<header>
  <div class="eyebrow">Keluarga</div>
  <h1>Keluarga Hermawan</h1>
  <p>Yunianto Hermawan &amp; Mikey Apinadania</p>
</header>

<div class="wrap">
  <div class="grid">
    <div class="card papa">
      <div class="role">Papa</div>
      <div class="name">Yunianto Hermawan</div>
      <div class="status"><span class="dot"></span>Pegawai Negeri Sipil (PNS)</div>
    </div>

    <div class="card mama">
      <div class="role">Mama</div>
      <div class="name">Mikey Apinadania</div>
      <div class="status"><span class="dot"></span>Ibu Rumah Tangga</div>
    </div>

    <div class="card jozea">
      <div class="role">Anak Pertama</div>
      <div class="name">Jozea Laventa Theodouron Hermawan</div>
      <div class="status"><span class="dot"></span>Kelas 1, SMK N 2 Depok, Sleman, Yogyakarta</div>
    </div>

    <div class="card given">
      <div class="role">Anak Kedua</div>
      <div class="name">Given Gretacia Kiamanda Hermawan</div>
      <div class="status"><span class="dot"></span>Kelas 4, SD Maria Assumpta, Klaten</div>
    </div>
  </div>

  <div class="tree">
    <svg viewBox="0 0 400 90" width="360" height="80">
      <circle cx="130" cy="20" r="6" fill="var(--accent)"/>
      <circle cx="270" cy="20" r="6" fill="var(--accent2)"/>
      <line x1="130" y1="20" x2="270" y2="20" stroke="var(--sub)" stroke-width="2"/>
      <line x1="200" y1="20" x2="200" y2="55" stroke="var(--sub)" stroke-width="2"/>
      <line x1="130" y1="55" x2="270" y2="55" stroke="var(--sub)" stroke-width="2"/>
      <circle cx="130" cy="75" r="5" fill="var(--accent)"/>
      <circle cx="270" cy="75" r="5" fill="var(--accent2)"/>
      <line x1="130" y1="55" x2="130" y2="70" stroke="var(--sub)" stroke-width="2"/>
      <line x1="270" y1="55" x2="270" y2="70" stroke="var(--sub)" stroke-width="2"/>
    </svg>
    <div class="line2">Papa &amp; Mama — Jozea &amp; Given</div>
  </div>
</div>

<footer>Dibuat dengan penuh kasih untuk Keluarga Hermawan</footer>
</body>
</html># hermawan.html
