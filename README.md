<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miguelki Network MC Launcher</title>
    <link rel="icon" href="favicon.png" type="image/png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #e0e0e0;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-top: 50px;
        }

        .header img {
            width: 100px;
            height: 100px;
        }

        .header h1 {
            font-size: 2.5em;
            margin: 20px 0;
            color: #fff;
        }

        .stats {
            display: flex;
            justify-content: center;
            margin: 50px 0;
        }

        .stats div {
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            text-align: center;
            flex: 1;
            margin: 0 10px;
            position: relative;
        }

        .stats div p {
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 22px;
            font-weight: bold;
            color: #fff;
        }

        .stats div p::after {
            content: '';
            width: 10px;
            height: 10px;
            background-color: #00ff00;
            border-radius: 50%;
            margin-left: 10px;
            animation: pulse 1s infinite;
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.5);
            }
            100% {
                transform: scale(1);
            }
        }

        .description {
            text-align: justify;
            margin: 50px 0;
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .description p {
            margin: 0;
            color: #fff;
            font-size: 18px;
            font-weight: bold;
        }

        .carousel {
            display: flex;
            justify-content: center;
            overflow-x: auto;
            scroll-behavior: smooth;
        }

        .carousel img {
            width: 375px;
            height: 225px;
            margin: 0 10px;
            border-radius: 10px;
        }

        /* Scrollbar styles */
        ::-webkit-scrollbar {
            width: 12px;
        }

        ::-webkit-scrollbar-track {
            background: #1e1e1e;
        }

        ::-webkit-scrollbar-thumb {
            background-color: #007bff;
            border-radius: 10px;
            border: 3px solid #1e1e1e;
        }

        .credits {
            display: flex;
            align-items: center;
            margin: 50px 0;
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .credits img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-right: 20px;
        }

        .credits div {
            flex: 1;
        }

        .credits h2 {
            margin: 0;
            color: #fff;
        }

        .credits .social-buttons {
            margin-top: 10px;
        }

        .credits .social-buttons a {
            margin: 0 10px;
            text-decoration: none;
            color: #fff;
            font-size: 1.5em;
            transition: color 0.3s;
        }

        .credits .social-buttons a:hover {
            color: #007bff;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="header">
            <img src="favicon.png" alt="Favicon">
            <h1>Miguelki Network MC Launcher</h1>
        </div>
        <div class="stats">
            <div>
                <h2>Usuarios activos</h2>
                <p>
                    1                </p>
            </div>
        </div>
        <div class="description">
            <p>Miguelki Network MC Launcher es la versión más refinada y moderna de Selvania Launcher, diseñada para ofrecer una experiencia optimizada y visualmente atractiva. Su interfaz ha sido mejorada con un diseño intuitivo y fluido, brindando una navegación más cómoda y agradable para los jugadores.<br><br>

                Este launcher está especialmente optimizado para su uso en servidores y eventos, permitiendo una conexión rápida y estable con una configuración simplificada. Además, cuenta con un panel de administración que facilita la gestión de jugadores y ajustes del servidor, haciendo que la organización de partidas y torneos sea más eficiente.<br><br>

                Como una función adicional, incluye un sistema anticheat que ayuda a mantener la experiencia de juego justa sin afectar el rendimiento ni la fluidez del launcher. Con su enfoque en la estética, la optimización y la facilidad de uso, Miguelki Network MC Launcher es la mejor opción para comunidades que buscan una herramienta moderna y eficiente.</p><br>
            <div class="carousel">
                <img src="img/launcher1.png" alt="Image 1">
                <img src="img/launcher2.png" alt="Image 2">
                <img src="img/launcher3.png" alt="Image 3">
            </div>
        </div>
        <div class="credits">
            <img src="img/pfp.png" alt="Profile picture">
            <div>
                <h2>Miguelki</h2>
                <div class="social-buttons">
                    <a href="https://x.com/miguelkix30" target="_blank"><i class="fab fa-twitter"></i></a>
                    <a href="https://github.com/miguelkix30" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="https://dsc.gg/miguelkinetwork" target="_blank"><i class="fab fa-discord"></i></a>
                </div>
            </div>
        </div>
        <footer style="text-align: center; margin-top: 20px; color: #fff;">
            Versión de la API: 5.0.13        </footer>
    </div>
</body>

</html>
