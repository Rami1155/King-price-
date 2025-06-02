<!DOCTYPE html>
<html lang="he">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>חנות גאדג'טים - דוגמה</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      direction: rtl;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
    }

    header {
      background-color: #1e88e5;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #1565c0;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
    }

    .product {
      background: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 15px;
      padding: 15px;
      width: 280px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 5px;
    }

    .product h3 {
      margin-top: 10px;
      font-size: 18px;
    }

    .product p {
      font-size: 14px;
      color: #555;
    }

    .product button {
      background-color: #1e88e5;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }

    .product button:hover {
      background-color: #1565c0;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #e0e0e0;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>ברוכים הבאים לחנות הגאדג'טים שלנו!</h1>
    <p>מוצרים חכמים במחירים חכמים</p>
  </header>

  <nav>
    <a href="#">בית</a>
    <a href="#">מוצרים</a>
    <a href="#">צור קשר</a>
  </nav>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/280x200" alt="מוצר 1" />
      <h3>שעון חכם</h3>
      <p>שעון חכם עם מד דופק, GPS והתראות.</p>
      <button onclick="addToCart('שעון חכם')">הוסף לעגלה</button>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/280x200" alt="מוצר 2" />
      <h3>אוזניות Bluetooth</h3>
      <p>אוזניות איכותיות עם סינון רעשים.</p>
      <button onclick="addToCart('אוזניות Bluetooth')">הוסף לעגלה</button>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/280x200" alt="מוצר 3" />
      <h3>מטען נייד 10000mAh</h3>
      <p>מטען חזק ומהיר עם 2 יציאות USB.</p>
      <button onclick="addToCart('מטען נייד')">הוסף לעגלה</button>
    </div>
  </section>

  <footer>
    <p>© 2025 חנות גאדג'טים. כל הזכויות שמורות.</p>
  </footer>

  <script>
    function addToCart(productName) {
      alert(productName + " נוסף לעגלת הקניות!");
    }
  </script>
</body>
</html>
