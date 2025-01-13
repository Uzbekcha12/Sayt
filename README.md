<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Shaxsiy saytim, bu yerda mening ishlarim va aloqa ma'lumotlarim bor.">
    <title>Shaxsiy Sayt</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigatsiya menyusi -->
    <header>
        <nav>
            <ul>
                <li><a href="#about">Haqqimda</a></li>
                <li><a href="#portfolio">Portfel</a></li>
                <li><a href="#contact">Aloqa</a></li>
            </ul>
        </nav>
    </header>

    <!-- Kirish qismi -->
    <section id="intro">
        <div class="container">
            <h1>Assalomu alaykum!</h1>
            <p>Menim ismim [Ismingiz], va bu mening shaxsiy sayt.</p>
        </div>
    </section>

    <!-- Haqqimda bo'limi -->
    <section id="about">
        <div class="container">
            <h2>Haqqimda</h2>
            <p>Men [kasbingiz] bo'lib, [sohangiz] sohasida faoliyat yuritaman. Menimcha, har bir ishda mukammallikni qidirish juda muhim.</p>
        </div>
    </section>

    <!-- Portfel bo'limi -->
    <section id="portfolio">
        <div class="container">
            <h2>Portfel</h2>
            <p>Mana mening ishlagan loyihalarim:</p>
            <div class="portfolio-item">
                <img src="portfolio1.jpg" alt="Loyihalar 1">
                <h3>Loyihalar 1</h3>
                <p>Loyihalar 1 ta'rifi.</p>
            </div>
            <div class="portfolio-item">
                <img src="portfolio2.jpg" alt="Loyihalar 2">
                <h3>Loyihalar 2</h3>
                <p>Loyihalar 2 ta'rifi.</p>
            </div>
        </div>
    </section>

    <!-- Aloqa bo'limi -->
    <section id="contact">
        <div class="container">
            <h2>Aloqa</h2>
            <form>
                <label for="name">Ismingiz:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email manzilingiz:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Xabaringiz:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Yuborish</button>
            </form>
        </div>
    </section>

    <!-- Foydali ma'lumotlar -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Shaxsiy Saytingiz. Barcha huquqlar himoyalangan.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
