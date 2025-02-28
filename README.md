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

        /* Logo */
        .logo {
            margin-top: -40px;
            width: 250px;
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
