<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>TRAVMAT24 - Интернет-магазин</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
      color: #00ccff;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 20px;
    }
    .card {
      background-color: #222;
      border-radius: 10px;
      overflow: hidden;
      width: 300px;
      box-shadow: 0 0 10px #000;
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-content {
      padding: 15px;
    }
    .card h3 {
      margin: 0;
    }
    .price {
      color: #00ccff;
      font-size: 1.2em;
      margin: 10px 0;
    }
    .buy-btn {
      background-color: #00ccff;
      color: #000;
      padding: 10px;
      text-align: center;
      border-radius: 5px;
      text-decoration: none;
      display: inline-block;
    }
    .buy-btn:hover {
      background-color: #009ecc;
    }
  </style>
</head>
<body>

<header>TRAVMAT24</header>

<section class="products">
  <div class="card">
    <img src="1A69C056-502E-4DFC-BF5A-88B5A21CC0F0.jpeg" alt="Пистолет ПМ-Т">
    <div class="card-content">
      <h3>ПМ-Т</h3>
      <div class="price">15 000 ₽</div>
      <a class="buy-btn" href="https://t.me/moroderr" target="_blank">Купить</a>
    </div>
  </div>

  <div class="card">
    <img src="C65D4A5A-56E4-46D1-AFCC-066DE55C8AE3.jpeg" alt="Пистолет МР-356">
    <div class="card-content">
      <h3>МР-356</h3>
      <div class="price">18 500 ₽</div>
      <a class="buy-btn" href="https://t.me/moroderr" target="_blank">Купить</a>
    </div>
  </div>
</section>

</body>
</html>
