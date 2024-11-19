<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Propose Your Crush</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f2c4c4;
            font-family: Arial, sans-serif;
            color: #333;
        }
        img {
            width: 150px;
            height: auto;
        }
        h1 {
            margin-top: 20px;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            margin: 10px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .yes {
            background-color: #90ee90;
        }
        .no {
            background-color: #ff6961;
        }
    </style>
</head>
<body>
    <img src="https://i.imgur.com/6xKfWwb.png" alt="Cute Cat">
    <h1>Do you love me? 😊</h1>
    <p>Chiku is all yours</p>
    <div class="buttons">
        <button class="yes" onclick="alert('Yay! I love you too! ❤️')">Yes</button>
        <button class="no" onclick="alert('Oh no! 😢')">No</button>
    </div>
</body>
</html>
