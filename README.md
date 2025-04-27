<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saloon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Saloon</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="features.html">Features</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h1>Welcome to Saloon</h1>
        <p>Your ultimate tool for managing [your niche].</p>
        <button>Get Started</button>
    </section>
    <footer>
        <p>&copy; 2025 Saloon. All Rights Reserved.</p>
    </footer>
</body>
</html># Saloonbody {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    display: flex;
    justify-content: space-between;
    padding: 20px;
    background: #333;
    color: white;
}
header .logo {
    font-size: 24px;
    font-weight: bold;
}
header nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
}
header nav ul li a {
    text-decoration: none;
    color: white;
}
.hero {
    text-align: center;
    padding: 100px 20px;
    background: #f4f4f4;
}
.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
}
.hero p {
    font-size: 18px;
    margin-bottom: 20px;
}
.hero button {
    padding: 10px 20px;
    font-size: 16px;
    background: #333;
    color: white;
    border: none;
    cursor: pointer;
}
footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: white;
}