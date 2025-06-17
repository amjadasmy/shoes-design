# shoes-design
https://shoesdesign-amjad.github.io/shoes-website/
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Shoes Product Card</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .card {
      background: white;
      border-radius: 15px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
      width: 300px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
    }

    .card h2 {
      margin: 15px 0 10px;
      font-size: 22px;
      color: #333;
    }

    .card p {
      color: #555;
      font-size: 15px;
      line-height: 1.5;
    }

    .price {
      font-size: 20px;
      color: #e91e63;
      margin: 15px 0;
    }

    .card button {
      padding: 10px 20px;
      background: #e91e63;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .card button:hover {
      background: #c2185b;
    }
  </style>
</head>
<body>

  <div class="card">
    <img src="https://i.imgur.com/1XbKjU9.png" alt="Shoes Image">
    <h2>Stylish Running Shoes</h2>
    <p>Comfortable, durable, and perfect for sports or daily use.</p>
    <div class="price">$49.99</div>
    <button>Add to Cart</button>
  </div>

</body>
</html>
