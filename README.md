<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIMO Servicios</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://example.com/construction-background.jpg'); /* Cambia esta URL por una imagen adecuada */
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
        }
        header {
            background-color: rgba(51, 51, 51, 0.8);
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(68, 68, 68, 0.8);
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 8px;
        }
        .section {
            background-color: #fff;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: rgba(51, 51, 51, 0.8);
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>VIMO Servicios</h1>
        <p>Construimos el futuro contigo</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="container">
        <section id="inicio" class="section">
            <h2>Bienvenidos a VIMO</h2>
            <p>Somos una empresa líder en ingeniería y construcción, comprometida con ofrecer servicios de calidad para tus proyectos. Descubre todo lo que podemos hacer por ti.</p>
        </section>

        <section id="servicios" class="section">
            <h2>Nuestros Servicios</h2>
            <h3>Ingeniería y Construcción</h3>
            <ul>
                <li>Preparación de terrenos</li>
                <li>Construcción de edificios y obras civiles</li>
                <li>Carreteras, puentes, y estructuras metálicas</li>
            </ul>

            <h3>Consultoría y Supervisión</h3>
            <ul>
                <li>Asesoramiento técnico para proyectos</li>
                <li>Tasación y valorización de edificaciones</li>
            </ul>

            <h3>Venta de Artículos</h3>
            <ul>
                <li>Equipos de protección personal (EPPs)</li>
                <li>Útiles de oficina y papelería</li>
                <li>Abarrotes al por mayor y menor</li>
            </ul>
        </section>

        <section id="proyectos" class="section">
            <h2>Proyectos Destacados</h2>
            <p>Explora algunos de nuestros proyectos más recientes en ingeniería y construcción.</p>
            <!-- Aquí puedes agregar una galería de imágenes -->
        </section>

        <section id="contacto" class="section">
            <h2>Contacto</h2>
            <p>¿Tienes alguna consulta? Contáctanos a través del siguiente formulario:</p>
            <form>
                <label for="name">Nombre:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Correo Electrónico:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Mensaje:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>

                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 VIMO Servicios. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
