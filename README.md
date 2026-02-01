<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>For My Love Rida ❤️</title>

<style>
body{
    margin:0;
    font-family:'Poppins', sans-serif;
    background: linear-gradient(135deg,#ff9ecf,#ffc1e3,#ffd6ec);
    overflow-x:hidden;
    text-align:center;
    color:#333;
}

.heart{
    position:fixed;
    bottom:-20px;
    font-size:20px;
    animation: float 6s linear infinite;
    opacity:0.6;
}
@keyframes float{
    to{
        transform: translateY(-110vh);
        opacity:0;
    }
}

section{
    padding:60px 20px;
}

h1{
    font-size:50px;
    color:#d6006e;
}

.card{
    background:white;
    padding:20px;
    border-radius:20px;
    margin:15px;
    display:inline-block;
    width:260px;
    box-shadow:0 8px 20px rgba(0,0,0,0.15);
    transition:0.3s;
}
.card:hover{
    transform:scale(1.05);
}

.gallery img{
    width:200px;
    height:200px;
    object-fit:cover;
    border-radius:20px;
    margin:10px;
    transition:0.4s;
}
.gallery img:hover{
    transform:scale(1.1);
}

button{
    padding:15px 30px;
    border:none;
    background:#ff3f8e;
    color:white;
    font-size:18px;
    border-radius:30px;
    cursor:pointer;
}

#popup{
    display:none;
    position:fixed;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    background:white;
    padding:40px;
    border-radius:20px;
    box-shadow:0 0 30px rgba(0,0,0,0.3);
}
</style>
</head>

<body>

<script>
setInterval(()=>{
    let heart=document.createElement("div");
    heart.className="heart";
    heart.innerHTML="❤️";
    heart.style.left=Math.random()*100+"vw";
    heart.style.fontSize=(15+Math.random()*25)+"px";
    document.body.appendChild(heart);
    setTimeout(()=>heart.remove(),6000);
},300);
</script>

<section>
<h1>For My Wifey ❤️</h1>
<h2>You are my love, my peace, my forever.</h2>
<p>Every moment with you feels like magic ✨</p>
</section>

<section>
<h2>my beautiful wife hehe 📸</h2>
<div class="gallery">
    <img src="wifey.jpg.jpeg" alt="Rida photo">
    <img src="wifey2.jpeg" alt="Rida photo">
    <img src="WIFEY3.jpeg" alt="Rida photo">
    <img src="WIFEY4.jpeg" alt="Rida photo">
</div>
</section>

<section>
<h2>Why I Love You 💌</h2>
<div class="card">Your smile makes my worst days better</div>
<div class="card">You understand me like no one else</div>
<div class="card">Your laugh is my favorite sound</div>
<div class="card">You support my dreams</div>
<div class="card">You are my safe place</div>
<div class="card">You are my forever person</div>
</section>

<section>
<h2>Message From My Heart ❤️</h2>
<p style="max-width:700px;margin:auto;font-size:18px;line-height:1.7;">
Rida,
From the day you came into my life, everything became brighter.
You are my happiness, my comfort, my motivation, and my home.
Every second with you feels special.
I promise to always care for you, protect you, and love you more every day.
I don’t just love you… I choose you, every single day. 💖
</p>
</section>

<section>
<button onclick="showLove()">Click for Surprise 🎁</button>
</section>

<div id="popup">
<h2>I Love You Rida ❤️</h2>
<p>You are the best thing that ever happened to me.</p>
<button onclick="closeLove()">Close</button>
</div>

<script>
function showLove(){
    document.getElementById("popup").style.display="block";
}
function closeLove(){
    document.getElementById("popup").style.display="none";
}
</script>

</body>
</html>
