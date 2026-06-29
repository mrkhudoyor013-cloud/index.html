<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mening Saytim</title>

<style>body::before{
content:"";
position:fixed;
width:300px;
height:300px;
background:cyan;
filter:blur(150px);
top:-100px;
left:-100px;
animation:move 8s infinite alternate;
}

@keyframes move{
0%{
transform:translate(0,0);
}
100%{
transform:translate(250px,400px);
}
}
body{
margin:0;
background:#0f172a;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
font-family:Arial;
color:white;
}

.card{transition:0.4s;
}

.card:hover{
transform:scale(1.05);
}
width:300px;
padding:20px;
background:#1e293b;
border-radius:20px;
text-align:center;
box-shadow:0 0 20px cyan;
}

img{
width:120px;
height:120px;
border-radius:50%;
}

button{}
padding:15px 40px;
border:none;
border-radius:50px;
background:#00e5ff;
font-size:20px;
transition:.3s;
}

button:hover{
transform:scale(1.1);
box-shadow:0 0 25px cyan;
button{
    margin-top:20px;
    padding:12px 30px;
    border:none;
    border-radius:10px;
    background:cyan;
    font-size:18px;
    transition:.3s;
}

button:hover{
    transform:scale(1.1);
    box-shadow:0 0 25px cyan;
}
</style>

</head>

<body>

<div class="card">
<img src="https://picsum.photos/200">
<h1>Khudoyor</h1>
<p>Mening shaxsiy saytim</p>
<a href="https://t.me/USERNAME">
<button>width:220px;
cursor:pointer;
font-weight:bold;</button>
</a>

<br><br>

<a href="https://instagram.com/USERNAME">
<button>Instagram</button>
</a>

<br><br>

<a href="https://youtube.com/@USERNAME">
<button>YouTube</button>
</a>
<a href="https://t.me/khudoyor0">
<button>Telegram</button>
</a>
  
</div>

</body>
</html>