<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Una pequeña introducción al mundo de las matemáticas básicas para ingenieros</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body style="background-image: url('https://www.uam.mx/img/azcapotzalco_rojo_blanco.jpg'); background-size: cover; background-repeat: no-repeat; background-attachment: fixed;">
    <header>
        <h1>Una pequeña introducción al mundo de las matemáticas básicas para ingenieros</h1>
        <nav>
            <ul>
                <li><a href="#material">Material del Curso</a></li>
                <li><a href="#videos">Videos</a></li>
                <li><a href="#autoevaluaciones">Autoevaluaciones</a></li>
                <li><a href="#juegos">Juegos</a></li>
                <li><a href="#chat">Chat</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="material">
            <h2>Material del Curso</h2>
            <p>Aquí encontrarás todo el material necesario para tu aprendizaje.</p>
        </section>

        <section id="videos">
            <h2>Videos</h2>
            <p>Explora nuestros videos educativos:</p>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=OzjfekXYd_g" target="_blank">Aritmética Básica</a></li>
                <li><a href="https://www.youtube.com/watch?v=MP-_JWEp2ZM" target="_blank">Álgebra</a></li>
                <li><a href="https://www.youtube.com/watch?v=kaoAOzNke3Q" target="_blank">Geometría</a></li>
                <li><a href="https://www.youtube.com/watch?v=5jUTdZO3Yvc" target="_blank">Geometría Analítica</a></li>
                <li><a href="https://www.youtube.com/watch?v=ScGwBGggSmg" target="_blank">Trigonometría</a></li>
                <li><a href="https://www.youtube.com/watch?v=wXJGuz94Drw" target="_blank">Funciones</a></li>
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
            <button onclick="iniciarAutoevaluacion()">Iniciar Autoevaluación</button>
        </section>

        <section id="juegos">
            <h2>Juegos</h2>
            <p>Diviértete aprendiendo con estos juegos:</p>
            <ul>
                <li><a href="https://www.brainzilla.com/logic/logic-games/sudoku/" target="_blank">Sudoku</a></li>
                <li><a href="https://www.chess.com/play" target="_blank">Ajedrez</a></li>
                <li><a href="https://www.puzzleprime.com/" target="_blank">Rompecabezas y Problemas Lógicos</a></li>
                <li><a href="https://www.geogebra.org/classic" target="_blank">Geometría Interactiva</a></li>
                <li><a href="https://www.khanacademy.org/math" target="_blank">Juegos Matemáticos Khan Academy</a></li>
            </ul>
        </section>

        <section id="chat">
            <h2>Chat</h2>
            <p>Habla con otros participantes:</p>
            <div id="chat-box">
                <textarea id="chat-input" placeholder="Escribe tu mensaje..."></textarea>
                <button onclick="enviarMensaje()">Enviar</button>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Curso Interactivo. Todos los derechos reservados.</p>
        <p>¿Necesitas ayuda? <a href="mailto:jlf@azc.uam.mx">Contáctanos</a></p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
