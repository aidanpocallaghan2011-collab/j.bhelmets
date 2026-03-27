# j.bhelmets
hurling helmets for sale

</body>
</html></title>
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    /* Header */
    header {
      background-color: #1abc9c;
      color: white;
      text-align: center;
      padding: 50px 20px;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
      font-weight: 300;
    }

    /* Navigation */
    nav {
      background-color: #16a085;
      text-align: center;
      padding: 15px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #f1c40f;
    }

    /* Container */
    .container {
      max-width: 1200px;
      margin: 40px auto;
      padding: 0 20px;
      text-align: center;
    }

    /* Products Section */
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .product-card {
      background: white;
      border-radius: 10px;
      padding: 25px;
      width: 300px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .product-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 12px 25px rgba(0,0,0,0.15);
    }

    .product-card h2 {
      margin-bottom: 15px;
      color: #16a085;
    }

    .product-card p {
      font-size: 1em;
      color: #555;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      background-color: #f1c40f;
      color: #333;
      text-decoration: none;
      border-radius: 6px;
      margin-top: 15px;
      transition: background-color 0.3s;
      font-weight: bold;
    }

    .btn:hover {
      background-color: #d4ac0d;
      color: white;
    }

    /* Contact Form */
    .contact-form {
      background: white;
      padding: 30px;
      border-radius: 10px;
      max-width: 500px;
      margin: 40px auto;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      text-align: left;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 1em;
    }

    .contact-form button {
      width: 100%;
      padding: 12px;
      border: none;
      background-color: #1abc9c;
      color: white;
      font-size: 1.1em;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .contact-form button:hover {
      background-color: #16a085;
    }

    /* Footer */
    footer {
      background-color: #1abc9c;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    /* Responsive */
    @media(max-width: 960px){
      .products {
        flex-direction: column;
        align-items: center;
      }
    }

  </style>
</head>
<body>

  <header>
    <h1>Hurling Helmets Store</h1>
    <p>High-quality hurling helmets for safety and style on the field</p>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="products">
    <h2>Our Helmets</h2>
    <div class="products">
      <div class="product-card">
        <h2>Standard Helmet</h2>
        <p>Lightweight, durable, and perfect for beginners or casual players.</p>
        <a href="#contact" class="btn">Order Now</a>
      </div>
      <div class="product-card">
        <h2>Pro Helmet</h2>
        <p>Advanced protection with premium padding and airflow for serious players.</p>
        <a href="#contact" class="btn">Order Now</a>
      </div>
      <div class="product-card">
        <h2>Custom Helmet</h2>
        <p>Design your own helmet with custom colours and decals for your team.</p>
        <a href="#contact" class="btn">Order Now</a>
      </div>
    </div>
  </div>

  <div class="container" id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>

  <footer>
    <p>&copy; 2026 Hurling Helmets Store</p>
  </footer>

</body>
</html>
