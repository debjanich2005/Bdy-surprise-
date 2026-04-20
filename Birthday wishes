<!DOCTYPE html>
<html>
<head>
    <title>Happy Birthday Preetam 💖</title>

    <style>
        body {
            margin: 0;
            text-align: center;
            font-family: 'Comic Sans MS', cursive;
            background: linear-gradient(to top, #ffd6e0, #fff0f5);
            overflow: hidden;
        }

        h1 {
            color: #ff4d6d;
            margin-top: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            margin: 20px;
            border-radius: 20px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }

        img {
            width: 150px;
            border-radius: 50%;
            border: 4px solid pink;
        }

        #typing {
            color: #ff4d6d;
            font-size: 18px;
            margin-top: 10px;
        }

        button {
            background: pink;
            border: none;
            padding: 10px 20px;
            border-radius: 20px;
            color: white;
            margin-top: 15px;
            cursor: pointer;
        }

        #surprise {
            display: none;
            color: #ff4d6d;
            font-size: 18px;
            margin-top: 15px;
        }

    </style>
</head>

<body>

<h1>🎂 Happy Birthday Preetam 🎂</h1>

<div class="card">

    <!-- BF Photo -->
    <img src="https://i.imgur.com/yourimage.jpg">

    <!-- Typing Message -->
    <div id="typing"></div>

    <!-- Gift Box -->
    <br><br>
    <img src="https://cdn-icons-png.flaticon.com/512/3468/3468371.png" 
    width="100" onclick="openGift()" id="gift">

    <!-- Hidden Surprise -->
    <div id="surprise">
        💖 Surpriseeee Baby 💖 <br><br>
        Tumi amar chocolate 🍫 <br>
        amar teddy 🐻 <br>
        amar shob kichu 💕 <br><br>
        Ami tomake onek onek bhalobashi 😘❤️
    </div>

</div>

<!-- Cute GIF -->
<img src="C:\Users\DEBJANI\OneDrive\Documents\bdy\p.JPEG" width="130">

<!-- Music -->
<audio autoplay loop>
  <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3">
</audio>

<script>

/// ❤️ Typing Effect
let text = "My cutest baby Preetam 🧸💖 ... Tumi amar life er sobcheye special manus 😘";
let i = 0;

function typeEffect() {
    if (i < text.length) {
        document.getElementById("typing").innerHTML += text.charAt(i);
        i++;
        setTimeout(typeEffect, 50);
    }
}
typeEffect();


/// 🎁 Gift Open
function openGift(){
    document.getElementById("gift").style.display = "none";
    document.getElementById("surprise").style.display = "block";
}


/// 💕 Falling Hearts
setInterval(() => {
    let heart = document.createElement("div");
    heart.innerHTML = "💗";
    heart.style.position = "fixed";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.top = "-10px";
    heart.style.fontSize = (15 + Math.random() * 20) + "px";

    document.body.appendChild(heart);

    let fall = setInterval(() => {
        let top = parseFloat(heart.style.top);
        heart.style.top = top + 2 + "px";

        if (top > window.innerHeight) {
            clearInterval(fall);
            heart.remove();
        }
    }, 20);
}, 300);


/// 💌 First popup
setTimeout(()=>{
    alert("Scan korar jonno thank you baby 😘❤️");
},1000);

</script>

</body>
</html>
