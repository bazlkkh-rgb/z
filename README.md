<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Валентинка</title>
<style>
body {
    margin: 0;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(135deg, #ffd6e7, #ffeef5);
    font-family: "Segoe UI", sans-serif;
}

.card {
    background: white;
    padding: 35px;
    border-radius: 25px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.12);
    text-align: center;
    max-width: 420px;
}

h1 { color: #ff4d8d; }

.code {
    margin-top: 15px;
    background: #f7f7f7;
    padding: 12px;
    border-radius: 10px;
    font-family: monospace;
}

button {
    margin-top: 10px;
    padding: 12px 20px;
    border: none;
    border-radius: 12px;
    background: #ff4d8d;
    color: white;
    font-size: 15px;
    cursor: pointer;
}

.sticker {
    display: none;
    margin-top: 15px;
}

.sticker img {
    width: 200px;
}
</style>
</head>
<body>

<div class="card">
    <div style="font-size:55px;">🧸💗</div>
    <h1>С Днём Валентина!</h1>
    <p>Ты мой любимый человек среди друзей 💞</p>

    <div class="code">
friends.add(you); <br>
happiness++; <br>
status = "lucky";
    </div>

    <button onclick="showSticker1()">Показать стикер 😏</button>
    <button onclick="showSticker2()">Ещё смешнее 😂</button>

    <div class="sticker" id="gif1">
        <img src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif" width="220">
    </div>

    <div class="sticker" id="gif2">
        <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="220">
    </div>

    <p style="margin-top:20px;">
        Люблю и ценю 💕
    </p>
</div>

<script>
function showSticker1() {
    document.getElementById("gif1").style.display = "block";
}

function showSticker2() {
    document.getElementById("gif2").style.display = "block";
}
</script>

</body>
</html>
