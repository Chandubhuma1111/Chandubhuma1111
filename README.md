<!DOCTYPE html>
<html>
<head>
    <title>Dice Roller</title>
    <!-- You can link a CSS file for styling if needed -->
    <style>
        /* Add your CSS styles here */
    </style>
</head>
<body>
    <h1>Dice Roller</h1>
    <form action="roll_dice.php" method="post">
        <label for="num_dice">Number of Dice:</label>
        <input type="number" id="num_dice" name="num_dice" min="1"><br><br>

        <label for="dice_type">Type of Dice:</label>
        <select id="dice_type" name="dice_type">
            <option value="4">d4</option>
            <option value="6">d6</option>
            <option value="8">d8</option>
            <option value="10">d10</option>
            <option value="12">d12</option>
            <option value="20">d20</option>
        </select><br><br>

        <input type="submit" value="Roll">
    </form>
</body>
</html>
