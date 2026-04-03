<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jaclyn Collection</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background: #f7f5f2;
  color: #2b2b2b;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  padding: 20px 40px;
  font-weight: 500;
  font-size: 18px;
}

/* Hero */
.hero {
  text-align: center;
  padding: 100px 20px 80px;
}

.hero h1 {
  font-size: 40px;
  font-weight: 500;
  margin-bottom: 10px;
}

.hero p {
  color: #777;
  font-size: 16px;
}

/* Button */
.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 12px 24px;
  background: #1f1f1f;
  color: #fff;
  text-decoration: none;
  border-radius: 30px;
  font-size: 14px;
  transition: 0.3s;
}

.btn:hover {
  opacity: 0.8;
}

/* Section */
.section {
  padding: 60px 40px;
}

.section h2 {
  font-weight: 500;
  margin-bottom: 30px;
}

/* Product Grid */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px,1fr));
  gap: 25px;
}

.card {
  background: #fff;
  border-radius: 16px;
  overflow: hidden;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-6px);
}

.card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
}

.card-content {
  padding: 15px;
}

.card h3 {
  font-weight: 500;
  margin: 5px 0;
}

.card p {
  font-size: 14px;
  color: #777;
}

/* Portfolio */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
  gap: 15px;
}

.gallery img {
  width: 100%;
  border-radius: 12px;
  height: 200px;
  object-fit: cover;
}

/* About */
.about {
  text-align: center;
  max-width: 700px;
  margin: auto;
  color: #666;
  line-height: 1.6;
}

/* Footer */
footer {
  text-align: center;
  padding: 40px;
  font-size: 13px;
  color: #999;
}

/* WhatsApp Floating */
.whatsapp {
  position: fixed;
  right: 20px;
  bottom: 20px;
  background: #25D366;
  color: #fff;
  padding: 14px 18px;
  border-radius: 50px;
  text-decoration: none;
  font-size: 14px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}
</style>
</head>

<body>

<header>
  <div>Jaclyn Collection</div>
  <div>Custom Gifts</div>
</header>

<section class="hero">
  <h1>Simple. Personal. Meaningful.</h1>
  <p>Custom Tote Bags • Pencil Cases • Personalized Printing</p>
  <a class="btn" href="https://wa.me/60123456789?text=Hi%20Jaclyn%2C%20I%20want%20to%20order">Order via WhatsApp</a>
</section>

<section class="section">
  <h2>Our Products</h2>
  <div class="grid">

    <div class="card">
      <img src="https://via.placeholder.com/400x300">
      <div class="card-content">
        <h3>Tote Bags</h3>
        <p>Minimal design, fully customizable.</p>
        <a class="btn" href="https://wa.me/60123456789?text=Hi%20I%20want%20tote%20bag">Order</a>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400x300">
      <div class="card-content">
        <h3>Pencil Cases</h3>
        <p>Perfect for gifts & daily use.</p>
        <a class="btn" href="https://wa.me/60123456789?text=Hi%20I%20want%20pencil%20case">Order</a>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400x300">
      <div class="card-content">
        <h3>Custom Printing</h3>
        <p>Bring your ideas to life.</p>
        <a class="btn" href="https://wa.me/60123456789?text=Hi%20I%20want%20custom%20printing">Customize</a>
      </div>
    </div>

  </div>
</section>

<section class="section">
  <h2>Portfolio</h2>
  <div class="gallery">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
  </div>
</section>

<section class="section">
  <div class="about">
    <h2>About Jaclyn Collection</h2>
    <p>
      We specialise in custom-made gifts with a focus on quality, simplicity, and personal touch. 
      Every piece is made with care to bring your ideas into something meaningful and unique.
    </p>
  </div>
</section>

<footer>
  © 2026 Jaclyn Collection
</footer>

<a class="whatsapp" href="https://wa.me/60123456789?text=Hi%20Jaclyn%2C%20I%20want%20to%20order">
  Chat on WhatsApp
</a>

</body>
</html>
