<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comercial Amaya</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            height: 100vh;
            background: linear-gradient(to bottom right, #a2d5f2, #1762a3);
            color: #ffffff;
        }

        /* Menú lateral */
        .sidebar {
            width: 220px;
            background-color: #003f5c;
            display: flex;
            flex-direction: column;
            padding-top: 20px;
            box-shadow: 2px 0 5px rgba(0,0,0,0.2);
        }

        .sidebar h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 1.5em;
            font-weight: bold;
        }

        .sidebar a {
            padding: 15px 20px;
            text-decoration: none;
            color: #ffffff;
            font-weight: bold;
            text-transform: uppercase;
            transition: background 0.3s, color 0.3s;
        }

        .sidebar a:hover {
            background-color: #ffa500;
            color: #003f5c;
            cursor: pointer;
        }

        /* Área de contenido */
        .main-content {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 30px;
        }

        .main-content h1 {
            font-size: 3em;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

    </style>
</head>
<body>

    <div class="sidebar">
        <h2>Comercial Amaya</h2>
        <a href="index.html">Inicio</a>
        <a href="listado_clientes.html">Listado de Clientes</a>
        <a href="gestiones.html">Gestiones</a>
        <a href="gestore_cobros.html">Gestores de Cobro</a> <!-- Enlace corregido -->
        <a href="#">Reportes</a>
        <a href="#">Información del Empleado</a>
        <a href="#">Mora</a>
    </div>

    <div class="main-content">
        <h1>¡Bienvenido a Comercial Amaya!</h1>
    </div>

</body>
</html>
