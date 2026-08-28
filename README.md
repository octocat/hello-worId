hello-worId
===========<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رسالة خاصة لكِ ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #ffe6e9;
            text-align: center;
            overflow-x: hidden;
        }
        #overlay {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background-color: #ff4d6d;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            font-size: 24px;
            cursor: pointer;
            z-index: 100;
            transition: opacity 0.8s ease;
        }
        .main-content {
            padding: 50px 20px;
            display: none;
        }
        .card {
            background: white;
            padding: 25px;
            margin: 20px auto;
            max-width: 400px;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .sticker { font-size: 50px; }
    </style>
</head>
<body>

    <div id="overlay" onclick="startExperience()">
        <p>✨ اضغطي هنا يا أجمل إنسانة ✨</p>
        <span style="font-size: 40px;">👇❤️</span>
    </div>

    <div class="main-content" id="content">
        <div class="sticker">🥰🌹</div>
        <h2>إلى أميرتي..</h2>
        <div class="card">
            <p>أكتب لكِ هذه الكلمات لأخبركِ كم أنتِ جميلة ومميزة في حياتي...</p>
        </div>
        <div class="sticker">💖✨💖</div>
        <div class="card">
            <p>اني احبج تبارك يروحي كل ثانية وأنتِ بقلبي وبخير دائمًا 🌸</p>
        </div>
    </div>

    <script>
        function startExperience() {
            let overlay = document.getElementById('overlay');
            let content = document.getElementById('content');
            overlay.style.opacity = '0';
            setTimeout(() => {
                overlay.style.display = 'none';
                content.style.display = 'block';
            }, 800);
        }
    </script>
</body>
</html>


My first repository on GitHub.
