<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Perfumes BFC</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&display=swap" rel="stylesheet">
<style>
body {
  margin:0;
  font-family: 'Playfair Display', serif;
  background:#000;
  color:#fff;
}
header {
  background:#000;
  padding:40px;
  text-align:center;
}
header h1 {
  color:#d4af37;
  font-size:48px;
}
.hero {
  background: linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
  url('https://images.unsplash.com/photo-1523294587484-bae6cc870010');
  background-size:cover;
  padding:120px 20px;
  text-align:center;
}
.hero h2 {
  color:#d4af37;
  font-size:42px;
}
.btn {
  background:#b30000;
  color:white;
  padding:15px 30px;
  border-radius:5px;
  text-decoration:none;
  font-size:18px;
}
.section {
  padding:60px 20px;
  text-align:center;
}
.products {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:25px;
}
.card {
  background:#111;
  border:2px solid #b30000;
  padding:20px;
  border-radius:10px;
}
footer {
  background:#000;
  padding:30px;
  text-align:center;
  color:#d4af37;
}
</style>
</head>

<body>

<header>
<h1>Perfumes BFC</h1>
<p>Fragancias de lujo para damas y caballeros</p>
</header>

<section class="hero">
<h2>Lujo que se siente</h2>
<p>Perfumes exclusivos, entrega solo en tu ciudad</p><br>
<a class="btn" href="https://wa.me/573057637291">Comprar por WhatsApp</a>
</section>

<section class="section">
<h2>🌸 Damas</h2>
<div class="products">
<div class="card">Good Girl<br><br><a class="btn" href="https://wa.me/573057637291">Cotizar</a></div>
<div class="card">212 VIP<br><br><a class="btn" href="https://wa.me/573057637291">Cotizar</a></div>
<div class="card">Floral Dama<br><br><a class="btn" href="https://wa.me/573057637291">Cotizar</a></div>
</div>
</section>

<section class="section">
<h2>🔥 Caballeros</h2>
<div class="products">
<div class="card">Invictus<br><br><a class="btn" href="https://wa.me/573057637291">Cotizar</a></div>
<div class="card">Dior Sauvage<br><br><a class="btn" href="https://wa.me/573057637291">Cotizar</a></div>
<div class="card">Fresh Hombre<br><br><a class="btn" href="https://wa.me/573057637291">Cotizar</a></div>
</div>
</section>

<footer>
<p>📲 WhatsApp: 305 763 7291</p>
<p>© 2026 Perfumes BFC</p>
</footer>

</body>
</html>
