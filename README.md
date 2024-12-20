- <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Divertida</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4);
            text-align: center;
            color: #333;
        }
        header {
            background: #ff6f61;
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        h1 {
            font-size: 3em;
            margin: 0;
        }
        main {
            padding: 20px;
        }
        .color-button {
            font-size: 1.5em;
            padding: 10px 20px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            background-color: #ffcc00;
            color: #333;
            transition: transform 0.3s;
        }
        .color-button:hover {
            transform: scale(1.2);
            background-color: #ffeb3b;
        }
        .surprise {
            font-size: 2em;
            margin-top: 20px;
            display: none;
            animation: pop 0.5s ease-in-out;
        }
        footer {
            margin-top: 40px;
            padding: 10px;
            background-color: #ff6f61;
            color: white;
        }
        @keyframes pop {
            0% { transform: scale(0); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <header>
        <h1>🌈 Página Divertida 🌟</h1>
    </header>
    <main>
        <p>Bem-vindo à página mais divertida da internet!</p>
        <p>Clique no botão abaixo para uma surpresa colorida 🎉:</p>
        <button class="color-button" onclick="showSurprise()">Clique aqui!</button>
        <div class="surprise" id="surprise">🎉 Surpresa! Você é incrível! 🎈</div>
    </main>
    <footer>
        <p>Feito com ❤️ por um programador animado!</p>
    </footer>

    <script>
        function showSurprise() {
            const surprise = document.getElementById('surprise');
            surprise.style.display = 'block';
        }
    </script>
</body>
</html>
