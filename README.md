<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ama al prójimo como a ti mismo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Ama al prójimo como a ti mismo</h1>
        <h2>- Dona a los necesitados -</h2>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Inicio</a></li>
            <li><a href="#donate">Donar</a></li>
        </ul>
    </nav>
    <main>
        <section id="home" class="magazine-promo">
            <h2>Revista sobre la Caridad</h2>
            <div class="magazine-image">
                <img src="images/revista.jpg" alt="Vista previa de la revista sobre caridad">
            </div>
            <p>Lee sobre los testimonios de las comunidades necesitadas y descubre historias inspiradoras de cambio y esperanza.</p>
            <p><strong>Al comprar esta revista, estás ayudando directamente a los necesitados.</strong></p>
            <p>Para comprar la revista o obtener más información, contáctanos por WhatsApp:</p>
            <a href="https://wa.me/NUMERODEWHATSAPP" class="whatsapp-button" target="_blank">
                Comprar por WhatsApp
            </a>
        </section>
        <section id="donate" class="donate-section">
            <h2>Dona con Nequi</h2>
            <p>Tu generosidad puede transformar vidas. Cada donación cuenta.</p>
            <form id="donateForm">
                <label for="amount">Cantidad a donar:</label>
                <input type="number" id="amount" name="amount" min="1000" step="1000" required>
                <label for="phone">Número de teléfono Nequi:</label>
                <input type="tel" id="phone" name="phone" pattern="[0-9]{10}" required>
                <button type="submit">Donar</button>
            </form>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
