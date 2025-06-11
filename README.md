<?php
session_start();

if (!isset($_SESSION["logged_in"]) || $_SESSION["logged_in"] !== true) {
    header("Location: login.php");
    exit();
}
?>

<!DOCTYPE html>
<html lang="es">
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
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background: #2c3e50;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #34495e;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            flex: 1;
            padding: 20px;
        }

        section {
            margin-bottom: 30px;
        }

        footer {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 15px 20px;
        }

        footer a {
            color: #ffcccc;
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
                <li><a href="http://newton.matem.unam.mx/arquimedes/index.html" target="_blank">Proyecto Arquímedes</a></li>
                <li><a href="https://es.khanacademy.org" target="_blank">Khan Academy: Matemáticas Básicas</a></li>
                <li><a href="http://canek.uam.mx/?secc=1" target="_blank">Introducción al Cálculo</a></li>
            </ul>
        </section>

        <section id="videos">
            <h2>Videos Tutoriales</h2>
            <p>Explora videos que explican conceptos clave paso a paso:</p>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=MIUJPkc3x6s&list=PLoxtZmChTSdiqRdRU1OoCR264Isisxdt-" target="_blank">Aritmética</a></li>
                <li><a href="https://www.youtube.com/watch?v=e5L05pvyMr0&list=PL9SnRnlzoyX1sF5fX83CleyK_SATfbhia" target="_blank">Introducción al Álgebra</a></li>
                <li><a href="https://www.youtube.com/watch?v=fZQsWTLFR5g&list=PLZeRcx60JO52LhJmL23FKZtQDjHVmtKY2" target="_blank">Funciones</a></li>
                <li><a href="https://www.youtube.com/watch?v=video3" target="_blank">Cálculo Diferencial Básico</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Curso Interactivo. Todos los derechos reservados.</p>
        <p>¿Necesitas ayuda? <a href="mailto:jlf@azc.uam.mx">Contáctanos</a></p>
        <p><a href="logout.php" style="color: red;">Cerrar Sesión</a></p>
    </footer>
</body>
</html>
