<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Nuestro Campus</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        header {
            background-color: #002147;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #003366;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background: url('https://via.placeholder.com/1500x500') no-repeat center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 40px;
            font-weight: bold;
        }

        .container {
            padding: 40px;
            text-align: center;
        }

        .description {
            font-size: 18px;
            margin-bottom: 40px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
            height: 200px;
            object-fit: cover;
        }

        footer {
            background-color: #002147;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>Nuestro Campus</h1>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Campus</a>
    <a href="#">Admisiones</a>
    <a href="#">Contacto</a>
</nav>

<div class="hero">
    Bienvenidos a Nuestro Campus
</div>

<div class="container">
    <p class="description">
        Más de 60 años en la ciudad de Cali, como pioneros en una enseñanza trilingüe: español, francés e inglés. 
        Con excelentes resultados de nuestros estudiantes ...
    </p>

    <h2>Conoce nuestras instalaciones</h2>

    <div class="gallery">
        <!-- REEMPLAZA ESTAS IMÁGENES POR LAS DE TU DRIVE -->
        <img src="https://drive.google.com/uc?export=view&id=ID_IMAGEN_1">
        <img src="https://drive.google.com/uc?export=view&id=ID_IMAGEN_2">
        <img src="https://drive.google.com/uc?export=view&id=ID_IMAGEN_3">
        <img src="https://drive.google.com/uc?export=view&id=ID_IMAGEN_4">
    </div>

    <p style="margin-top:30px;">
        Nuestro campus campestre cuenta con amplios espacios naturales, zonas deportivas, piscinas y áreas diseñadas 
        para el aprendizaje integral, promoviendo el desarrollo académico y personal de los estudiantes. :contentReference[oaicite:1]{index=1}
    </p>

</div>

<footer>
    © 2026 Nuestro Colegio - Inspirado en el modelo educativo francés
</footer>

</body>
</html>
