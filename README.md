<html>
    <head>
        <title>My Game</title>
    </head>
    <body>
        <h1>My Game</h1>
        <p>This is my first game!</p>
 
        <script>
            //Game Logic
            let score = 0;
            let health = 100;
 
            // Player actions
            function jump() {
                score += 10;
                console.log('Jumped!');
            }
 
            function duck() {
                health += 5;
                console.log('Ducked!');
            }
 
            //Game loop
            while (health > 0) {
                jump();
                duck();
            }
 
            console.log("Game Over! Final Score: " + score);
        </script>
    </body>
</html>
