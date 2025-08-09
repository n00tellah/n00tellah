<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Estela's README</title>
<style>
    body {
        font-family: 'Comic Sans MS', sans-serif;
        background-color: #fffafc;
        color: #333;
        text-align: center;
        padding: 50px;
    }
    h1 {
        font-size: 2.5rem;
        white-space: nowrap;
        overflow: hidden;
        border-right: 3px solid pink;
        width: 0;
        animation: typing 3s steps(20) forwards, blink 0.6s step-end infinite;
        margin: 0 auto;
    }
    @keyframes typing {
        from { width: 0; }
        to { width: 15ch; }
    }
    @keyframes blink {
        50% { border-color: transparent; }
    }
    .socials {
        margin-top: 20px;
    }
    .socials a {
        margin: 0 10px;
        display: inline-block;
        transition: transform 0.3s ease;
    }
    .socials a:hover {
        transform: scale(1.2);
    }
    .skills {
        margin-top: 30px;
        font-size: 1.2rem;
    }
</style>
</head>
<body>

<h1>Hi, I'm Estela 🌸</h1>

<div class="socials">
    <a href="https://facebook.com/" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" width="40">
    </a>
    <a href="https://instagram.com/" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" width="40">
    </a>
    <a href="mailto:your-email@example.com">
        <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="40">
    </a>
</div>

<div class="skills">
    🌼 Laravel | 🌼 Figma | 🌼 CSS | 🌼 HTML | 🌼 PHP
</div>

</body>
</html>
