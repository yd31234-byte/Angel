<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bouncing Red Ball</title>
    <style>
        body {
            margin: 0;
            background-color: white;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .ball {
            width: 50px;
            height: 50px;
            background-color: red;
            border-radius: 50%;
            position: absolute;
            animation: bounce 2s infinite ease-in-out alternate;
        }

        @keyframes bounce {
            0% {
                transform: translateY(-40vh);
            }
            100% {
                transform: translateY(40vh);
            }
        }
    </style>
</head>
<body>

    <div class="ball"></div>

</body>
</html>
