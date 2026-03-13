<!DOCTYPE html>
<html>
<head>
<title>Future Dev</title>

<style>
body{
margin:0;
font-family:Arial;
background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
color:white;
text-align:center;
}

.container{
margin-top:150px;
}

h1{
font-size:50px;
}

p{
font-size:20px;
opacity:0.8;
}

button{
padding:15px 40px;
font-size:18px;
border:none;
border-radius:30px;
background:#00ffcc;
color:black;
cursor:pointer;
transition:0.3s;
}

button:hover{
transform:scale(1.1);
background:#00ccaa;
}

.card{
width:300px;
margin:50px auto;
padding:20px;
background:rgba(255,255,255,0.1);
border-radius:15px;
backdrop-filter:blur(10px);
}
</style>

</head>

<body>

<div class="container">
<h1>Welcome</h1>
<p>My first cool website</p>

<button onclick="hello()">Click Me</button>

<div class="card">
<h2>Davud</h2>
<p>Future Developer</p>
</div>

</div>

<script>
function hello(){
alert("Welcome to my site!");
}
</script>

</body>
</html>
