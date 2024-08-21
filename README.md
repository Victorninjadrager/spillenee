<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spil Hjemmeside</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #333;
        }

        .game-link {
            display: inline-block;
            margin: 20px;
            text-decoration: none;
            border-radius: 8px;
        }

        .game-link img {
            width: 200px;
            height: 200px;
            border-radius: 8px;
            transition: transform 0.2s;
        }

        .game-link img:hover {
            transform: scale(1.1);
        }
    </style>
    <script>
        function confirmAccess(url) {
            var input = prompt("Skriv 'godtspil' for at komme ind på hjemmesiden:");
            if (input === "godtspil") {
                window.location.href = url;
            } else {
                alert("Forkert kode. Prøv igen.");
            }
        }
    </script>
</head>
<body>
    <h1>Velkommen til Spil Hjemmesiden</h1>
    <p>Klik på et billede nedenfor for at spille:</p>

    <a href="javascript:void(0)" class="game-link" onclick="confirmAccess('https://fivenightsatfreddys3.com/')">
        <img src="https://via.placeholder.com/200?text=Five+Nights+at+Freddy's" alt="Five Nights at Freddy's">
    </a>

    <a href="javascript:void(0)" class="game-link" onclick="confirmAccess('https://www.y8.com/')">
        <img src="https://via.placeholder.com/200?text=Y8+Games" alt="Y8 Games">
    </a>

    <a href="javascript:void(0)" class="game-link" onclick="confirmAccess('https://www.crazygames.com/')">
        <img src="https://via.placeholder.com/200?text=Crazy+Games" alt="Crazy Games">
    </a>

    <a href="javascript:void(0)" class="game-link" onclick="confirmAccess('https://www.roblox.com/')">
        <img src="https://via.placeholder.com/200?text=Roblox" alt="Roblox">
    </a>

    <p>God fornøjelse!</p>
</body>
</html>
