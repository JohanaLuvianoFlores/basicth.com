<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal de Matemáticas Básicas</title>
    <style>
        /* Configuración básica del marco */
        html {
            margin: 0;
            padding: 0;
            min-height: 100%;
            border: 0.5cm solid #2c3e50;
            box-sizing: border-box;
        }
        *, *::before, *::after {
            box-sizing: inherit;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            min-height: 100%;
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
            flex-grow: 1;
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
        <!-- Sección Material del Curso -->
        <section id="material">
            <h2>Material del Curso</h2>
            <p>Descarga documentos y recursos educativos de matemáticas básicas.</p>
            <ul>
                <li><a href="https://drive.google.com/file/d/1KEOnChlO5jzvuQN6xRvIqdzs8qrMSj1V/view?usp=sharing" target="_blank" rel="noopener noreferrer">Libro de Taller de Matemáticas</a></li>
                <li><a href="https://drive.google.com/file/d/1V24coWn2FZLf4OP7-oJMRgfSHR0Zy7cz/view?usp=sharing" target="_blank" rel="noopener noreferrer">Álgebra Baldor</a></li>
                <li><a href="https://drive.google.com/file/d/1FXqNL3ZgGjZgfGHeBKSpMfJ_4isrfp8E/view?usp=sharing" target="_blank" rel="noopener noreferrer">Geometría Analítica</a></li>
                <li><a href="https://drive.google.com/file/d/19ZffaZCbwRuRp_ny-KyFDyv2PKTvu3ez/view?usp=sharing" target="_blank" rel="noopener noreferrer">Cálculo</a></li>
            </ul>
        </section>

        <!-- Sección Página de Apoyo -->
        <section id="apoyo">
            <h2>Página de Apoyo</h2>
            <p>Accede a recursos adicionales para fortalecer tu aprendizaje de matemáticas:</p>
            <ul> 
                <li><a href="http://newton.matem.unam.mx/arquimedes/index.html" target="_blank" rel="noopener noreferrer">Proyecto Arquimedes</a></li>
                <li><a href="https://es.khanacademy.org" target="_blank" rel="noopener noreferrer">Khan Academy: Matemáticas Básicas</a></li>
                <li><a href="http://canek.uam.mx/?secc=1" target="_blank" rel="noopener noreferrer">Introducción al cálculo</a></li>
                <li><a href="https://portalacademico.cch.unam.mx/alumno/matematicas1" target="_blank" rel="noopener noreferrer">Matemáticas</a></li>
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
                <li><a href="https://www.youtube.com/watch?v=rX0kSP4aQIQ&list=PLDrYCU02ie-F3ngZ3VHIuaDl5Ay2Ly5Ik">Precálculo</a></li>
            </ul>
        </section>

        <!-- Sección Juegos -->
        <section id="juegos">
            <h2>Juegos</h2>
            <p>Diviértete aprendiendo con estos juegos:</p>
            <ul>
                <li><a href="https://mathigon.org/polypad" target="_blank" rel="noopener noreferrer">Exploración Matemática</a></li>
                <li><a href="https://brilliant.org/" target="_blank" rel="noopener noreferrer">Problemas Desafiantes para Matemáticos</a></li>
                <li><a href="https://puzzling.stackexchange.com/" target="_blank" rel="noopener noreferrer">Puzzles y Lógica Matemática</a></li>
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
        const socket = new WebSocket('wss://example.com/chat'); // Cambiar a tu servidor WebSocket real

        const mensajesContainer = document.getElementById('chat-messages');
        const mensajeInput = document.getElementById('chat-message');

        socket.addEventListener('message', (event) => {
            const mensaje = document.createElement('div');
            mensaje.textContent = event.data;
            mensajesContainer.appendChild(mensaje);
            mensajesContainer.scrollTop = mensajesContainer.scrollHeight;
        });

        function enviarMensaje() {
            const mensaje = mensajeInput.value.trim();
            if (mensaje) {
                socket.send(mensaje);
                mensajeInput.value = '';
            } else {
                alert('Por favor, escribe un mensaje antes de enviarlo.');
            }
        }
    </script>
</body>
</html>
