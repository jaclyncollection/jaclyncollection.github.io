# jaclyncollection.github.io
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
  background: #f6f3ef;
  color: #2b2b2b;
}

/* Header */
header {
  background: #f6f3ef;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  font-weight: 500;
  font-size: 18px;
}

/* Hero */
.hero {
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 36px;
  font-weight: 500;
}

.hero p {
  color: #777;
  margin-top: 10px;
}

/* Button */
.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 12px 22px;
  background: #2b2b2b;
  color: white;
  text-decoration: none;
  border-radius: 30px;
  font-size: 14px;
}

/* Section */
.section {
  padding: 60px 40px;
}

.section h2 {
  font-weight: 500;
  margin-bottom: 30px;
}

/* Products */
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
  gap: 25px;
}

.card {
  background: #fff;
  border-radius: 16px;
  overflow: hidden;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
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
  margin: 5px 0;
  font-weight: 500;
}

.card p {
  color: #777;
  font-size: 14px;
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
}

/* Footer */
footer {
  text-align: center;
  padding: 30px;
  color: #888;
  font-size: 13px;
}

/* Floating WhatsApp */
.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25D366;
  color: white;
  padding: 14px 16px;
  border-radius: 50px;
  text-decoration: none;
  font-size: 14px;
}
</style>
</head>

<body>

<header>
  <div>Jaclyn Collection</div>
  <div>Custom Gifts</div>
</header>

<section class="hero">
  <h1>Personalised Gifts, Made Simple</h1>
  <p>Tote Bags • Pencil Cases • Custom Printing</p>
  <a class="btn" href="https://wa.me/60123456789?text=Hi%20Jaclyn%2C%20I%27m%20interested%20in%20your%20products">Order via WhatsApp</a>
</section>

<section class="section">
  <h2>Products</h2>
  <div class="products">

    <div class="card">
      <img src="https://via.placeholder.com/400">
      <div class="card-content">
        <h3>Tote Bags</h3>
        <p>Minimal, everyday custom totes</p>
        <a class="btn" href="https://wa.me/60123456789?text=Hi%20I%20want%20tote%20bag">Order</a>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400">
      <div class="card-content">
        <h3>Pencil Cases</h3>
        <p>Perfect for gifts & daily use</p>
        <a class="btn" href="https://wa.me/60123456789?text=Hi%20I%20want%20pencil%20case">Order</a>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400">
      <div class="card-content">
        <h3>Custom Printing</h3>
        <p>Print your own design or logo</p>
        <a class="btn" href="https://wa.me/60123456789?text=Hi%20I%20want%20custom%20printing">Customize</a>
      </div>
    </div>

  </div>
</section>

<section class="section">
  <h2>Our Work</h2>
  <div class="gallery">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
    <img src="https://via.placeholder.com/400">
  </div>
</section>

<footer>
  © 2026 Jaclyn Collection
</footer>

<a class="whatsapp" href="https://wa.me/60123456789?text=Hi%20Jaclyn%2C%20I%27m%20interested%20in%20your%20products">
  Chat on WhatsApp
</a>

</body>
</html>
