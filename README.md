<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jungle Clothes - Молодіжний одяг</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            overflow-x: hidden;
        }
        header {
            background-color: #2ecc71;
            color: white;
            padding: 20px;
            text-align: center;
            animation: slideDown 1s ease-out;
        }
        section {
            padding: 20px;
            animation: fadeIn 2s ease-in;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product {
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 15px;
            width: 200px;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        footer {
            background-color: #2ecc71;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
            animation: slideUp 1s ease-out;
        }

        @keyframes slideDown {
            from { transform: translateY(-100%); }
            to { transform: translateY(0); }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            from { transform: translateY(100%); }
            to { transform: translateY(0); }
        }
    </style>
</head>
<body>

<header>
    <h1>Jungle Clothes</h1>
    <p>Стильний молодіжний одяг</p>
</header>

<section>
    <h2>Наш асортимент</h2>
    <div class="products">
        <div class="product">
            <img src="https://via.placeholder.com/200x250.png?text=T-Shirt" alt="Футболка">
            <p>Футболки</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200x250.png?text=Hoodie" alt="Худі">
            <p>Худі</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200x250.png?text=Jeans" alt="Джинси">
            <p>Джинси</p>
        </div>
    </div>
</section>

<section>
    <h2>Контакти</h2>
    <p>Телефон: <a href="tel:+380930597820">093 059 7820</a></p>
    <p>Telegram: <a href="https://t.me/gpssrt" target="_blank">@gpssrt</a></p>
</section>

<footer>
    <p>Jungle Clothes &copy; 2025</p>
</footer>

</body>
</html>
