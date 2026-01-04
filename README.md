# CienciaYtecnologia
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ciencia & Tech Global - Noticias Veraces</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 2rem;
            display: grid;
            grid-template-columns: 3fr 1fr;
            gap: 2rem;
        }
        .news-card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin-bottom: 1.5rem;
        }
        .news-card h2 {
            color: #2980b9;
            margin-bottom: 0.8rem;
            font-size: 1.4rem;
        }
        .news-date {
            color: #7f8c8d;
            font-size: 0.9rem;
            margin-bottom: 1rem;
            display: block;
        }
        .news-summary {
            line-height: 1.6;
            margin-bottom: 1rem;
        }
        .news-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 4px;
            margin-bottom: 1rem;
        }
        .sidebar {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .sidebar h3 {
            color: #2c3e50;
            margin-bottom: 1rem;
            border-bottom: 2px solid #2980b9;
            padding-bottom: 0.5rem;
        }
        .sidebar-item {
            margin-bottom: 0.8rem;
            line-height: 1.5;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        /* Adaptación móvil */
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Ciencia & Tech Global</h1>
        <p>Noticias veraces y accesibles sobre avances mundiales</p>
    </header>

    <main class="container">
        <!-- Sección principal de noticias -->
        <section class="main-news">
            <!-- Noticia destacada -->
            <article class="news-card">
                <h2>Nuevo telescopio espacial detecta exoplanetas con condiciones habitables</h2>
                <span class="news-date">04 de enero de 2026 - Fuente: Agencia Espacial Europea (ESA)</span>
                <img src="https://via.placeholder.com/800x200?text=Telescopio+Espacial+ESA" alt="Telescopio espacial en órbita" class="news-image">
                <p class="news-summary">El telescopio Euclid-Next de la ESA ha identificado tres exoplanetas en la zona habitable de su estrella anfitriona, con presencia de agua líquida y atmósfera estable. Los científicos señalan que se trata de uno de los avances más relevantes en la búsqueda de vida más allá de nuestro sistema solar.</p>
                <p><strong>Puntos clave:</strong> Distancia de 40 años luz, atmósfera con oxígeno y metano, y superficie con masas similares a la Tierra.</p>
            </article>

            <!-- Noticia 2 -->
            <article class="news-card">
                <h2>Avance en biotecnología: cultivo de órganos humanos en laboratorio</h2>
                <span class="news-date">03 de enero de 2026 - Fuente: Universidad de Tokio</span>
                <img src="https://via.placeholder.com/800x200?text=Cultivo+de+Órganos" alt="Experimento de biotecnología en laboratorio" class="news-image">
                <p class="news-summary">Investigadores japoneses han logrado cultivar un riñón funcional de tamaño reducido a partir de células madre humanas. El logro abre posibilidades para reducir la dependencia de trasplantes y estudiar enfermedades renales de forma más precisa.</p>
                <p><strong>Próximos pasos:</strong> Pruebas en modelos animales durante los próximos 6 meses, con vista a pruebas clínicas en humanos en 2 años.</p>
            </article>

            <!-- Noticia 3 -->
            <article class="news-card">
                <h2>Energía solar de nueva generación alcanza eficiencia del 40%</h2>
                <span class="news-date">02 de enero de 2026 - Fuente: Centro de Investigación en Energía de Alemania</span>
                <img src="https://via.placeholder.com/800x200?text=Paneles+Solares+Nuevos" alt="Paneles solares de nueva generación" class="news-image">
                <p class="news-summary">Los paneles solares de doble capa de perovskita y silicio desarrollados en Alemania han superado el umbral del 40% de eficiencia energética, duplicando el rendimiento de los modelos convencionales. Los costos de producción se mantienen competitivos, lo que permite su implementación a gran escala.</p>
                <p><strong>Impacto:</strong> Se espera que reduzca en un 30% el costo de la energía solar en países con alta radiación.</p>
            </article>
        </section>

        <!-- Barra lateral -->
        <aside class="sidebar">
            <h3>Temas destacados</h3>
            <div class="sidebar-item">• Inteligencia artificial: Nuevos modelos que interpretan lenguaje científico</div>
            <div class="sidebar-item">• Robótica médica: Cirugías autónomas con precisión milimétrica</div>
            <div class="sidebar-item">• Cambio climático: Tecnologías para captura de carbono</div>
            <div class="sidebar-item">• Nanotecnología: Aplicaciones en medicamentos personalizados</div>

            <h3>Próximos eventos</h3>
            <div class="sidebar-item">• Congreso Mundial de Ciencia - 15-18 de febrero (París)</div>
            <div class="sidebar-item">• Feria de Tecnología Global - 5-7 de marzo (Singapur)</div>
        </aside>
    </main>

    <footer>
        <p>Ciencia & Tech Global © 2026 - Todo contenido verificado y basado en fuentes científicas reconocidas</p>
    </footer>
</body>
</html>
