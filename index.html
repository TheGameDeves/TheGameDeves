<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Top Down Game Player</title>
<style>
    body {
        margin: 0;
        padding: 0;
        overflow: hidden;
    }
    canvas {
        display: block;
    }
</style>
</head>
<body>

<canvas id="gameCanvas"></canvas>

<script>
    // Initialize canvas
    const canvas = document.getElementById('gameCanvas');
    const ctx = canvas.getContext('2d');
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
    
    // Player object
    const player = {
        x: canvas.width / 2,
        y: canvas.height / 2,
        width: 50,
        height: 50,
        speed: 5
    };
    
    // Draw player
    function drawPlayer() {
        ctx.fillStyle = 'blue';
        ctx.fillRect(player.x - player.width / 2, player.y - player.height / 2, player.width, player.height);
    }
    
    // Update player position
    function update() {
        if (keys.ArrowUp && player.y > 0) {
            player.y -= player.speed;
        }
        if (keys.ArrowDown && player.y < canvas.height) {
            player.y += player.speed;
        }
        if (keys.ArrowLeft && player.x > 0) {
            player.x -= player.speed;
        }
        if (keys.ArrowRight && player.x < canvas.width) {
            player.x += player.speed;
        }
    }
    
    // Game loop
    function gameLoop() {
        ctx.clearRect(0, 0, canvas.width, canvas.height);
        update();
        drawPlayer();
        requestAnimationFrame(gameLoop);
    }
    
    // Keyboard input
    const keys = {};
    window.addEventListener('keydown', e => {
        keys[e.code] = true;
    });
    window.addEventListener('keyup', e => {
        keys[e.code] = false;
    });
    
    // Start game
    gameLoop();
</script>

</body>
</html>
