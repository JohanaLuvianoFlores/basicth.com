<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal de Matemáticas Básicas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
            border: 5px solid #2c3e50; /* Marco azul del color del encabezado */
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
            background: #f4f4f4; /* Fondo neutro para el pie de página */
            color: #000; /* Texto en negro para contraste */
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

        <section id="apoyo">
            <h2>Página de Apoyo</h2>
            <p>Accede a recursos adicionales para fortalecer tu aprendizaje de matemáticas:</p>
            <ul> 
                <li><a href="http://newton.matem.unam.mx/arquimedes/index.html" target="_blank">Proyecto Arquimedes</a></li>
                <li><a href="https://es.khanacademy.org" target="_blank">Khan Academy: Matemáticas Básicas</a></li>
                <li><a href="http://canek.uam.mx/?secc=1" target="_blank">Introducción al cálculo</a></li>
            </ul>
        </section>

        <section id="videos">
            <h2>Videos Tutoriales</h2>
            <p>Explora videos que explican conceptos clave paso a paso:</p>
            <ul>  
                <li><a href="https://www.youtube.com/watch?v=MIUJPkc3x6s&list=PLoxtZmChTSdiqRdRU1OoCR264Isisxdt-">Aritmética</a></li>
                <li><a href="https://www.youtube.com/watch?v=e5L05pvyMr0&list=PL9SnRnlzoyX1sF5fX83CleyK_SATfbhia">Introducción al Álgebra</a></li>
                <li><a href="https://www.youtube.com/watch?v=fZQsWTLFR5g&list=PLZeRcx60JO52LhJmL23FKZtQDjHVmtKY2">Funciones</a></li>
                <li><a href="https://www.youtube.com/watch?v=4T0EnQ4BiVg" target="_blank">Cálculo Diferencial Básico</a></li>
            </ul>
        </section>

        <section id="herramientas">
            <h2>Herramientas Matemáticas</h2>
            <p>Utiliza herramientas en línea para resolver problemas complejos y visualizar conceptos:</p>
            <ul>
                <li><a href="https://www.geogebra.org" target="_blank">GeoGebra: Herramienta Gráfica</a></li>
                <li><a href="https://www.desmos.com" target="_blank">Desmos: Calculadora Gráfica</a></li>
                <li><a href="https://www.symbolab.com" target="_blank">Symbolab: Resolver Ecuaciones</a></li>
            </ul>
        </section>

        <section id="tareas">
            <h2>Tareas</h2>
            <p>Aquí puedes subir y acceder a las tareas del curso de matemáticas básicas.</p>
            <form action="https://ejemplo-servidor.com/subir" method="POST" enctype="multipart/form-data">
                <label for="upload-tarea">Subir Tarea:</label>
                <input type="file" id="upload-tarea" name="upload-tarea">
                <button type="submit">Subir</button>
            </form>
            <p><strong>Ejemplos de tareas disponibles:</strong></p>
            <ul>
                <li><a href="/tareas/problemas-aritmeticos.pdf" download>Problemas Aritméticos</a></li>
                <li><a href="/tareas/ecuaciones-basicas.pdf" download>Ecuaciones Básicas</a></li>
                <li><a href="/tareas/funciones-y-graficas.pdf" download>Funciones y Gráficas</a></li>
            </ul>
        </section>

        <section id="autoevaluaciones">
            <h2>Autoevaluaciones</h2>
            <p>Pon a prueba tus conocimientos:</p>
            <ul>
                <li><a href="http://newton.matem.unam.mx/aritmetica/index.html" target="_blank">Ejercicios y problemas de aritmética y álgebra</a></li>
                <li><a href="http://newton.matem.unam.mx/tareas/algebraV.html" target="_blank">Autoevaluación de álgebra</a></li>
                <li><a href="https://es.khanacademy.org/math/arithmetic" target="_blank">Ejercicios de Aritmética</a></li>
                <li><a href="https://es.khanacademy.org/math/algebra" target="_blank">Ejercicios de Álgebra</a></li>
                <li><a href="https://es.khanacademy.org/math/geometry" target="_blank">Ejercicios de Geometría</a></li>
                <li><a href="https://es.khanacademy.org/math/geometry/hs-geo-analytic-geometry/hs-geo-parallel-perpendicular-eq/test/hs-geo-analytic-geometry-unit-test" target="_blank">Ejercicios de Geometría Analítica</a></li>
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
