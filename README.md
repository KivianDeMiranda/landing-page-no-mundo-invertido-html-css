# landing-page-no-mundo-invertido-html-css
Construindo uma Landing Page no Mundo Invertido com HTML e CSS

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mundo Invertido</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1>Bem-vindo ao Mundo Invertido</h1>
        <nav>
            <ul>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#gallery">Galeria</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>
    <section id="about" class="about">
        <h2>Sobre</h2>
        <p>Explore os mistérios do Mundo Invertido, uma dimensão sombria e intrigante.</p>
    </section>
    <section id="gallery" class="gallery">
        <h2>Galeria</h2>
        <div class="gallery-container">
            <img src="path/to/image1.jpg" alt="Imagem 1">
            <img src="path/to/image2.jpg" alt="Imagem 2">
            <img src="path/to/image3.jpg" alt="Imagem 3">
        </div>
    </section>
    <section id="contact" class="contact">
        <h2>Contato</h2>
        <form>
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer class="footer">
        <p>&copy; 2024 Mundo Invertido. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #111;
    color: #fff;
    text-align: center;
}

.header {
    background-color: #000;
    padding: 20px;
}

.header h1 {
    margin: 0;
}

.header nav ul {
    list-style: none;
    padding: 0;
}

.header nav ul li {
    display: inline;
    margin: 0 10px;
}

.header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.about, .gallery, .contact {
    padding: 50px 20px;
}

.gallery-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.gallery-container img {
    max-width: 100%;
    height: auto;
    border: 3px solid #fff;
}

.contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.contact form input, .contact form textarea {
    width: 100%;
    max-width: 500px;
    padding: 10px;
    margin: 10px 0;
    border: none;
    border-radius: 5px;
}

.contact form button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    background-color: #444;
    color: #fff;
    cursor: pointer;
}

.contact form button:hover {
    background-color: #666;
}

.footer {
    background-color: #000;
    padding: 20px;
}
