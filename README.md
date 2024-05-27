# proyectoxnada
Proyecto nada
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto Nada</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #1a1a1a;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            padding: 2rem 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        h1, h2 {
            font-weight: bold;
            font-size: 2rem;
            color: #ffffff;
        }
        h2 {
            margin-top: 2rem;
        }
        nav {
            background-color: #333333;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            color: #ffffff;
            margin: 0 1rem;
            text-decoration: none;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
            margin-top: 2rem;
        }
        .gallery img {
            max-width: 300px;
            border: 3px solid #ffffff;
            border-radius: 10px;
        }
        footer {
            background-color: #333333;
            color: #ffffff;
            text-align: center;
            padding: 2rem 0;
        }
        .contact-info {
            text-align: center;
            margin-bottom: 2rem;
        }
        .logo {
            max-width: 100px;
            margin-bottom: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Proyecto Nada" class="logo">
        <h1>Proyecto Nada</h1>
        <h2>Del todo hacer la nada y en la nada inventarnos</h2>
    </header>
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Artículos</a>
        <a href="#">Contacto</a>
    </nav>
    <div class="container">
        <section>
            <h2>Últimos Artículos</h2>
            <!-- Aquí puedes añadir tus artículos -->
            <article>
                <h3>El laberinto del ser y la nada</h3>
                <p>Explorando los rincones de la existencia humana y la búsqueda de significado en un mundo aparentemente vacío.</p>
            </article>
            <article>
                <h3>Migraciones invisibles: la experiencia latina en tierras extranjeras</h3>
                <p>Reflexiones sobre las experiencias de migración de los latinos y su impacto en la identidad y la sociedad.</p>
            </article>
            <article>
                <h3>El poder de la protesta: política y cambio social</h3>
                <p>Análisis de la importancia de la participación política y las protestas en la configuración del futuro de una sociedad.</p>
            </article>
        </section>
        <section>
            <h2>Galería</h2>
            <div class="gallery">
                <img src="https://source.unsplash.com/random/300x400/?mystery" alt="Mystery Image 1">
                <img src="https://source.unsplash.com/random/300x400/?enigma" alt="Mystery Image 2">
                <img src="https://source.unsplash.com/random/300x400/?dark" alt="Mystery Image 3">
                <img src="https://source.unsplash.com/random/300x400/?secret" alt="Mystery Image 4">
            </div>
        </section>
    </div>
    <footer>
        <div class="contact-info">
            <p>Contacto:</p>
            <p>Correo electrónico: <a href="mailto:contacto@proyectonada.com">contacto@proyectonada.com</a></p>
            <p>Instagram: <a href="https://www.instagram.com/proyectonada">@proyectonada</a></p>
        </div>
        <p>Sitio creado por Proyecto Nada &copy; 2024</p>
    </footer>
</body>
</html>

