# DISE-O-PAGINAS-WEB
<!DOCTYPE html>
<html lang="es">
<head>
    <title>Perfumería Handeli - Básico</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Perfumería Fina Handeli</h1>
        <nav>
            <a href="#productos">Ver Productos</a>
        </nav>
    </header>

    <main>
        <section>
            <article id="productos">
                <h2>Nuestros Productos</h2>
                <h3>Línea de la Casa</h3>
                <p>
                    Tenemos <strong>esencias de alta calidad</strong>. Son <em>increíbles</em>.
                </p>

                <ul>
                    <li>Femeninas</li>
                    <li>Masculinas</li>
                    <li>Árabes</li>
                </ul>

                <ol>
                    <li>Elige tu esencia.</li>
                    <li>Elige el tamaño.</li>
                    <li>Disfruta tu perfume.</li>
                </ol>

                <table>
                    <thead>
                        <tr>
                            <th>Tamaño</th>
                            <th>Precio</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>100ml</td>
                            <td>$25</td>
                        </tr>
                        <tr>
                            <td>50ml</td>
                            <td>$15</td>
                        </tr>
                    </tbody>
                </table>
                
                <img src="assets/img/presentacion.jpg" alt="Perfume y crema de Handeli">

                <video controls>
                    <source src="assets/video/promo.mp4" type="video/mp4">
                </video>

                <form>
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre">
                    <br><br>
                    <label for="correo">Correo:</label>
                    <input type="email" id="correo" name="correo">
                    <br><br>
                    <button type="submit">Enviar</button>
                </form>

            </article>
        </section>
    </main>

    <footer>
        <p>Contacto y redes sociales.</p>
        <a href="https://www.instagram.com" target="_blank">Nuestro Instagram</a>
    </footer>

</body>
</html>
