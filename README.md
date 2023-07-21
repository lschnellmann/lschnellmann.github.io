# lschnellmann.github.io
<!DOCTYPE html>
<html>
    <body>
        <img src="/crimeabridgethumbnailfornewsstory.webp" alt="statue" style="width: 300"
    </body>
<head>
    <style>
        body {
            background-color: black;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 12;
            background-image: STATUEFORTMFINRWEBPAGE.png;
            background-position; center;
            background-repeat; no-repeat;
            background-size: cover;
        }
        
        .block-letters {
            color: white;
            font-size: 72px;
            font-weight: bold;
            text-align: center;
            margin-top: 100px;
        }
        
        #video-container {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            position: absolute;
            bottom: 20px;
            left: 20px;
        }
        
        .video-thumbnail {
            width: 200px;
            height: 113px;
            margin-bottom: 20px;
        }
        
        .typing-effect {
            color: lightgreen;
            font-family: Verdana, sans-serif;
            font-weight: bold;
            font-size: 18px;
            text-align: left;
            line-height: 1.5;
            margin-top: 20px;
            width: 4in;
            white-space: pre-wrap;
            overflow-wrap: break-word;
            animation: typing 4s steps(40, end);
        }
        
        @keyframes typing {
            from {
                width: 0;
            }
            to {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="block-letters">#TMFINR</div>
    <div id="video-container">
        <a href="https://www.youtube.com/embed/zXPiqk0-zDY" target="_blank">
            <img class="video-thumbnail" src="https://img.youtube.com/vi/zXPiqk0-zDY/maxresdefault.jpg" alt="Video Thumbnail 1">
        </a>
        <a href="https://www.youtube.com/embed/1MkZB2YEiy4" target="_blank">
            <img class="video-thumbnail" src="https://img.youtube.com/vi/1MkZB2YEiy4/maxresdefault.jpg" alt="Video Thumbnail 2">
        </a>
        <a href="https://www.youtube.com/embed/2lxd7odxvkQ" target="_blank">
            <img class="video-thumbnail" src="https://img.youtube.com/vi/2lxd7odxvkQ/maxresdefault.jpg" alt="Video Thumbnail 3">
        </a>
        <a href="https://www.youtube.com/embed/0cxqbDgCxNI" target="_blank">
            <img class="video-thumbnail" src="https://img.youtube.com/vi/0cxqbDgCxNI/maxresdefault.jpg" alt="Video Thumbnail 4">
        </a>
        <a href="https://www.youtube.com/embed/uRQH2CFvedY" target="_blank">
            <img class="video-thumbnail" src="https://img.youtube.com/vi/uRQH2CFvedY/maxresdefault.jpg" alt="Video Thumbnail 5">
        </a>
        <a href="https://www.euronews.com/2023/07/17/russia-blames-ukraine-for-crimea-bridge-attack" target="_blank">
            <img class="video-thumbnail" src="URL_OF_YOUR_CHOSEN_IMAGE" alt="Euronews Thumbnail">
        </a>
    </div>
    <div class="typing-effect" id="typing-effect"></div>
    
    <script>
        const text = `MeidasTouch host Ben Meiselas reports on Special Counsel Jack Smith sending a target letter to a Donald Trump employee for potential charges relating to obstruction of surveillance footage at Mar-A-Lago.`;
        const typingEffect = document.getElementById("typing-effect");
        
        let index = 0;
        const delay = 100; // Delay between each character (in milliseconds)
        
        function typeText() {
            if (index < text.length) {
                typingEffect.innerHTML += text.charAt(index);
                index++;
                setTimeout(typeText, delay);
            }
        }
        
        typeText();
    </script>
</body>
</html>
