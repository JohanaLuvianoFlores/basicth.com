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
            background: #f4f4f4;
            color: #000;
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
