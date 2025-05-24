<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estudio Art & Impression</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@400;500&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #000;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .logo {
            margin: 1rem auto;
            max-width: 200px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: 500;
            font-size: 1.1rem;
            padding: 0.5rem 1rem;
            background-color: #1a73e8;
            border-radius: 25px;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        nav ul li a:hover {
            background-color: #ff6600;
            transform: scale(1.1);
        }

        .hero {
            text-align: center;
            padding: 4rem 1rem;
            background: url('../img/hero.jpg') no-repeat center center/cover;
            color: #fff;
            font-family: 'Playfair Display', serif;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .hero p {
            font-size: 1.5rem;
            text-shadow: 1px 1px 6px rgba(0, 0, 0, 0.7);
        }

        .about {
            padding: 3rem 1rem;
            background-color: #fff;
            text-align: center;
        }

        .about h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #000;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            font-family: 'Roboto', sans-serif;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <img src="img/logo.jpg" alt="Estudio Art & Impression Logo" class="logo">
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="portafolio.html">Portafolio</a></li>
                <li><a href="precios.html">Precios y Promociones</a></li>
                <li><a href="contacto.html">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Bienvenidos a Estudio Art & Impression</h1>
            <p>Capturamos tus momentos más preciados con arte y pasión.</p>
        </section>

        <section class="about">
            <h2>¿Quiénes Somos?</h2>
            <p>Somos un estudio de fotografía especializado en crear recuerdos inolvidables a través de un lente. Descubre nuestra propuesta artística y déjanos contar tu historia en imágenes.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Estudio Art & Impression. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
