<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Links 2</title>
  <style>
    body {
      background-color: #000;
      color: white;
      font-family: 'Poppins', sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      gap: 20px;
    }

    h1 {
      background-color: red;
      padding: 10px 25px;
      border-radius: 15px;
      font-size: 28px;
      font-weight: 700;
      color: white;
      letter-spacing: 1px;
      box-shadow: 0 0 15px red;
    }

    img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid red;
      box-shadow: 0 0 20px red;
    }

    .btn {
      display: block;
      width: 220px;
      background-color: red;
      color: white;
      font-weight: 600;
      text-decoration: none;
      padding: 14px;
      border-radius: 25px;
      margin: 8px 0;
      transition: all 0.3s ease;
      box-shadow: 0 0 10px rgba(255, 0, 0, 0.6);
    }

    .btn:hover {
      background-color: white;
      color: red;
      box-shadow: 0 0 20px red;
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>OUR LINKS 2</h1>
    <img src="samurai_logo.png" alt="Samurai Logo">
    <a href="#" class="btn">Our Website</a>
    <a href="#" class="btn">Our Instagram</a>
    <a href="#" class="btn">Our Snapchat</a>
    <a href="#" class="btn">Our Tiktok</a>
  </div>
</body>
</html>
