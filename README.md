
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
            overflow-x: hidden;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        #content {
            position: absolute;
            top:  50px;
            left: 0px;
            right:0px;
            transform: translate(0, 0);
            text-align:center;
        }

        h1 {
            font-size: 60px;
            font-weight: bold;
            animation: neon 4s linear infinite alternate;
        }
        p {
            font-size: 20px;
  
        }
        p2 {
            font-size: 20px;
  
        }

        @keyframes neon {
            0% {
                text-shadow: 0 0 10px #00f, 0 0 20px #00f, 0 0 30px #00f;
            }
            25% {
                text-shadow: 0 0 10px #CCFF99, 0 0 20px #00f, 0 0 30px #CCFF99;
            }
            50% {
                text-shadow: 0 0 10px #FFD700, 0 0 20px #FFD700, 0 0 30px #FFD700;
            }
            75% {
                text-shadow: 0 0 10px #FF9966, 0 0 20px #FFD700, 0 0 30px #FF9966;
            }
            100% {
                text-shadow: 0 0 10px #f00, 0 0 20px #f00, 0 0 30px #f00;
            }
        }

        .hidden {
            opacity: 0;
            transition: opacity 0.5s;
        }

        .notes {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -2;
            font-size: 25px;
        }

        .note {
            position: absolute;
            animation: move-notes 10s linear infinite;
        }

        .note:nth-child(odd) {
            animation-duration: 12s;
            opacity: 0.7;
        }

        .note:nth-child(1) {
            color: #FF33CC;
        }

        .note:nth-child(2) {
            color: #00FFFF;
        }

        .note:nth-child(3) {
            color: #FFD700;
        }

        .note:nth-child(4) {
            color: #f4b887;
            
        }

        .note:nth-child(5) {
            color: #9400D3;
        }

        @keyframes move-notes {
            0% {
                transform: translateX(10);
            }
            100% {
                transform: translateX(100vw);
            }
        }

        .social-media {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
        }

        .social-media a {
            font-size: 36px;
            margin: 0 20px;
            color: #FFD700;
        }

        }

        .video-container {
            position: relative;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            width: 80%;
            max-width: 800px;
            margin: 20px auto;
        }

        .video {
            position: absolute;
            width: 300px;
            box-sizing: border-box;
            overflow: hidden;
            margin-bottom: 0px;
            border: 2px solid #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .video iframe {
            width: 100%;
            display: block;
            border-radius: 8px;
        }

        .video1 {
            top: 350px;
            left: 20px;
        }

        .video2 {
            top: 550px;
            left: 20px;
        }

        .video3 {
            top: 750px;
            left: 20px;
        }

        .video4 {
            top: 350px;
            right: 20px;
        }

        .video5 {
            top: 550px;
            right: 20px;
        }

        .video6 {
            top: 750px;
            right: 20px;
        }
        #featured-content,
        #events {
            width: 400px;
            height:80px;
            margin-top: 163px; 
        }

        .featured-video.video1 {
    width: 80%; /* También puedes ajustar el ancho si es necesario */
    height:150px;
    box-sizing: border-box;
    padding: 2px;
    border: 2px solid #fff;
    border-radius: 30px;
    overflow: hidden;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    margin-bottom: 10px;
}
        .featured-video iframe {
            width: 100%;
            height: 162px;
        }
    </style>
</head>

<body>
    <div id="content">
        <h1 class="text-line"><font color="#FFD700">Welcome to YMusicT</font></h1>
        <p class="text-line"><font color="#fff">I can't be the pencil that write your lyrycs, But let me be your rubber to clean  your fails. </font></p>
<p2 class="text-line"><font color="#fff">
The cat really was in love with the miusic, he trade his seven lifes to have one with her. </font></p2>
        <p class="text-line">This is my channel <a href="https://www.youtube.com/@ymusict1041">YmusicT</a></p>
    </div>

    <div class="notes">
        <!-- Notas generadas dinámicamente by JavaScript -->
    </div>

    <div class="social-media">
        <a href="tu-enlace-de-Facebook" target="_blank">
            <i class="fab fa-facebook"></i>
        </a>
        <a href="tiktok.com/@ymusict?_t=8gjUbSZa1on&_r=1" target="_blank">
            <i class="fab fa-tiktok"></i>
        </a>
        <a href="tu-enlace-de-Twitter" target="_blank">
            <i class="fab fa-twitter"></i>
        </a>
        <a href="tu-enlace-de-Instagram" target="_blank">
            <i class="fab fa-instagram"></i>
        </a>
    </div>

    <div class="video-container">
        <div class="video video1">
            <iframe src="https://www.youtube.com/embed/6-5VLM8GVYc" frameborder="0" allowfullscreen></iframe>
        </div>

        <div class="video video2">
            <iframe src="https://www.youtube.com/embed/e3v4ar6UqhU" frameborder="0" allowfullscreen></iframe>
        </div>

        <div class="video video3">
            <iframe src="https://www.youtube.com/embed/iCmTNzWcvYQ" frameborder="0" allowfullscreen></iframe>
        </div>

        <div class="video video4">
            <iframe src="https://www.youtube.com/embed/xFqPQlhLD04" frameborder="0" allowfullscreen></iframe>
        </div>

        <div class="video video5">
            <iframe src="https://www.youtube.com/embed/Pc_Bl6wQcBQ" frameborder="0" allowfullscreen></iframe>
        </div>

        <div class="video video6">
            <iframe src="https://www.youtube.com/embed/tj4LnX2hw08" frameborder="0" allowfullscreen></iframe>
        </div>
        <!-- Nueva sección: Featured Content -->
    <div id="featured-content">
        <h2>Contenido Destacado</h2>

        <div class="featured-video video1">
            <iframe src="https://www.youtube.com/embed/BkhQrsuZYLM" frameborder="0" allowfullscreen></iframe>
        </div>
    </div>
    <!-- Nueva sección: Events -->
    <div id="events">
        <h2>Próximos Eventos</h2>

        <div class="event">
            <h3 data-translate="Live Concert">Proximo video</h3>
            <p data-translate="Don't miss our upcoming live concert! Enjoy live music and connect with us."></p>
            <p data-translate="Date: DD/MM/YYYY">Fecha: 7/12/2023</p>
        </div>
    </div>

    <script>
        var notesContainer = document.querySelector('.notes');

        function generateRandomNotes() {
            const noteSymbols = ['♪', '♫', '♩', '♪', '♬', '♭', '♮', '♯'];

            for (let i = 0; i < 200; i++) {
                const note = document.createElement('div');
                note.classList.add('note');
                note.innerText = noteSymbols[Math.floor(Math.random() * noteSymbols.length)];
                note.style.top = Math.random() * 100 + 'vh';
                note.style.left = Math.random() * 100 + 'vw';
                note.style.animationDuration = Math.random() * 10 + 5 + 's';
                note.style.color = getRandomColor();
                note.style.textShadow = '1px 1px 2px rgba(0, 0, 0, 0.5)';
                note.style.transform = 'scale(' + (Math.random() + 0.5) + ')';
                notesContainer.appendChild(note);
            }
        }

        function getRandomColor() {
            return '#' + (Math.random().toString(16) + '000000').slice(2, 8);
        }

        generateRandomNotes();
    </script>
</body>
</html>
