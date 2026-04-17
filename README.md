# tamia-dot.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Favorite Rappers</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #ffffff;
            text-align: center;
        }

        h1 {
            margin-top: 40px;
            font-size: 3em;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        .artist {
            margin-bottom: 60px;
        }

        img {
            width: 300px;
            border-radius: 12px;
            margin: 20px 0;
        }

        p {
            font-size: 1.2em;
            line-height: 1.6;
        }

        audio {
            margin-top: 15px;
        }

        button {
            background-color: #1db954;
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 1em;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 20px;
        }

        button:hover {
            background-color: #17a44b;
        }
    </style>
</head>
<body>

    <h1>My Favorite Rappers</h1>

    <div class="container">

        <!-- J. Cole -->
        <div class="artist">
            <h2>J. Cole</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/7/70/J_Cole_2018.jpg" alt="J Cole">
            <p>
                J. Cole is known for meaningful lyrics and storytelling. His music talks about life,
                struggles, and success, making him one of the most respected rappers.
            </p>

            <!-- Audio Player -->
            <audio controls>
                <source src="jcole.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>

        <!-- EBK Jaaybo -->
        <div class="artist">
            <h2>EBK Jaaybo</h2>
            <img src="https://via.placeholder.com/300x300.png?text=EBK+Jaaybo" alt="EBK Jaaybo">
            <p>
                EBK Jaaybo brings a raw, energetic style. His music reflects modern street life
                and has a strong, emotional sound.
            </p>

            <!-- Audio Player -->
            <audio controls>
                <source src="jaaybo.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>

        <button onclick="alert('Music is powerful!')">
            Click Me
        </button>

    </div>

</body>
</html>
