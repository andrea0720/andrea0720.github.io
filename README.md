# trial.github.io
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awesome Coffee Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <nav>
            <a href="#home">Home</a>
            <a href="#menu">Menu</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="home">
            <h1>Welcome to Awesome Coffee Shop</h1>
            <p>Discover the best coffee in town!</p>
        </section>

        <section id="menu">
            <h2>Our Menu</h2>
            <ul>
                <li>Espresso</li>
                <li>Cappuccino</li>
                <li>Latte</li>
                <li>Americano</li>
                <li>Mocha</li>
            </ul>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>At Awesome Coffee Shop, we are passionate about serving the finest coffee sourced from around the world. Our skilled baristas are dedicated to crafting the perfect cup for you every time.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Have a question or want to know more about our coffee shop? Get in touch with us!</p>
            <p>Email: info@awesomecoffeeshop.com</p>
            <p>Phone: +1 (555) 123-4567</p>
        </section>
    </main>

    <footer>
        <p>&copy; <span id="year"></span> Awesome Coffee Shop. All rights reserved.</p>
    </footer>

    <script>
        // Dynamically update the current year in the footer
        document.getElementById("year").textContent = new Date().getFullYear();
    </script>
</body>

</html>
