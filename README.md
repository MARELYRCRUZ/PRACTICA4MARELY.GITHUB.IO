# PRACTICA4MARELY.GITHUB.IO
MARELY RAMOS CRUZ
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio de Desarrollo Profesional</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            margin-bottom: 20px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 2rem;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #00ff88;
        }

        .hero {
            text-align: center;
            padding: 4rem 0;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
                        url('https://source.unsplash.com/random/1920x1080') center/cover;
            color: #fff;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem 0;
        }

        .project-card {
            background: #fff;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            nav {
                flex-direction: column;
                text-align: center;
            }

            nav ul {
                margin-top: 1rem;
                flex-direction: column;
            }

            nav ul li {
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav class="container">
            <h1>Mi Portafolio</h1>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="container">
            <h2>Desarrollador Full Stack</h2>
            <p>Especializado en soluciones web modernas y escalables</p>
        </div>
    </section>

    <main class="container">
        <section id="proyectos" class="projects">
            <article class="project-card">
                <h3>Sistema de Gestión</h3>
                <p>Aplicación web empresarial desarrollada con React y Node.js</p>
            </article>
            
            <article class="project-card">
                <h3>E-commerce</h3>
                <p>Plataforma de ventas online con pasarela de pagos integrada</p>
            </article>
            
            <article class="project-card">
                <h3>App Móvil</h3>
                <p>Aplicación nativa para iOS y Android con React Native</p>
            </article>
        </section>

        <section id="contacto" class="contact-form">
            <h2>Contacto</h2>
            <form>
                <div>
                    <label>Nombre:</label>
                    <input type="text" required>
                </div>
                <div>
                    <label>Email:</label>
                    <input type="email" required>
                </div>
                <div>
                    <label>Mensaje:</label>
                    <textarea required></textarea>
                </div>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Portafolio Profesional. Todos los derechos reservados.</p>
        </div>
    </footer>
</body>
</html>
