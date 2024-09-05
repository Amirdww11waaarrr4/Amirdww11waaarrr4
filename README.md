<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colorful Cherry Website</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive;
            background: linear-gradient(45deg, #FFB3BA, #FFDFBA, #FFFFBA, #BAFFC9, #BAE1FF);
            color: #8B0000;
            text-align: center;
            animation: gradientBG 15s ease infinite;
            background-size: 400% 400%;
        }
        @keyframes gradientBG {
            0% {background-position: 0% 50%;}
            50% {background-position: 100% 50%;}
            100% {background-position: 0% 50%;}
        }
        h1 {
            color: #FF0000;
            text-shadow: 2px 2px 4px #000000;
            animation: bounce 2s ease infinite;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {transform: translateY(0);}
            40% {transform: translateY(-30px);}
            60% {transform: translateY(-15px);}
        }
        .cherry {
            font-size: 100px;
            animation: rotate 3s linear infinite;
        }
        @keyframes rotate {
            0% {transform: rotate(0deg);}
            100% {transform: rotate(360deg);}
        }
        .rainbow-text {
            background-image: linear-gradient(to left, violet, indigo, blue, green, yellow, orange, red);
            -webkit-background-clip: text;
            color: transparent;
            font-size: 24px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Welcome to the Colorful Cherry Website!</h1>
    <p class="rainbow-text">Enjoy our delicious cherries!</p>
    <div class="cherry">🍒</div>
</body>
</html>
