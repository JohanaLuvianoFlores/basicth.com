<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal de Matemáticas Básicas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
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
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
        }
        footer {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 10px 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        #chat-container {
            margin-top: 20px;
            border: 1px solid #ccc;
            padding: 10px;
            background-color: #fff;
        }
        #messages {
            height: 200px;
            overflow-y: scroll;
            border: 1px solid #ccc;
            padding: 5px;
            margin-bottom: 10px;
            background-color: #f9f9f9;
        }
        #messages div {
            margin-bottom: 10px;
        }
        #chat-input {
            display: flex;
        }
        #chat-input input {
            flex: 1;
            padding: 10px;
            border: 1px solid #ccc;
        }
        #chat-input button {
            padding: 10px;
            background-color: #2c3e50;
            color: white;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portal de Matemáticas Básicas</h1>
    </header>
    <nav>
        <a href="#tareas">Tareas</a>
        <a href="#juegos">Juegos</a>
        <a href="#material">Material del Curso</a>
        <a href="#apoyo">Página de Apoyo</a>
        <a href="#videos">Videos Tutoriales</a>
        <a href="#herramientas">Herramientas</a>
        <a href="#evaluaciones">Evaluaciones</a>
        <a href="#chat">Chat</a>
    </nav>

    <p style="text-align: center; font-weight: bold;">Esta página es privada. Por favor, envía un correo con tus datos a <a href='mailto:jlf@azc.uam.mx' style='color: blue;'>jlf@azc.uam.mx</a> para solicitar acceso.</p>
    <main>
        <section id="material">
            <h2>Material del Curso</h2>
            <ul>
                <li>Aritmética</li>
                <li>Álgebra</li>
                <li>Geometría</li>
                <li>Geometría Analítica</li>
                <li>Trigonometría</li>
                <li>Funciones</li>
            </ul>
        </section>

        <section id="videos">
            <h2>Videos</h2>
            <p>Explora nuestros videos educativos:</p>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=EXAMPLE1" target="_blank">Introducción a la Aritmética</a></li>
                <li><a href="https://www.youtube.com/watch?v=EXAMPLE2" target="_blank">Fundamentos de Álgebra</a></li>
                <li><a href="https://www.youtube.com/watch?v=EXAMPLE3" target="_blank">Conceptos Básicos de Geometría</a></li>
                <li><a href="https://www.youtube.com/watch?v=EXAMPLE4" target="_blank">Geometría Analítica Avanzada</a></li>
                <li><a href="https://www.youtube.com/watch?v=EXAMPLE5" target="_blank">Trigonometría para Ingenieros</a></li>
                <li><a href="https://www.youtube.com/watch?v=EXAMPLE6" target="_blank">Funciones y Modelos</a></li>
            </ul>
        </section>

        <section id="autoevaluaciones">
            <h2>Autoevaluaciones</h2>
            <p>Pon a prueba tus conocimientos:</p>
            <ul>
                <li><a href="https://es.khanacademy.org/math/arithmetic" target="_blank">Ejercicios de Aritmética</a></li>
                <li><a href="https://es.khanacademy.org/math/algebra" target="_blank">Ejercicios de Álgebra</a></li>
                <li><a href="https://es.khanacademy.org/math/geometry" target="_blank">Ejercicios de Geometría</a></li>
                <li><a href="https://es.khanacademy.org/math/geometry-analytic" target="_blank">Ejercicios de Geometría Analítica</a></li>
                <li><a href="https://es.khanacademy.org/math/trigonometry" target="_blank">Ejercicios de Trigonometría</a></li>
                <li><a href="https://es.khanacademy.org/math/precalculus/precalc-functions" target="_blank">Ejercicios de Funciones</a></li>
            </ul>
        </section>

        <section id="juegos">
            <h2>Juegos</h2>
            <p>Diviértete aprendiendo con estos juegos:</p>
            <ul>
                <li><a href="https://mathigon.org/polypad" target="_blank">Exploración Matemática</a></li>
                <li><a href="https://brilliant.org/" target="_blank">Problemas Desafiantes para Matemáticos</a></li>
                <li><a href="https://puzzling.stackexchange.com/" target="_blank">Puzzles y Lógica Matemática</a></li>
                <li><a href="https://www.geogebra.org/classic" target="_blank">Geometría Interactiva</a></li>
                <li><a href="https://mathsstarters.net/" target="_blank">Desafíos Matemáticos Rápidos</a></li>
            </ul>
        </section>

        <section id="chat">
            <h2>Chat</h2>
            <p>Habla con otros participantes:</p>
            <div id="chat-box">
               <button onclick="enviarMensaje()">Enviar</button>
            </div>
        </sectio   <textarea id="chat-input" placeholder="Escribe tu mensaje..."></textarea>
              n>
    </main>

    <footer>
        <p>&copy; 2024 Curso Interactivo. Todos los derechos reservados.</p>
        <p>¿Necesitas ayuda? <a href="mailto:jlf@azc.uam.mx">Contáctanos</a></p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
