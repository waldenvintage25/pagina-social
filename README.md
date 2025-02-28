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

        /* Intestazione */
        header {
            background-color: #333;
            color: #fff;
            width: 100%;
            padding: 40px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 40px;
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            font-weight: bold;
        }

        header p {
            font-size: 1.5em;
            margin-top: 0;
        }

        /* Logo */
        .logo {
            width: 250px;
            margin-bottom: 20px;
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
        @m
