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
    <main>
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
        <section id="juegos">
            <h2>Juegos Matemáticos</h2>
            <p>Participa en juegos interactivos para reforzar tus conocimientos de matemáticas.</p>
            <ul>
                <li><a href="https://www.educaplay.com" target="_blank">Educaplay: Juegos Matemáticos</a></li>
                <li><a href="https://www.cerebriti.com/matematicas" target="_blank">Cerebriti: Retos Matemáticos</a></li>
                <li><a href="https://www.mathplayground.com" target="_blank">Math Playground</a></li>
            </ul>
        </section>
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
                <li><a href="https://es.khanacademy.org" target="_blank">Khan Academy: Matemáticas Básicas</a></li>
            </ul>
        </section>
        <section id="videos">
            <h2>Videos Tutoriales</h2>
            <p>Explora videos que explican conceptos clave paso a paso:</p>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=video1" target="_blank">Introducción al Álgebra</a></li>
                <li><a href="https://www.youtube.com/watch?v=video2" target="_blank">Gráficas de Funciones</a></li>
                <li><a href="https://www.youtube.com/watch?v=video3" target="_blank">Cálculo Diferencial Básico</a></li>
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
        <section id="evaluaciones">
            <h2>Evaluaciones Básicas</h2>
            <p>Realiza evaluaciones interactivas para medir tus conocimientos y recibe retroalimentación inmediata:</p>
            <form onsubmit="return evaluar()">
                <p>1. ¿Cuál es el resultado de 5 + 3?</p>
                <input type="radio" name="q1" value="6"> 6<br>
                <input type="radio" name="q1" value="8"> 8<br>
                <input type="radio" name="q1" value="10"> 10<br>

                <p>2. ¿Cuál es el valor de x en la ecuación 2x = 10?</p>
                <input type="radio" name="q2" value="2"> 2<br>
                <input type="radio" name="q2" value="5"> 5<br>
                <input type="radio" name="q2" value="10"> 10<br>

                <button type="submit">Enviar</button>
            </form>
            <p id="resultado"></p>
            <script>
                function evaluar() {
                    let puntaje = 0;
                    const respuestas = {
                        q1: '8',
                        q2: '5'
