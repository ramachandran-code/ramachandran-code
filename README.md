<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Egg Boiling</title>
    <style>
        body {
            background-color: #ffffff;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 90px;
            background-color: #c4f4f0;
            box-shadow: 5px 5px 2px 2px rgb(192, 228, 239);
            border-radius: 20px;
        }
        h1 {
            text-align: center;
            font-family: 'Courier New', Courier, monospace;
            color: #333;
        }
        .options {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .option {
            padding: 10px 20px;
            border: none;
            border-radius: 20px;
            font-family: 'Courier New', Courier, monospace;
            font-weight: bold;
            background-color: #d2e2f6;
            box-shadow: 5px 5px 2px 2px rgb(192, 228, 239);
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s;
        }
        .option:hover {
            background-color: #a2acf3;
            color: white;
        }
        .info {
            margin-top: 30px;
            padding: 15px;
            background-color: #a4ecec;
            border: 1px solid #b1dcdf;
            box-shadow: 5px 5px 2px 2px rgb(192, 228, 239);
            border-radius: 40px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Egg Boiling Options</h1>
    <div class="options">
        <div class="option" onclick="redirectToSoftBoil()">Soft Boil</div>
        <div class="option" onclick="redirectToHardBoil()">Hard Boil</div>
        <div class="option" onclick="redirectToFriedEgg()">Fried Egg</div>
    </div>

    <div class="info" id="eggInfo">
        <p>Select an option to learn more.</p>
    </div>
</div>

<script>
    function redirectToSoftBoil() {
        // Redirect to soft_boiled.html page
        window.location.href = "soft_boiled.html";
    }

    // Placeholder functions for Hard Boil and Fried Egg (you can change these similarly)
    function redirectToHardBoil() {
        window.location.href = "hard_boiled.html";
    }

    function redirectToFriedEgg() {
        window.location.href = "fried_egg.html";
    }
    
</script>

</body>
</html>

