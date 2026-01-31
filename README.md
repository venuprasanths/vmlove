<!DOCTYPE html>
<html>
<head>
<title>Venuprasanth ❤️ Madhusri</title>

<style>
body{
margin:0;
font-family:Arial;
background:linear-gradient(135deg,#ff5f8a,#ff9ab5);
height:100vh;
display:flex;
justify-content:center;
align-items:center;
overflow:hidden;
color:white;
}

.card{
background:rgba(255,255,255,.2);
padding:40px;
border-radius:25px;
text-align:center;
width:350px;
box-shadow:0 15px 40px rgba(0,0,0,.3);
backdrop-filter:blur(10px);
}

h1{margin:0;}

.names{margin:10px 0;font-size:22px;}

.heart{
font-size:80px;
animation:beat 1s infinite;
}

@keyframes beat{
0%{transform:scale(1)}
50%{transform:scale(1.3)}
100%{transform:scale(1)}
}

button{
margin-top:20px;
padding:10px 30px;
border:none;
border-radius:25px;
background:white;
color:#ff4f7b;
cursor:pointer;
}

footer{
margin-top:15px;
font-size:12px;
opacity:.8;
}

.floating{
position:fixed;
bottom:-20px;
animation:float 6s linear infinite;
}

@keyframes float{
to{transform:translateY(-110vh);opacity:0;}
}
</style>
</head>

<body>

<div class="card">
<h1>Forever Love</h1>

<div class="names">Venuprasanth ❤️ Madhusri</div>

<div class="heart">❤️</div>

<p>Two hearts<br>One soul<br>Endless love 💕</p>

<button onclick="msg()">Click Me</button>

<footer>Made with love 🤍</footer>
</div>

<script>
function msg(){
alert("Venuprasanth loves Madhusri forever ❤️");
}

setInterval(()=>{
let h=document.createElement("div");
h.className="floating";
h.innerHTML="❤️";
h.style.left=Math.random()*100+"%";
document.body.appendChild(h);
setTimeout(()=>h.remove(),6000);
},500);
</script>

</body>
</html>
