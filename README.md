<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tradiciones Mexicanas - Día de Muertos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff8f0;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #d32f2f;
            color: white;
            text-align: center;
            padding: 30px 0;
        }

        nav {
            background-color: #f5c6c6;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: #333;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #d32f2f;
        }

        h1 {
            margin: 0;
            font-size: 2.5em;
        }

        main {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }

        h2 {
            color: #d32f2f;
            border-bottom: 2px solid #d32f2f;
            padding-bottom: 5px;
        }

        p {
            line-height: 1.6;
        }

        .imagen {
            text-align: center;
            margin: 20px 0;
        }

        .imagen img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        footer {
            background-color: #d32f2f;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 40px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        th, td {
            border: 1px solid #d32f2f;
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #f5c6c6;
        }

        /* === ESTILOS DEL FORMULARIO === */
        #satisfaccion {
            background-color: #fdecea;
            padding: 25px;
            border-radius: 10px;
            margin-top: 40px;
        }

        #satisfaccion h2 {
            color: #b71c1c;
        }

        form {
            margin-top: 15px;
        }

        label {
            font-weight: bold;
        }

        input, select, textarea, button {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #d32f2f;
            border-radius: 5px;
            font-size: 1em;
        }

        button {
            background-color: #d32f2f;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }

        button:hover {
            background-color: #b71c1c;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tradiciones Mexicanas</h1>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#lugares">Lugares Turísticos</a>
        <a href="#catrina">La Catrina</a>
        <a href="#satisfaccion">Opinión</a>
    </nav>

    <main id="inicio">
        <h2>Día de Muertos</h2>
        <p>
            El <strong>Día de Muertos</strong> es una de las tradiciones más importantes de México, celebrada el <strong>1 y 2 de noviembre</strong>.
            Es una fecha en la que las familias recuerdan a sus seres queridos con amor y respeto, decorando altares con flores de cempasúchil,
            velas, fotografías y sus alimentos favoritos.
        </p>

        <div class="imagen">
            <img src="https://www.gob.mx/cms/uploads/article/main_image/26574/proyecto-mixquic-mixquic3.jpg" alt="Ofrenda Día de Muertos">
        </div>

        <h2 id="lugares">Lugares Turísticos Tradicionales</h2>
        <p>
            Algunos lugares en México se destacan por sus celebraciones del Día de Muertos. Aquí te mostramos algunos de los más visitados y sus costos aproximados:
        </p>

        <table>
            <tr>
                <th>Lugar</th>
                <th>Ubicación</th>
                <th>Entrada Aproximada</th>
                <th>Enlace Externo</th>
            </tr>
            <tr>
                <td>Mixquic</td>
                <td>Ciudad de México</td>
                <td>Gratuita</td>
                <td><a href="https://www.mexicodesconocido.com.mx/mixquic-dia-de-muertos.html" target="_blank">Visitar sitio</a></td>
            </tr>
            <tr>
                <td>Pátzcuaro y Janitzio</td>
                <td>Michoacán</td>
                <td>$50 - $100 MXN (traslado en lancha)</td>
                <td><a href="https://www.visitmichoacan.com.mx/" target="_blank">Visitar sitio</a></td>
            </tr>
            <tr>
                <td>Oaxaca</td>
                <td>Oaxaca de Juárez</td>
                <td>Gratuita</td>
                <td><a href="https://www.visitmexico.com/oaxaca" target="_blank">Visitar sitio</a></td>
            </tr>
            <tr>
                <td>San Andrés Mixquic</td>
                <td>Tláhuac, CDMX</td>
                <td>Gratuita</td>
                <td><a href="https://cdmx.gob.mx/" target="_blank">Visitar sitio</a></td>
            </tr>
        </table>

        <div class="imagen">
            <img src="https://cdn.espirituaventurero.com.mx/images/63cb01874374794ae99d4e51ae033e26.jpg" alt="Janitzio en Día de Muertos">
        </div>

        <h2 id="catrina">Origen de La Catrina</h2>
        <p>
            La famosa <strong>Catrina</strong> fue creada por el ilustrador <em>José Guadalupe Posada</em> a inicios del siglo XX.
            Es un símbolo que recuerda que la muerte llega a todos sin importar la clase social.
        </p>

        <div class="imagen">
            <img src="https://storage.googleapis.com/gx-global-cms/mkt/6d6cb90f-9946-4520-9569-6a5efe4ac5c2.png" alt="La Catrina">
        </div>

        <p>
            Si deseas conocer más sobre las celebraciones, visita la página oficial del 
            <a href="https://www.gob.mx/cultura" target="_blank">Gobierno de México - Cultura</a>.
        </p>

        <!-- === FORMULARIO DE SATISFACCIÓN === -->
        <section id="satisfaccion">
            <h2>Formulario de Satisfacción</h2>
            <p>Tu opinión es muy importante para nosotros. Por favor, llena este breve formulario:</p>

            <form action="https://formsubmit.co/TU_CORREO@ejemplo.com" method="POST">
                <label for="nombre">Nombre:</label><br>
                <input type="text" id="nombre" name="nombre" required><br><br>

                <label for="correo">Correo electrónico:</label><br>
                <input type="email" id="correo" name="correo" required><br><br>

                <label for="satisfaccion">Nivel de satisfacción:</label><br>
                <select id="satisfaccion" name="satisfaccion" required>
                    <option value="">Selecciona una opción</option>
                    <option value="Excelente">Excelente</option>
                    <option value="Buena">Buena</option>
                    <option value="Regular">Regular</option>
                    <option value="Mala">Mala</option>
                </select><br><br>

                <label for="comentarios">Comentarios adicionales:</label><br>
                <textarea id="comentarios" name="comentarios" rows="4" cols="50"></textarea><br><br>

                <!-- Evita el captcha y define la página de confirmación -->
                <input type="hidden" name="_captcha" value="false">
                <input type="hidden" name="_next" value="https://tusitio.com/gracias.html">

                <button type="submit">Enviar</button>
            </form>
        </section>

    </main>

    <footer>
        <p>© 2025 Tradiciones Mexicanas | Elaborado por [Tu Nombre]</p>
        <a href="#inicio" style="color: white;">Volver al inicio</a>
    </footer>
</body>
</html>

