<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Regalo para Fiorella</title>
    <style>
        body {
            font-family: Helvetica, sans-serif;
            background-color: #fff;
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
        }

        button {
            padding: 10px 20px;
            background-color: #ff69b4;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        img {
            max-width: 100%;
            height: auto;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <p>Se que es tarde para entregarte flores amarillas pero el día no importa, así que estas son para ti</p>
        <button onclick="showFlowers()">Abrir regalo</button>
        <div id="flowers" style="display:none;">
            <img src="yellow_flowers.jpg" alt="Ramo de flores amarillas">
        </div>
        <p>Hola preciosa,</p>
        <p>Quería recordarte lo mucho que te quiero y lo especial que eres para mí. Aunque estemos separados por la distancia, nuestro cariño es más fuerte que nunca.</p>
        <p>Te extraño cada día y no puedo esperar a estar juntos nuevamente.</p>
        <p>Espera, no te vayas. para ti </p>
        <button onclick="showKiss()">Da clic </button>
        <div id="kiss" style="display:none;">
            <img src="kiss.jpg" alt="un beso">
        </div>
    </div>

    <script>
        function showFlowers() {
            document.getElementById("flowers").style.display = "block";
        }

        function showKiss() {
            document.getElementById("kiss").style.display = "block";
        }
    </script>
</body>
</html>
