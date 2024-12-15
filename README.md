<!DOCTYPE html>
<html lang="es">
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
            border: 0.5cm solid #2c3e50; /* Marco azul de 0.5 cm */
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
        <!-- Sección Material del Curso -->
        <section id="material">
            <h2>Material del Curso</h2>
            <p>Descarga documentos, guías y recursos educativos de matemáticas básicas.</p>
            <ul>
                <li><a href="/materiales/Taller de Matematicas.pdf" download>Taller de Matemáticas</a></li>
                <li><a href="/materiales/introduccion_algebra.pdf" download>Introducción al Álgebra</a></li>
                <li><a href="/materiales/funciones_basicas.pdf" download>Funciones Básicas</a></li>
                <li><a href="/materiales/matematicas_para_ingenieria.pdf" download>Matemáticas para Ingeniería</a></li>
            </ul>
        </section>

        <!-- Sección Página de Apoyo -->
        <section id="apoyo">
            <h2>Página de Apoyo</h2>
            <p>Accede a recursos adicionales para fortalecer tu aprendizaje de matemáticas:</p>
            <ul> 
                <li><a href="http://newton.matem.unam.mx/arquimedes/index.html" target="_blank">Proyecto Arquimedes</a></li>
                <li><a href="https://es.khanacademy.org" target="_blank">Khan Academy: Matemáticas Básicas</a></li>
                <li><a href="http://canek.uam.mx/?secc=1" target="_blank">Introducción al cálculo</a></li>
            </ul>
        </section>

        <!-- Sección Videos Tutoriales -->
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

        <!-- Sección Herramientas Matemáticas -->
        <section id="herramientas">
            <h2>Herramientas Matemáticas</h2>
            <p>Utiliza herramientas en línea para resolver problemas complejos y visualizar conceptos:</p>
            <ul>
                <li><a href="https://www.geogebra.org" target="_blank">GeoGebra: Herramienta Gráfica</a></li>
                <li><a href="https://www.desmos.com" target="_blank">Desmos: Calculadora Gráfica</a></li>
                <li><a href="https://www.symbolab.com" target="_blank">Symbolab: Resolver Ecuaciones</a></li>
            </ul>
        </section>

        <!-- Sección Juegos -->
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

        <!-- Sección Chat -->
        <section id="chat">
            <h2>Chat</h2>
            <p>Habla con otros participantes:</p>
            <div id="chat-box">
                <div id="chat-messages" aria-live="polite">
                    <!-- Aquí se mostrarán los mensajes -->
                </div>
                <label for="chat-message">Escribe tu mensaje:</label>
                <textarea id="chat-message" rows="3" placeholder="Escribe tu mensaje..." required></textarea>
                <button type="button" onclick="enviarMensaje()">Enviar</button>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Curso Interactivo. Todos los derechos reservados.</p>
        <p>¿Necesitas ayuda? <a href="mailto:jlf@azc.uam.mx">Contáctanos</a></p>
    </footer>

    <script>
        function enviarMensaje() {
            const mensajeInput = document.getElementById('chat-message');
            const mensajesContainer = document.getElementById('chat-messages');

            // Obtener el mensaje
            const mensaje = mensajeInput.value.trim();

            // Validar si el mensaje no está vacío
            if (mensaje) {
                // Crear un nuevo elemento para mostrar el mensaje
                const nuevoMensaje = document.createElement('div');
                nuevoMensaje.textContent = mensaje;

                // Agregar el mensaje al contenedor
                mensajesContainer.appendChild(nuevoMensaje);

                // Limpiar el campo de texto
                mensajeInput.value = '';

                // Hacer scroll automático hacia el último mensaje
                mensajesContainer.scrollTop = mensajesContainer.scrollHeight;
            } else {
                alert('Por favor, escribe un mensaje antes de enviarlo.');
            }
        }
    </script>
</body>
</html>
