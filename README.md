<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorpresa de Cumpleaños</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        #message {
            font-size: 24px;
            color: #333;
            text-align: center;
            display: none;
        }
        .button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <button class="button" onclick="showMessage()">Haz click para ver tu sorpresa</button>
    <div id="message">🎉 ¡Feliz cumpleaños, Maira! 🎉<br>Que este año esté lleno de salud, sonrisas y éxitos, como los que brindas cada día en tu labor como enfermera.</div>

    <script>
        function showMessage() {
            document.querySelector('.button').style.display = 'none';
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
