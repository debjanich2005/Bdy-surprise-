<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>🎂 Happy Birthday Didi ❤️</title>

<style>

body{
    margin:0;
    padding:0;
    text-align:center;
    font-family:'Comic Sans MS',cursive;
    background:linear-gradient(to top,#ffd6e0,#fff0f5);
    overflow-x:hidden;
}

h1{
    color:#ff4d6d;
    margin-top:30px;
    font-size:40px;
}

.card{
    max-width:600px;
    margin:auto;
    background:white;
    padding:20px;
    border-radius:20px;
    box-shadow:0 0 20px rgba(0,0,0,0.1);
}

.profile{
    width:180px;
    height:180px;
    object-fit:cover;
    border-radius:50%;
    border:5px solid pink;
    animation:glow 2s infinite alternate;
}

@keyframes glow{
    from{
        box-shadow:0 0 10px pink;
    }
    to{
        box-shadow:0 0 30px hotpink;
    }
}

#typing{
    margin-top:15px;
    font-size:20px;
    color:#ff4d6d;
    min-height:80px;
}

#gift{
    width:120px;
    cursor:pointer;
    transition:0.3s;
}

#gift:hover{
    transform:scale(1.1);
}

#surprise{
    display:none;
    background:#fff0f5;
    padding:20px;
    border-radius:20px;
    margin-top:20px;
    color:#ff4d6d;
    font-size:20px;
}

button{
    background:pink;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:20px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    transform:scale(1.1);
}

.heart{
    position:fixed;
    top:-20px;
    font-size:25px;
    animation:fall linear forwards;
}

@keyframes fall{
    to{
        transform:translateY(110vh);
    }
}

.footer{
    margin-top:20px;
    color:#888;
}

</style>
</head>

<body>

<h1>🎂 Happy Birthday Didi ❤️</h1>

<div class="card">

<!-- Photo -->
<img src="C:\Users\DEBJANI\OneDrive\Documents\bdy\photo.jpg.jpeg" class="profile">
<!-- Music -->
<audio autoplay loop controls>
<source src="C:\Users\DEBJANI\OneDrive\Documents\bdy\music.mp3.ogg" type="audio/mpeg">
</audio>

<!-- Typing Message -->
<div id="typing"></div>

<br>

<h2>🎁 Open Your Surprise 🎁</h2>
<h2>TAP ME</h2>

<img id="gift"
src="https://cdn-icons-png.flaticon.com/512/3468/3468371.png"
onclick="openGift()">



<div id="surprise">

<h2>💖 Surpriseeeee 💖</h2>

<p>
Tumi amar life er sobcheye special manus ❤️<br><br>

Tor sob swapno puron hok 🌸<br>
Sob somoy hasi khushi thak 😊<br>
Ami sobsomoy tomar pashe achi 💕<br><br>

🎂 Happy Birthday Didi 🎂
</p>

</div>

<div class="footer">
✨ Made With Love💕 ✨
</div>

</div>


<script>

// Typing Effect

let text =
"💖 My Cutest Didi 💖 ... Tumi amar life er sobcheye special manus. Happy Birthday ❤️🎂";

let i=0;

function typeEffect(){

    if(i < text.length){

        document.getElementById("typing").innerHTML += text.charAt(i);

        i++;

        setTimeout(typeEffect,50);
    }
}

typeEffect();


// Open Gift

function openGift(){

    document.getElementById("gift").style.display="none";

    document.getElementById("surprise").style.display="block";

    alert("🎉 Surprise Unlocked 🎉");
}


// Falling Hearts

setInterval(()=>{

    let heart=document.createElement("div");

    heart.className="heart";

    heart.innerHTML="❤️";

    heart.style.left=Math.random()*100+"vw";

    heart.style.fontSize=
    (15+Math.random()*25)+"px";

    heart.style.animationDuration=
    (3+Math.random()*4)+"s";

    document.body.appendChild(heart);

    setTimeout(()=>{
        heart.remove();
    },7000);

},300);


// Welcome Popup

setTimeout(()=>{


alert("🎂 Happy Birthday Didi ❤️\nWishing you love, happiness, success, and all the joy in the world! ✨");

},1000);

</script>

</body>
</html>
