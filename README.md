
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
        }

        main {
            padding: 20px;
        }

        button {
            padding: 10px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Simple Website</h1>
    </header>
    <main>
        <p>Welcome to my simple website! Click the button below to change the background color.</p>
        <button onclick="changeBackgroundColor()">Change Color</button>
    </main>

    <script>
        function changeBackgroundColor() {
            var body = document.body;
            var currentColor = body.style.backgroundColor;

            // If the current color is white or not set, change it to light blue; otherwise, change it to white.
            body.style.backgroundColor = (currentColor === 'white' || currentColor === '') ? '#add8e6' : 'white';
        }
    </script>
</body>
</html>
```
