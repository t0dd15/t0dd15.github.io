<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>t0dd15 links</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            font-weight: 600;
            background-image: url(https://s2.best-wallpaper.net/wallpaper/1920x1080/2002/Blue-and-purple-abstract-background_1920x1080.jpg);
            background-repeat: no-repeat;
            background-color: black;
            background-size: cover;
            color: white;
            height: 100vh;
            background-position-x: center;
        }

        header {
            text-align: center;
            padding: 10px;
            margin-bottom: 20px;
            font-size: 2em;
        }

        .links {
            text-align: center;
            margin-top: 50px;
        }

        .home-button {
            background-color: #333;
            color: white;
            font-weight: bold;
            padding: 10px;
            font-size: 1em;
            border: 2px solid #111;
            border-radius: 5px;
            cursor: pointer;
            position: absolute;
            top: 10px;
            left: 10px;
            width: auto; /* Adjusted width */
        }

        button {
            background-color: #333;
            color: white;
            font-weight: bold;
            padding: 15px 30px;
            font-size: 1.2em;
            border: 2px solid #111;
            border-radius: 10px;
            margin: 10px 0;
            cursor: pointer;
            display: block;
            width: 80%;
            margin-left: auto;
            margin-right: auto;
        }

        @media (max-width: 600px) {
            header {
                font-size: 1.5em;
            }
        }
    </style>
</head>

<body>

    

    <header>
        <h1>Links</h1>
    </header>

    <div class="links">
        <button onclick="window.location.href='https://t.me/t0dd15'">Telegram</button>
        <button onclick="copyToClipboard('t0dd15')">Discord</button>
        <button onclick="window.location.href='https://steamcommunity.com/id/fuckfuckfuckfuckfuckfuckfucku/'">Steam</button>
    </div>

    <script>
        function copyToClipboard(text) {
            const tempInput = document.createElement('input');
            tempInput.value = text;
            document.body.appendChild(tempInput);
            tempInput.select();
            document.execCommand('copy');
            document.body.removeChild(tempInput);
            alert('Copied to clipboard: ' + text);
        }
        });
    </script>
</body>

</html>
