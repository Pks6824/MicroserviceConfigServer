# Simple web project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            width: 100%;
            text-align: center;
        }

        main {
            text-align: center;
            margin-top: 20px;
        }

        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 10px 2px;
            cursor: pointer;
            border-radius: 4px;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple HTML Project</h1>
    </header>
    <main>
        <p>This is a simple HTML project with CSS and JavaScript.</p>
        <button id="myButton">Click Me!</button>
    </main>
    <script>
        document.getElementById('myButton').addEventListener('click', function() {
            alert('Button clicked!');
        });
    </script>
</body>
</html>

