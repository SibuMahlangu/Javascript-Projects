<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    
    <title>To-Do List App JS</title>
</head>
<body>
    <div class="container">
        <div class="todo-app">
            <h2>To-Do List <img src="images/icon.png"></h2>
            <div class="row">
                <input type="text" id="input-box" placeholder="Add your text">
                <button onclick="addTask()">Add</button>
            </div>
            <ul id="list-container">
                <!-- <li class="checked">Task 1</li>
                <li>Task 2</li>
                <li>Task 3</li> -->
            </ul>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
