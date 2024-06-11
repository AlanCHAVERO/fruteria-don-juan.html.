<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frutería de Don Juan</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        nav {
            background: #333;
            color: white;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background: #575757;
        }
        section {
            padding: 20px;
        }
        h1, h2, h3, h4 {
            color: #4CAF50;
        }
        .offer, .product-description, .service, .blog-post {
            background: #f9f9f9;
            border: 1px solid #ddd;
            margin: 10px 0;
            padding: 10px;
        }
        .team-member {
            background: #f2f2f2;
            border: 1px solid #ccc;
            margin: 10px 0;
            padding: 10px;
            text-align: center;
        }
        .team-member img {
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Frutería de Don Juan</h1>
        <p>¡Las mejores frutas y verduras frescas al mejor precio!</p>
    </header>
    
    <nav>
        <a href="#frutas">Frutas</a>
        <a href="#verduras">Verduras</a>
        <a href="#ofertas">Ofertas</a>
        <a href="#promociones">Promociones</a>
        <a href="#equipo">Equipo de Trabajo</a>
        <a href="#nosotros">Sobre Nosotros</a>
        <a href="#catalogo">Catálogo</a>
        <a href="#precios">Precios</a>
        <a href="#servicios">Servicios</a>
        <a href="#blog">Blog</a>
        <a href="#contacto">Contacto</a>
        <a href="#politica">Política de Privacidad</a>
        <a href="#redes">Redes Sociales</a>
    </nav>
    
    <section id="frutas">
        <h2>Frutas</h2>
        <article class="product-description">
            <h3>Manzanas</h3>
            <p>Las manzanas de Don Juan son las más frescas y jugosas de la región. Disponemos de varias variedades incluyendo Fuji, Gala, y Granny Smith.</p>
            <img src="https://via.placeholder.com/150" alt="Manzanas 1">
            <img src="https://via.placeholder.com/150" alt="Manzanas 2">
        </article>
        <article class="product-description">
            <h3>Plátanos</h3>
            <p>Plátanos maduros y llenos de sabor. Perfectos para un snack saludable o para tus recetas de postres.</p>
            <img src="https://via.placeholder.com/150" alt="Plátanos 1">
            <img src="https://via.placeholder.com/150" alt="Plátanos 2">
        </article>
        <article class="product-description">
            <h3>Naranjas</h3>
            <p>Naranjas frescas, ideales para jugo o para comer. Proporcionan una excelente fuente de vitamina C.</p>
            <img src="https://via.placeholder.com/150" alt="Naranjas 1">
            <img src="https://via.placeholder.com/150" alt="Naranjas 2">
        </article>
        <!-- Repite para más frutas -->
    </section>
    
    <section id="verduras">
        <h2>Verduras</h2>
        <article class="product-description">
            <h3>Tomates</h3>
            <p>Tomates frescos y llenos de sabor, perfectos para ensaladas y salsas.</p>
            <img src="https://via.placeholder.com/150" alt="Tomates 1">
            <img src="https://via.placeholder.com/150" alt="Tomates 2">
        </article>
        <article class="product-description">
            <h3>Lechuga</h3>
            <p>Lechugas frescas y crujientes, ideales para tus ensaladas.</p>
            <img src="https://via.placeholder.com/150" alt="Lechuga 1">
            <img src="https://via.placeholder.com/150" alt="Lechuga 2">
        </article>
        <article class="product-description">
            <h3>Zanahorias</h3>
            <p>Zanahorias frescas, perfectas para cocinar o comer crudas.</p>
            <img src="https://via.placeholder.com/150" alt="Zanahorias 1">
            <img src="https://via.placeholder.com/150" alt="Zanahorias 2">
        </article>
        <!-- Repite para más verduras -->
    </section>
    
    <section id="ofertas">
        <h2>Ofertas</h2>
        <div class="offer">
            <h3>Oferta de la Semana: Manzanas</h3>
            <p>¡Compra 1 kg de manzanas y lleva 500g adicionales gratis!</p>
        </div>
        <div class="offer">
            <h3>Oferta Especial: Plátanos</h3>
            <p>20% de descuento en todos los plátanos. ¡Solo esta semana!</p>
        </div>
        <div class="offer">
            <h3>Descuento en Naranjas</h3>
            <p>Compra 2 kg de naranjas y obtén un 10% de descuento.</p>
        </div>
        <!-- Repite para más ofertas -->
    </section>
    
    <section id="promociones">
        <h2>Promociones</h2>
        <div class="offer">
            <h3>Promoción de Verano: Mangos</h3>
            <p>Compra 1 kg de mangos y obtén 2 jugos de mango gratis.</p>
        </div>
        <div class="offer">
            <h3>Promoción de Invierno: Naranjas</h3>
            <p>Obtén un 15% de descuento en todos los productos a base de naranja.</p>
        </div>
        <div class="offer">
            <h3>Promoción de Primavera: Pimientos</h3>
            <p>Compra 3 kg de pimientos y obtén un pimiento rojo gratis.</p>
        </div>
        <!-- Repite para más promociones -->
    </section>

    <section id="equipo">
        <h2>Equipo de Trabajo</h2>
        <div class="team-member">
            <h3>Juan Pérez</h3>
            <p>Fundador y Director</p>
            <img src="https://via.placeholder.com/150" alt="Juan Pérez">
        </div>
        <div class="team-member">
            <h3>María López</h3>
            <p>Gerente de Ventas</p>
            <img src="https://via.placeholder.com/150" alt="María López">
        </div>
        <div class="team-member">
            <h3>Carlos Gómez</h3>
            <p>Jefe de Almacén</p>
            <img src="https://via.placeholder.com/150" alt="Carlos Gómez">
        </div>
        <!-- Repite para más miembros del equipo -->
    </section>
    
    <section id="nosotros">
        <h2>Sobre Nosotros</h2>
        <p>La Frutería de Don Juan fue fundada en 1990 con la misión de proporcionar frutas y verduras frescas y de alta calidad a la comunidad local. Nuestro compromiso es ofrecer productos saludables a precios justos, siempre con una sonrisa.</p>
    </section>
    
    <section id="catalogo">
        <h2>Catálogo</h2>
        <ul>
            <li>Manzanas: Fuji, Gala, Granny Smith</li>
            <li>Plátanos: Cavendish, Rojo</li>
            <li>Naranjas: Valencia, Navel</li>
            <li>Tomates: Cherry, Roma</li>
            <li>Lechugas: Iceberg, Romana</li>
            <li>Zanahorias: Baby, Nantes</li>
            <!-- Agrega más productos -->
        </ul>
    </section>
    
    <section id="precios">
        <h2>Precios</h2>
        <table border="1">
            <tr>
                <
