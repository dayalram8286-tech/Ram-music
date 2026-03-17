# Ram-music
Please support<!DOCTYPE html>
<html>
<head>
    <title>Ram Music</title>
    <style>
        body {
            background-color: black;
            color: white;
            text-align: center;
            font-family: Arial;
        }
        .song {
            border: 1px solid white;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
        }
        button {
            padding: 10px 20px;
            background: red;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<h1>🎵 Ram Music 🎵</h1>

<div class="song">
    <h3>Song 1</h3>
    <audio id="song1" src="song1.mp3"></audio>
    <button onclick="playSong('song1')">Play</button>
</div>

<div class="song">
    <h3>Song 2</h3>
    <audio id="song2" src="song2.mp3"></audio>
    <button onclick="playSong('song2')">Play</button>
</div>

<script>
function playSong(id) {
    var song = document.getElementById(id);
    song.play();
}
</script>

</body>
</html>
