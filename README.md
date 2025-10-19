<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Product & Service Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #fff;
      color: #000;
    }

    header {
      background-color: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    .hero {
      background: linear-gradient(135deg, #d90429, #000);
      color: #fff;
      text-align: center;
      padding: 80px 20px;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 30px;
    }

    .btn {
      background-color: #fff;
      color: #d90429;
      border: none;
      padding: 15px 40px;
      font-size: 18px;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background-color: #d90429;
      color: #fff;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .card {
      background: #f7f7f7;
      border-radius: 12px;
      padding: 25px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .card h3 {
      color: #d90429;
    }

    .reviews {
      background-color: #000;
      color: #fff;
    }

    .review {
      margin: 20px 0;
      font-style: italic;
    }

    footer {
      background-color: #d90429;
      color: #fff;
      text-align: center;
      padding: 15px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h2>🔥 My Product & Service Brand 🔥</h2>
  </header>

  <section class="hero">
    <h1>Transform Your Business Today</h1>
    <p>Get our exclusive product & professional service to boost your success.</p>
    <button class="btn">Buy Now</button>
  </section>

  <section>
    <h2>Our Products & Services</h2>
    <div class="features">
      <div class="card">
        <h3>🚀 Premium Product</h3>
        <p>High-quality, durable and designed to meet your needs.</p>
      </div>
      <div class="card">
        <h3>💼 Professional Service</h3>
        <p>Expert team to support and manage your business operations efficiently.</p>
      </div>
      <div class="card">
        <h3>⚡ Fast Delivery</h3>
        <p>Get your product and service within 24 hours guaranteed.</p>
      </div>
    </div>
  </section>

  <section class="reviews">
    <h2>What Our Clients Say</h2>
    <div class="review">“Amazing quality and top-notch service. Highly recommended!”</div>
    <div class="review">“Great experience from start to finish. Love the design!”</div>
  </section>

  <footer>
    © 2025 My Product & Service Brand — All Rights Reserved.
  </footer>

</body>
</html>
