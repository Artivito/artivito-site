# artivito-site
Ми - це дизайн та навіть більше. 
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artivito - Minimal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            padding: 20px;
            background-color: #1e1e1e;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #2a2a2a;
            border-radius: 10px;
        }
        a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            color: #fff;
            text-decoration: none;
            background-color: #444;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        a:hover {
            background-color: #666;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .product {
            background-color: #1e1e1e;
            margin: 15px;
            padding: 15px;
            border-radius: 5px;
            width: 250px;
            transition: transform 0.3s;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #ccc;
        }
        .product .price {
            color: #fff;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Artivito</h1>
    </header>
    <div class="container">
        <h2>Ласкаво просимо!</h2>
        <p>Слідкуйте за нами у соцмережах та переглядайте наші товари.</p>
        <a href="https://www.instagram.com/your_instagram" target="_blank">Instagram</a>
        <a href="https://t.me/your_telegram" target="_blank">Telegram</a>
    </div>
    <div class="container">
        <h2>Наші товари</h2>
        <div class="products">
            <div class="product">
                <img src="path_to_graphic_design_image.jpg" alt="Графічний дизайн та брендинг">
                <h3>Графічний дизайн та брендинг</h3>
                <p class="price">10 000,00₴</p>
            </div>
            <div class="product">
                <img src="path_to_3d_model_image.jpg" alt="3D модель готового дизайну">
                <h3>3D модель готового дизайну</h3>
                <p class="price">2 500,00₴</p>
            </div>
            <div class="product">
                <img src="path_to_interior_design_image.jpg" alt="Дизайн інтер'єру">
                <h3>Дизайн інтер'єру</h3>
                <p class="price">50 000,00₴</p>
            </div>
            <div class="product">
                <img src="path_to_web_design_image.jpg" alt="Дизайн вашого веб сайту">
                <h3>Дизайн вашого веб сайту</h3>
                <p class="price">1 000,00₴</p>
            </div>
        </div>
    </div>
</body>
</html>
