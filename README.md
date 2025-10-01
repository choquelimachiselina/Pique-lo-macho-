<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descubre el auténtico sabor del Pique a lo Macho - La Casa del Pique</title>
    <style>
        /* Paleta de Colores Sugerida */
        :root {
            --rojo-intenso: #B22222; /* Pasión y picante */
            --amarillo-dorado: #FFD700; /* Papas fritas y energía */
            --marron-oscuro: #5C4033; /* Carne y sazón */
            --verde-locoto: #3CB371; /* Frescura */
            --blanco: #FFFFFF; /* Equilibrio y legibilidad */
            --fondo-claro: #f8f8f8;
            --texto-oscuro: #333333;
        }

        /* Estilos Generales */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--fondo-claro);
            color: var(--texto-oscuro);
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Encabezado y Título */
        .header {
            text-align: center;
            padding: 40px 20px;
            background-color: var(--rojo-intenso);
            color: var(--blanco);
            border-bottom: 8px solid var(--amarillo-dorado);
        }

        .header h1 {
            font-size: 2.8em;
            margin: 0 0 10px 0;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .header h2 {
            font-size: 1.5em;
            font-weight: 400;
            margin: 0;
            color: var(--fondo-claro);
        }

        /* Sección de Introducción y Objetivo */
        .intro {
            text-align: center;
            padding: 30px 20px;
            background-color: var(--blanco);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .intro p {
            font-size: 1.1em;
            margin-bottom: 25px;
            color: var(--marron-oscuro);
        }

        /* Botones de Acción */
        .actions {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .btn {
            display: inline-block;
            padding: 15px 30px;
            text-decoration: none;
            color: var(--blanco);
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
            box-shadow: 0 3px 6px rgba(0, 0, 0, 0.2);
        }

        .btn-ordenar {
            background-color: var(--verde-locoto);
        }

        .btn-ordenar:hover {
            background-color: #2e8b57; /* Verde más oscuro */
        }

        .btn-receta {
            background-color: var(--marron-oscuro);
        }

        .btn-receta:hover {
            background-color: #4a3429; /* Marrón más oscuro */
        }

        /* Tipos de Pique */
        .section-title {
            text-align: center;
            font-size: 2em;
            margin: 50px 0 30px 0;
            color: var(--rojo-intenso);
            text-transform: uppercase;
        }

        .pique-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .pique-card {
            background-color: var(--blanco);
            border: 2px solid var(--amarillo-dorado);
            border-radius: 8px;
            padding: 20px;
            width: calc(50% - 30px); /* Dos por fila */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
        }

        .pique-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .pique-card h3 {
            color: var(--marron-oscuro);
            border-bottom: 2px dashed var(--rojo-intenso);
            padding-bottom: 5px;
            margin-top: 0;
        }

        /* Precios */
        .precios-tabla {
            width: 100%;
            margin-top: 30px;
            border-collapse: collapse;
        }

        .precios-tabla th, .precios-tabla td {
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        .precios-tabla th {
            background-color: var(--rojo-intenso);
            color: var(--blanco);
            text-transform: uppercase;
        }

        .precios-tabla tr:nth-child(even) {
            background-color: var(--fondo-claro);
        }

        .precio-bs {
            font-weight: bold;
            color: var(--verde-locoto);
            font-size: 1.1em;
        }

        /* Testimonios */
        .testimonios {
            padding: 40px 20px;
            background-color: var(--blanco);
            margin-top: 50px;
        }

        .testimonio-card {
            margin-bottom: 15px;
            padding: 15px;
            border-left: 5px solid var(--amarillo-dorado);
            background-color: #fffaf0; /* Color cremoso */
            font-style: italic;
        }

        .stars {
            color: var(--amarillo-dorado);
            font-size: 1.2em;
        }

        /* Footer y Contacto */
        .footer {
            text-align: center;
            padding: 30px 20px;
            background-color: var(--marron-oscuro);
            color: var(--blanco);
            margin-top: 50px;
        }

        .footer p {
            margin: 5px 0;
        }

        .social-links a {
            color: var(--amarillo-dorado);
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.2em;
            transition: color 0.3s ease;
        }

        .social-links a:hover {
            color: var(--verde-locoto);
        }

        /* Responsividad básica */
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }

            .header h2 {
                font-size: 1.2em;
            }

            .pique-card {
                width: 100%; /* Una tarjeta por fila en móviles */
            }

            .actions {
                flex-direction: column;
                gap: 10px;
            }

            .btn {
                width: 80%;
                margin: 0 auto;
            }
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Descubre el auténtico sabor del Pique a lo Macho</h1>
        <h2>El plato boliviano que conquista paladares</h2>
    </div>

    <div class="container">

        <div class="intro">
            <p>El **Pique a lo Macho** no es solo una comida, es una **tradición paceña** que se comparte. En **"La Casa del Pique"** hemos perfeccionado su sabor, ofreciéndote un plato abundante, lleno de sabor único y con la verdadera sazón boliviana. ¡Ideal para compartir en un ambiente acogedor y lleno de cultura!</p>

            <div class="actions">
                <a href="#" class="btn btn-ordenar">🍴 Ordenar ahora</a>
                <a href="#" class="btn btn-receta">📥 Descargar receta</a>
            </div>
        </div>

        <div class="section-title">Mira Cómo se Prepara Nuestro Pique</div>
        <div style="text-align: center; margin-bottom: 30px;">
            <iframe 
                width="100%" 
                height="450" 
                src="https://www.youtube.com/embed/Y_Ckwty5dks" 
                title="Cómo PREPARAR PIQUE MACHO RECETA BOLIVIANA 🇧🇴 paso a paso" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen
                style="border-radius: 8px; max-width: 800px;">
            </iframe>
        </div>

        <hr style="border: 0; border-top: 1px solid #ccc;">

        <div class="section-title">Variedades que Te Harán Agua la Boca</div>

        <div class="pique-grid">
            <div class="pique-card">
                <h3>Clásico</h3>
                <p>Carne de res, salchichas, papas fritas, huevo duro, cebolla, tomate y un toque de ají. ¡La receta original!</p>
            </div>
            <div class="pique-card">
                <h3>Especial</h3>
                <p>Para los más exigentes: incluye **carne premium**, huevo frito, quesillo y el potente **locoto paceño** extra.</p>
            </div>
            <div class="pique-card">
                <h3>Mixto</h3>
                <p>La combinación perfecta de sabores: abundante porción de carne de res, pollo y salchichas.</p>
            </div>
            <div class="pique-card">
                <h3>Familiar (XL)</h3>
                <p>Una versión colosal para **4-5 personas**. ¡Abundancia garantizada para compartir en grupo!</p>
            </div>
            <div class="pique-card" style="width: calc(100% - 40px);">
                <h3>Vegetariano 🌱 (¡Una sorpresa deliciosa!)</h3>
                <p>Alternativa con proteína vegetal, champiñones, verduras frescas y el sabor picante del locoto. ¡Igual de rico!</p>
            </div>
        </div>

        <hr style="border: 0; border-top: 1px solid #ccc;">

        <div class="section-title">Precios Aproximados</div>
        <table class="precios-tabla">
            <thead>
                <tr>
                    <th>Plato</th>
                    <th>Ideal Para</th>
                    <th>Precio</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Pique Clásico</td>
                    <td>2 personas</td>
                    <td class="precio-bs">80 Bs</td>
                </tr>
                <tr>
                    <td>Pique Mixto</td>
                    <td>2-3 personas</td>
                    <td class="precio-bs">95 Bs</td>
                </tr>
                <tr>
                    <td>Pique Especial</td>
                    <td>2 personas</td>
                    <td class="precio-bs">100 Bs</td>
                </tr>
                <tr>
                    <td>Pique Familiar (XL)</td>
                    <td>4-5 personas</td>
                    <td class="precio-bs">180 Bs</td>
                </tr>
            </tbody>
        </table>

        <div class="testimonios">
            <div class="section-title" style="margin-top: 0; margin-bottom: 20px;">Lo que Dicen Nuestros Clientes</div>
            <div class="testimonio-card">
                <span class="stars">⭐⭐⭐⭐⭐</span> “Una explosión de sabores, ideal para compartir en grupo. ¡Volveremos pronto!”
            </div>
            <div class="testimonio-card">
                <span class="stars">⭐⭐⭐⭐</span> “El pique especial fue un lujo, realmente único. La carne premium hace la diferencia.”
            </div>
            <div class="testimonio-card">
                <span class="stars">⭐⭐⭐⭐⭐</span> “Nunca había probado una versión vegetariana tan rica. ¡Gran alternativa!”
            </div>
        </div>

    </div>

    <div class="footer">
        <p>🍽️ **La Casa del Pique**</p>
        <p>📍 Av. 16 de Julio, Zona Central – La Paz, Bolivia</p>
        <p>🕒 Lunes a Domingo – **12:00 a 23:00**</p>
        <hr style="border-color: #8B4513; width: 50%;">
        <div class="social-links">
            <p>Síguenos y descubre promociones exclusivas:</p>
            <a href="#" title="Facebook">Facebook</a> |
            <a href="#" title="Instagram">Instagram</a> |
            <a href="#" title="TikTok">TikTok</a> |
            <a href="#" title="YouTube">YouTube</a>
        </div>
    </div>

</body>
</html>


