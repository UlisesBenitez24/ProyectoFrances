# ProyectoFrances
Actividad

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sitio de Skincare</title>
    <meta name="description" content="Encuentra los mejores productos para el cuidado de tu piel. Rutinas personalizadas, ingredientes naturales y consejos de expertos.">
    <meta name="keywords" content="skincare, cuidado de la piel, productos naturales, rutina facial, belleza, salud">
    <link rel="canonical" href="https://www.tusitiodeskincare.com/">
    <meta name="robots" content="index, follow">
    <meta property="og:title" content="Tu Sitio de Skincare">
    <meta property="og:description" content="Descubre productos y rutinas para una piel radiante.">
    <meta property="og:image" content="https://www.tusitiodeskincare.com/images/logo.jpg">
    <meta property="og:url" content="https://www.tusitiodeskincare.com/">
    <meta property="og:type" content="website">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Tu Sitio de Skincare">
    <meta name="twitter:description" content="Productos y consejos para el cuidado de la piel.">
    <meta name="twitter:image" content="https://d1csarkz8obe9u.cloudfront.net/posterpreviews/skincare-%26-hair-free-logo-design-template-7570ef196bb39d2f49a2ac9bf7900df2_screen.jpg?ts=1710345189">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
    <link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
    <meta name="msapplication-TileColor" content="#da532c">
    <meta name="theme-color" content="#ffffff">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/eb496ab1d3.js" crossorigin="anonymous"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.7;
        }
        header {
            background-color: #fff;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .logo img {
            height: 50px;
        }
        .logo h1 {
            margin: 0;
            font-size: 1.5rem;
            color: #007bff;
        }
        .nav-menu {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        .nav-menu li {
            margin-left: 1.5rem;
        }
        .nav-menu li a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        .nav-menu li a:hover {
            color: #007bff;
        }
        .burger {
            display: none;
            font-size: 1.5rem;
            color: #333;
            cursor: pointer;
        }
        .hero-section {
            background-color: #f8f9fa;
            padding: 4rem 0;
            text-align: center;
        }
        .hero-section h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #2c3e50;
        }
        .hero-section p {
            font-size: 1.1rem;
            margin-bottom: 2rem;
            color: #666;
        }
        .cta-button {
            background-color: #007bff;
            color: #fff;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: 600;
            transition: background-color 0.3s ease;
        }
        .cta-button:hover {
            background-color: #0056b3;
        }
        .products-section {
            padding: 4rem 0;
            text-align: center;
        }
        .products-section h2 {
            font-size: 2rem;
            margin-bottom: 2rem;
            color: #2c3e50;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        .product-card {
            background-color: #fff;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
            text-align: center;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-card img {
            width: 100%;
            border-radius: 5px;
            margin-bottom: 1rem;
        }
        .product-card h3 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: #34495e;
        }
        .product-card p {
            font-size: 1rem;
            margin-bottom: 1rem;
            color: #666;
        }
         .product-card .price {
            font-size: 1.5rem;
            font-weight: bold;
            color: #007bff;
            margin-bottom: 1rem;
        }
        .add-to-cart {
            background-color: #007bff;
            color: #fff;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: 600;
            transition: background-color 0.3s ease;
            cursor: pointer;
            border: none;
            font-size: 1rem;
        }
        .add-to-cart:hover {
            background-color: #0056b3;
        }

        .cart-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }

        .cart-content {
            background-color: #fff;
            padding: 2rem;
            border-radius: 5px;
            width: 90%;
            max-width: 600px;
            overflow-y: auto;
            max-height: 80vh;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .cart-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.5rem;
            border-bottom: 1px solid #ddd;
            padding-bottom: 1rem;
        }

        .cart-header h2 {
            margin: 0;
            font-size: 1.5rem;
            color: #34495e;
        }

        .close-cart {
            font-size: 1.5rem;
            color: #666;
            cursor: pointer;
            border: none;
            background: none;
        }

        .cart-items {
            margin-bottom: 1.5rem;
        }

        .cart-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid #eee;
        }

        .cart-item img {
            width: 80px;
            border-radius: 5px;
        }

        .cart-item-details {
            flex: 1;
            margin-left: 1rem;
        }

        .cart-item-details h3 {
            margin: 0 0 0.5rem;
            font-size: 1rem;
            color: #34495e;
        }

        .cart-item-details p {
            margin: 0;
            font-size: 0.9rem;
            color: #666;
        }
        .cart-item-quantity {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .quantity-btn {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 0.25rem 0.5rem;
            cursor: pointer;
            font-size: 1rem;
            transition: background-color 0.3s ease;
            background-color: #f4f4f4;
            color: #333;
        }

        .quantity-btn:hover {
            background-color: #007bff;
            color: #fff;
            border-color: #007bff;
        }

        .cart-total {
            font-size: 1.2rem;
            font-weight: bold;
            color: #34495e;
            margin-bottom: 1rem;
            text-align: right;
        }

        .checkout-btn {
            background-color: #28a745;
            color: #fff;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: 600;
            transition: background-color 0.3s ease;
            width: 100%;
            text-align: center;
            border: none;
            font-size: 1rem;
        }

        .checkout-btn:hover {
            background-color: #218838;
        }
       .remove-item {
            background: none;
            border: none;
            font-size: 1rem;
            color: #e74c3c;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .remove-item:hover {
            color: #c0392b;
        }

        .contact-section {
            padding: 4rem 0;
            text-align: center;
            background-color: #f8f9fa;
        }

        .contact-section h2 {
            font-size: 2rem;
            margin-bottom: 2rem;
            color: #2c3e50;
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: #34495e;
            font-size: 1rem;
        }

        .form-control {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
            transition: border-color 0.3s ease;
        }

        .form-control:focus {
            outline: none;
            border-color: #007bff;
            box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.1);
        }

        textarea.form-control {
            height: 150px;
            resize: vertical;
        }

        .submit-btn {
            background-color: #007bff;
            color: #fff;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 5px;
            font-weight: 600;
            transition: background-color 0.3s ease;
            font-size: 1rem;
            cursor: pointer;
            width: 100%;
        }

        .submit-btn:hover {
            background-color: #0056b3;
        }
        .footer {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
            font-size: 0.9rem;
        }

        .footer p {
            margin: 0;
        }

        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                align-items: flex-start;
            }
            .nav-menu {
                display: none;
                flex-direction: column;
                width: 100%;
                margin-top: 1rem;
            }
            .nav-menu li {
                margin-left: 0;
                margin-bottom: 1rem;
            }
            .nav-menu.active {
                display: flex;
            }
            .burger {
                display: block;
            }
             .hero-section h2 {
                font-size: 2rem;
            }
            .hero-section p {
                font-size: 1rem;
            }
            .product-grid {
                grid-template-columns: 1fr;
            }
             .cart-content {
                width: 95%;
                margin: 1rem auto;
            }
        }
        @media (max-width: 480px){
            .logo h1{
                font-size: 1.2rem;
            }
            .cart-item {
                flex-direction: column;
                align-items: flex-start;
            }
            .cart-item img{
                margin-bottom: 1rem;
            }
            .cart-item-details{
                margin-left: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav class="navbar">
                <div class="logo">
                    <img src="https://d1csarkz8obe9u.cloudfront.net/posterpreviews/skincare-%26-hair-free-logo-design-template-7570ef196bb39d2f49a2ac9bf7900df2_screen.jpg?ts=1710345189" alt="Logo de Skincare">
                    <h1>Tu Skincare</h1>
                </div>
                <ul class="nav-menu">
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#productos">Productos</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                    <li><a href="#" id="cart-icon"><i class="fas fa-shopping-cart"></i> Carrito</a></li>
                </ul>
                <div class="burger">
                    <i class="fas fa-bars"></i>
                </div>
            </nav>
        </div>
    </header>

    <main>
        <section id="inicio" class="hero-section">
            <div class="container">
                <h2>El mejor cuidado para tu piel</h2>
                <p>Descubre nuestra selección de productos de alta calidad, diseñados para resaltar tu belleza natural.</p>
                <a href="#productos" class="cta-button">Ver Productos</a>
            </div>
        </section>

        <section id="productos" class="products-section">
            <div class="container">
                <h2>Nuestros Productos</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <img src="https://d3gr7hv60ouvr1.cloudfront.net/CACHE/images/products/b1dcb10314d14fd79cac166bbe5d9721/0b0a45c60f5693bd26fc335fbba098e7.jpg" alt="Serum Facial">
                        <h3>Serum Facial Hidratante</h3>
                        <p>Un serum ligero que hidrata profundamente y revitaliza la piel.</p>
                        <p class="price">$25.00</p>
                        <button class="add-to-cart" data-product='{"id":1, "nombre":"Serum Facial Hidratante", "precio":25, "imagen":"https://d3gr7hv60ouvr1.cloudfront.net/CACHE/images/products/b1dcb10314d14fd79cac166bbe5d9721/0b0a45c60f5693bd26fc335fbba098e7.jpg"}'>Añadir al carrito</button>
                    </div>
                    <div class="product-card">
                        <img src="https://m.media-amazon.com/images/I/51BNRbd4o3S.jpg" alt="Crema Hidratante">
                        <h3>Crema Hidratante Diaria</h3>
                        <p>Crema de uso diario que protege y nutre la piel, dejándola suave y radiante.</p>
                        <p class="price">$20.00</p>
                        <button class="add-to-cart" data-product='{"id":2, "nombre":"Crema Hidratante Diaria", "precio":20, "imagen":"https://m.media-amazon.com/images/I/51BNRbd4o3S.jpg"}'>Añadir al carrito</button>
                    </div>
                    <div class="product-card">
                        <img src="https://production.na01.natura.com/on/demandware.static/-/Sites-nat-mex-b2b2c-catalog/default/dw9d624295/85003_2.jpg" alt="Mascarilla Facial">
                        <h3>Mascarilla Facial Exfoliante</h3>
                        <p>Mascarilla que elimina impurezas y células muertas, dejando la piel renovada.</p>
                         <p class="price">$18.00</p>
                        <button class="add-to-cart" data-product='{"id":3, "nombre":"Mascarilla Facial Exfoliante", "precio":18, "imagen":"https://production.na01.natura.com/on/demandware.static/-/Sites-nat-mex-b2b2c-catalog/default/dw9d624295/85003_2.jpg"}'>Añadir al carrito</button>
                    </div>
                     <div class="product-card">
                        <img src="https://shinyhushh.com/cdn/shop/files/Photoroom-20240629-193553.png?v=1719711971&width=1445" alt="Tónico Facial">
                        <h3>Tónico Facial Equilibrante</h3>
                        <p>Tónico que equilibra el pH de la piel y la prepara para los siguientes pasos de la rutina.</p>
                        <p class="price">$15.00</p>
                        <button class="add-to-cart" data-product='{"id":4, "nombre":"Tónico Facial Equilibrante", "precio":15, "imagen":"https://shinyhushh.com/cdn/shop/files/Photoroom-20240629-193553.png?v=1719711971&width=1445"}'>Añadir al carrito</button>
                    </div>
                </div>
            </div>
        </section>

        <section id="contacto" class="contact-section">
