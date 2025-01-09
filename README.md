# -
Интернет магазин 
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Интернет-магазин</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Шапка сайта -->
  <header>
    <div class="container">
      <h1>Интернет-магазин</h1>
      <nav>
        <ul>
          <li><a href="#">Главная</a></li>
          <li><a href="#">Каталог</a></li>
          <li><a href="#">О нас</a></li>
          <li><a href="#">Контакты</a></li>
          <li><a href="#">Корзина</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Главная секция с товарами -->
  <section class="products">
    <div class="container">
      <h2>Популярные товары</h2>
      <div class="product-list">
        <div class="product-item">
          <img src="product1.jpg" alt="Товар 1">
          <h3>Товар 1</h3>
          <p>Описание товара 1</p>
          <p>Цена: 1000 руб.</p>
          <button class="add-to-cart">Добавить в корзину</button>
        </div>
        <div class="product-item">
          <img src="product2.jpg" alt="Товар 2">
          <h3>Товар 2</h3>
          <p>Описание товара 2</p>
          <p>Цена: 2000 руб.</p>
          <button class="add-to-cart">Добавить в корзину</button>
        </div>
        <!-- Добавьте больше товаров здесь -->
      </div>
    </div>
  </section>

  <!-- Подвал -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Интернет-магазин. Все права защищены.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
