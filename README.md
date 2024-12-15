<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal de Matemáticas Básicas</title>
    <style>
        /* Estructura básica */
        html {
            height: 100%; /* Asegura que el html cubra toda la ventana */
            box-sizing: border-box; /* Incluye el borde en el cálculo del tamaño */
            border: 0.5cm solid #2c3e50; /* Marco azul de 0.5 cm */
        }

        *, *::before, *::after {
            box-sizing: inherit; /* Asegura el cálculo correcto para todos los elementos */
        }

        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            min-height: 100%; /* Asegura que el contenido siempre llene la ventana */
        }

        header {
            background: #2c3e50;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }

        nav {
            background: #34495e;
            padding: 10px 20px;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            flex-grow: 1; /* Ocupa el espacio restante */
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
        }

        footer {
            background: #f4f4f4;
            color: #000;
            text-align: center;
            padding: 10px 20px;
        }

        #chat-box {
            border: 1px solid #ccc;
            padding: 10px;
            margin-top: 20px;
            background-color: #fff;
        }

        #chat-messages {
            height: 200px;
            overflow-y: auto;
            border: 1px solid #ddd;
            margin-bottom: 10px;
            padding: 10px;
            background-color: #f9f9f9;
        }

        #chat-messages div {
            margin-bottom: 10px;
        }

        #chat-message {
            width: calc(100% - 110px);
            margin-right: 10px;
            resize: none;
        }

        button {
            padding: 10px;
            background-color: #2c3e50;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #34495e;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portal de Matemáticas Básicas</h1>
    </header>
    <nav>
        <a href="#material">Material del Curso</a>
        <a href="#apoyo">Página de Apoyo</a>
        <a href="#videos">Videos Tutoriales</a>
        <a href="#herramientas">Herramientas</a>
        <a href="#evaluaciones">Evaluaciones</a>
        <a href="#tareas">Tareas</a>
        <a href="#juegos">Juegos</a>
        <a href="#chat">Chat</a>
    </nav>
    <main>
        <!-- Contenido principal -->
        <section id="material">
            <h2>Material del Curso</h2>
            <p>Descarga documentos, guías y recursos educativos de matemáticas básicas.</p>
            <ul>
                <li><a href="/materiales/guia_aritmetica.pdf" download>Guía de Aritmética</a></li>
                <li><a href="/materiales/introduccion_algebra.pdf" download>Introducción al Álgebra</a></li>
                <li><a href="/materiales/funciones_basicas.pdf" download>Funciones Básicas</a></li>
                <li><a href="/materiales/matematicas_para_ingenieria.pdf" download>Matemáticas para Ingeniería</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Curso Interactivo. Todos los derechos reservados.</p>
        <p>¿Necesitas ayuda? <a href="mailto:jlf@azc.uam.mx">Contáctanos</a></p>
    </footer>
</body>
</html>
