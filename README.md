<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Valentine's Day Greeting</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <div class="container">
            <div class="initial-screen" id="initialScreen">
                <h1>Happy Valentine's Day!</h1>
                <p>Enter your name to see a special surprise</p>
                <input type="text" id="nameInput" placeholder="Your Name" required>
                <button id="submitBtn">Submit</button>
            </div>
            <div class="heart-container">
                <div class="heart" id="heart"></div>
                <h1 id="greeting">I Love You! Happy Valentine's Day!</h1>
            </div>
        </div>
        <script src="script.js"></script>
    </body>
    </html>
