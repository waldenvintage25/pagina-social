<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Walden - Rivendita Mobili</title>
    <style>
        /* Reset base */
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            height: 100%;
        }

        /* Sfondo generale e layout centrale */
        body {
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            text-align: center;
        }

        /* Intestazione semplice */
        header {
            width: 100%;
            padding: 20px 0;
            background-color: #333;
            color: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2em;
            margin: 0;
        }

        /* Logo */
        .logo {
            width: 250px;
            margin-top: 20px;
        }

        /* Sezione pulsanti */
        .buttons {
            display: flex;
            flex-direction: row;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }

        .button {
            padding: 18px 40px;
            font-size: 18px;
            text-decoration: none;
            color: #fff;
            background-color: #008CBA;
            border-radius: 8px;
            transition: background 0.3s ease;
            width: 250px;
            text-align: center;
        }

        .button:hover {
            background-color: #005f73;
        }

        /* Layout per desktop */
        @media (min-width: 768px) {
            .buttons {
                gap: 30px;
            }

            .button {
                width: 280px;
                font-size: 20px;
            }
        }

    </style>
</head>
<body>

    <!-- Intestazione semplice -->
    <header>
        <h1>Benvenuti alla Fiera Walden</h1>
    </header>

    <!-- Logo -->
    <img src="logo.webp" alt="Walden Logo" class="logo">

    <!-- Pulsanti -->
    <div class="buttons">
        <a href="URL_DEL_SITO" class="button">Visita il nostro Sito</a>
        <a href="URL_FACEBOOK" class="button">Seguici su Facebook</a>
        <a href="URL_INSTAGRAM" class="button">Seguici su Instagram</a>
    </div>

</body>
</html>
