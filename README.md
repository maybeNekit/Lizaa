<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Сердце</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-size: 24px;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            text-align: center;
        }
        .heart {
            height: 150px; 
            width: 150px; 
            background-color: red;
            position: relative;
            transform: rotate(-45deg);
            margin-bottom: 20px; 
        }
        .heart::before, 
        .heart::after {
            content: "";
            height: 150px; 
            width: 150px; 
            background-color: red;
            border-radius: 50%;
            position: absolute;
        }
        .heart::before {
            top: -75px; 
            left: 0;
        }
        .heart::after {
            left: 75px; 
            top: 0;
        }
    </style>
</head>
<body>
    <div>
        <div class="heart"></div>
        <h1>Сердце</h1>
        <p>Это символ любви и привязанности.</p>
    </div>
</body>
</html>
