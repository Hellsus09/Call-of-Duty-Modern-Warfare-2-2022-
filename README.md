<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Theme: MW2</title>
    <link rel="icon" href="https://example.com/mw2-icon.png"> <!-- Замени на URL иконки MW2 -->
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('https://example.com/mw2-wallpaper.jpg') no-repeat center center fixed; /* Замени URL на ссылку на изображение MW2 */
            background-size: cover;
            color: #ffffff;
        }

        .header {
            background: rgba(0, 0, 0, 0.7);
            padding: 10px;
            text-align: center;
            font-size: 24px;
            border-bottom: 2px solid #00ff00;
        }

        .content {
            padding: 20px;
            text-align: center;
        }

        .button {
            background-color: #00ff00;
            border: none;
            color: black;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            margin: 10px;
            border-radius: 5px;
        }

        .button:hover {
            background-color: #008000;
        }

        footer {
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
            background: rgba(0, 0, 0, 0.7);
            color: #00ff00;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <audio id="background-music" loop autoplay>
        <source src="https://example.com/mw2-music.mp3" type="audio/mpeg"> <!-- Замени URL на музыку MW2 -->
        Your browser does not support the audio element.
    </audio>

    <div class="header">GitHub Theme: Call of Duty MW2</div>
    
    <div class="content">
        <h1>Welcome to MW2 Theme</h1>
        <p>Experience the style of Call of Duty: Modern Warfare 2 in your GitHub application.</p>
        <button class="button" onclick="playSound('click-sound')">Customize Theme</button>
    </div>

    <footer>
        &copy; 2025 Call of Duty MW2 Theme for GitHub. All Rights Reserved.
    </footer>

    <audio id="click-sound">
        <source src="https://example.com/mw2-click-sound.mp3" type="audio/mpeg"> <!-- Замени URL на звук клика -->
        Your browser does not support the audio element.
    </audio>

    <script>
        // Воспроизведение звука при нажатии кнопки
        function playSound(soundId) {
            const sound = document.getElementById(soundId);
            if (sound) {
                sound.currentTime = 0;
                sound.play();
            }
        }

        // Кастомная анимация запуска приложения
        window.onload = function () {
            alert('Welcome to the MW2 Themed GitHub App!');
        };
    </script>
</body>
</html>
