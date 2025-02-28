<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Walden - Rivendita Mobili</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: #333;
        }

        /* Intestazione */
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            width: 100%;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            font-weight: bold;
        }

        header p {
            font-size: 1.2em;
        }

        /* Logo */
        .logo {
            max-width: 180px;
            margin-top: 20px;
        }

        /* Pulsanti */
        .buttons {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 30px;
        }

        .button {
            padding: 15px 30px;
            font-size: 18px;
            text-decoration: none;
            color: #fff;
            background-color: #008CBA; /* Blu per richiamare il branding */
            border-radius: 8px;
            transition: background 0.3s ease;
            width: 250px;
            text-align: center;
        }

        .button:hover {
            background-color: #005f73; /* Blu scuro per effetto hover */
        }

        @media (max-width: 600px) {
            .logo {
                max-width: 150px;
            }
            header h1 {
                font-size: 2em;
            }
            .button {
                width: 200px;
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <!-- Intestazione -->
    <header>
        <h1>Benvenuti alla Fiera Walden</h1>
        <p>Scopri il nostro mondo di mobili unici e funzionali</p>
    </header>

    <!-- Logo -->
    <img src="logo.png" alt="Walden Logo" class="logo">

    <!-- Pulsanti per il sito e i social -->
    <div class="buttons">
        <a href="URL_DEL_SITO" class="button">Visita il nostro Sito</a>
        <a href="URL_FACEBOOK" class="button">Seguici su Facebook</a>
        <a href="URL_INSTAGRAM" class="button">Seguici su Instagram</a>
    </div>
</body>
</html>
