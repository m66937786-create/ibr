<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Site</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(45deg, #000000, #000033, #000066, #000033);
            background-size: 400% 400%;
            animation: gradientShift 5s ease infinite;
            font-family: Arial, sans-serif;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .message {
            width: 5cm; /* Примерно 5 см ширины */
            height: 5cm; /* Примерно 5 см высоты */
            background-color: #000000;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            font-size: 14px; /* Маленький шрифт для вместимости */
            padding: 10px;
            box-sizing: border-box;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body>
    <div class="message">
        EROR ☢<br>
        PROFILE IBR<br>
        Hello, my friend, I'm into coding, and I love it. I recommend that you start too.
    </div>
</body>
</html>
