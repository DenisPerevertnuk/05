<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пример вложенности CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="site-header">
        <nav class="navigation">
            <ul>
                <li><a href="#">Главная</a></li>
                <li><a href="#">О нас</a></li>
                <li><a href="#">Услуги</a>
                    <ul>
                        <li><a href="#">Консультации</a></li>
                        <li><a href="#">Разработка</a></li>
                        <li><a href="#">Поддержка</a></li>
                    </ul>
                </li>
                <li><a href="#">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main class="content">
        <section class="intro">
            <h1>Добро пожаловать на наш сайт!</h1>
            <p>Мы предлагаем разнообразные услуги для вашего бизнеса.</p>
        </section>

        <section class="services">
            <h2>Наши услуги</h2>
            <div class="service-item">
                <h3>Консультации</h3>
                <p>Мы поможем вам найти оптимальные решения для вашего бизнеса.</p>
            </div>
            <div class="service-item">
                <h3>Разработка</h3>
                <p>Мы создадим для вас уникальные и эффективные решения.</p>
            </div>
            <div class="service-item">
                <h3>Поддержка</h3>
                <p>Мы обеспечим вас круглосуточной поддержкой.</p>
            </div>
        </section>
    </main>

    <footer class="site-footer">
        <p>&copy; 2024 Все права защищены.</p>
    </footer>
</body>
</html>
