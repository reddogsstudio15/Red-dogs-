# Red-dogs-
แฟชั่น
ราคา
สี ขาว ดำ เทา แดง<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Red Dogs | แบรนด์เสื้อผ้า</title>
  <style>
    body {
      margin: 0;
      font-family: 'Sarabun', sans-serif;
      background-color: #f7f7f7;
    }

    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      letter-spacing: 1px;
    }

    .product-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }

    .product:hover {
      transform: translateY(-5px);
    }

    .product img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .product-details {
      padding: 15px;
    }

    .product-name {
      font-size: 18px;
      font-weight: bold;
      margin: 0 0 10px;
    }

    .product-color {
      font-size: 14px;
      color: #555;
    }

    .product-price {
      font-size: 16px;
      color: #e91e63;
      font-weight: bold;
      margin-top: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #222;
      color: white;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    Red Dogs | Street Fashion
  </header>

  <section class="product-list">
    <div class="product">
      <img src="https://via.placeholder.com/400x300?text=เสื้อยืดลายสตรีท" alt="เสื้อยืดลายสตรีท">
      <div class="product-details">
        <p class="product-name">เสื้อยืดลายสตรีท</p>
        <p class="product-color">สี: ขาว/ดำ</p>
        <p class="product-price">ราคา: 490 บาท</p>
      </div>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/400x300?text=กางเกงยีนส์ขาดเท่ๆ" alt="กางเกงยีนส์ขาดเท่ๆ">
      <div class="product-details">
        <p class="product-name">กางเกงยีนส์ขาดเท่ๆ</p>
        <p class="product-color">สี: น้ำเงินเข้ม</p>
        <p class="product-price">ราคา: 890 บาท</p>
      </div>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/400x300?text=เสื้อแจ็คเก็ตOversize" alt="แจ็คเก็ต Oversize">
      <div class="product-details">
        <p class="product-name">แจ็คเก็ต Oversize</p>
        <p class="product-color">สี: ดำ / เทา</p>
        <p class="product-price">ราคา: 1,290 บาท</p>
      </div>
    </div>
  </section>

  <footer>
    © 2025 Red Dogs. All rights reserved.
  </footer>

</body>
</html>
