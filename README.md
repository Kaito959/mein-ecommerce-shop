<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mein E-Commerce-Geschäft</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        section {
            padding: 20px 0;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Mein E-Commerce-Geschäft</h1>
            <nav>
                <ul>
                    <li><a href="#home">Startseite</a></li>
                    <li><a href="#about">Über uns</a></li>
                    <li><a href="#products">Produkte</a></li>
                    <li><a href="#contact">Kontakt</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <section id="home">
            <h2>Willkommen zu unserem E-Commerce-Geschäft</h2>
            <p>Wir bieten die besten Produkte zu den besten Preisen!</p>
        </section>

        <section id="about">
            <h2>Über uns</h2>
            <p>Unser Unternehmen wurde gegründet, um hochwertige Produkte online anzubieten. Wir sind stolz auf unseren exzellenten Kundenservice und unsere schnelle Lieferung.</p>
        </section>

        <section id="products">
            <h2>Unsere Produkte</h2>
            <p>Hier finden Sie eine Auswahl unserer beliebtesten Produkte:</p>
            <ul>
                <li>Produkt 1</li>
                <li>Produkt 2</li>
                <li>Produkt 3</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Kontakt</h2>
            <p>Kontaktieren Sie uns über das folgende Formular:</p>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="message">Nachricht:</label><br>
                <textarea id="message" name="message"></textarea><br>
                <input type="submit" value="Absenden">
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Mein E-Commerce-Geschäft</p>
    </footer>
</body>
</html>
