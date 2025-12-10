<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IEP Santa Clara</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        header {
            background: #0056b3;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header img {
            width: 110px;
            margin-bottom: 10px;
        }

        nav {
            background: #003f7d;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .contenido {
            padding: 20px;
            background: white;
            margin: 20px auto;
            width: 90%;
            max-width: 900px;
            border-radius: 10px;
        }

        h2 {
            border-left: 5px solid #0056b3;
            padding-left: 10px;
            color: #0056b3;
        }

        .seccion {
            margin-bottom: 25px;
        }

        footer {
            background: #003f7d;
            color: white;
            padding: 15px;
            text-align: center;
            margin-top: 30px;
        }
    </style>
</head>

<body>

    <header>
        <img src="https://i.imgur.com/jl7dD90.png" alt="Logo Santa Clara">
        <h1>Institución Educativa Privada Santa Clara</h1>
        <p>Formando estudiantes con valores y excelencia académica</p>
    </header>

    <nav>
        <a href="#historia">Historia</a>
        <a href="#niveles">Niveles Educativos</a>
        <a href="#infraestructura">Infraestructura</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="contenido">

        <!-- Historia -->
        <div class="seccion" id="historia">
            <h2>Historia</h2>
            <p>
                La Institución Educativa Privada Santa Clara fue fundada con el propósito de brindar 
                una educación de calidad, fomentando el desarrollo integral de sus estudiantes mediante 
                valores, disciplina y excelencia académica.
            </p>
        </div>

        <!-- Niveles -->
        <div class="seccion" id="niveles">
            <h2>Niveles Educativos</h2>
            <ul>
                <li>➤ Educación Inicial</li>
                <li>➤ Educación Primaria</li>
                <li>➤ Educación Secundaria</li>
            </ul>
        </div>

        <!-- Infraestructura -->
        <div class="seccion" id="infraestructura">
            <h2>Infraestructura</h2>
            <p>
                La institución cuenta con ambientes amplios, aulas iluminadas, espacios deportivos,
                salas de cómputo y zonas seguras adecuadas para el aprendizaje de los estudiantes.
            </p>
        </div>

        <!-- Contacto -->
        <div class="seccion" id="contacto">
            <h2>Contacto</h2>
            <p><strong>Dirección:</strong> Av. Principal 123, Santa Clara</p>
            <p><strong>Teléfono:</strong> (01) 555-1234</p>
            <p><strong>Correo:</strong> informes@santaclara.edu.pe</p>
        </div>

    </div>

    <footer>
        © 2025 IEP Santa Clara – Todos los derechos reservados.
    </footer>

</body>
</html>
