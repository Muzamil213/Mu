<!doctype html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer;"/>
<title>Page Title</title>
<style>
body{
height:10000px;
font-size:25px;
width:1000px;
}
.divSettings{
text-align:center;
background-color:blue;
display:flex;
justify-content:center;
align-item:center;
}
.heading{
margin-top:20px;
padding-left:00px;
background-color:blue;
text-align: center;
color:white;
margin-left:0px;
padding-left:0px;
}
.container1{
border:2px solid black;
width:500px;
height:350px;
margin-left:250px;
}
.container2{
border:2px solid black;
width:500px;
height:350px;
margin-left:250px;
}
img{
width:500px;
height:350px;
}
.like{
margin-left:250px;
margin-top:0px;
background-color: white;
border:none;
font-size:50px;
color:gray;
}
.setting{
background-color:blue;
color:white;
height:60px;
border:none;
font-size:50px;
margin-top:20px;
margin-left:650px;
}
.like2{
margin-left:250px;
margin-top:0px;
background-color: white;
border:none;
font-size:50px;
color:gray;
}
.send{
font-weight:bold;
border:none;
background-color:white;
margin-left:700px;
font-size:25px;
}
.send2{
font-weight:bold;
border:none;
background-color:white;
margin-left:700px;
font-size:25px;
}
.face{
display:inline;
font-size:50px;
margin-left:250px;
}
.face2{
display:inline;
font-size:50px;
margin-left:250px;
}
.p1{
margin-left:10px;
display:inline;
font-size:25px;
}
.p2{
margin-left:10px;
display:inline;
font-size:25px;
}
.heart{
margin-left:10px;
margin-top:0px;
background-color: white;
border:none;
font-size:50px;
color:gray;
}
.heart2{
margin-left:10px;
margin-top:0px;
background-color: white;
border:none;
font-size:50px;
color:gray;
}
textarea{
display:inline;
margin-left:250px;
border:2px solid;
width:500px;
font-weight:bold;
height:50px;
font-size:25px;
}
h3{
margin-left:250px;
}
.para{
font-size:30px;
margin-left:250px;
}
.para2{
font-size:30px;
margin-left:250px;
}
.blue{
color:blue;
}
.red{
color:red;
}
</style>
</head>
<body>
<div class="divSettings">
<h1 class="heading">Facebook 2</h1>

<button class="setting"><i class="fa-solid fa-gear"></i></button>
</div>
<br>
<br>
<div class="post1">

<div class="face"><i class="fa-solid fa-circle-user"></i></div>

<p class="p1">Arif</p>

<br>
<br>

<div class="container1">

<img src="https://i.ibb.co/Gkh9YJM/IMG-20210916-WA0012.jpg;">

</div>

<button class="like"><i class="fa-solid fa-thumbs-up"></i></button>

<button class="heart"><i class="fa-solid fa-heart"></i></button>

<p id="para" class="para"></p>

<h3>Comment</h3>

<textarea id="text" rows="1" cols="1"></textarea>

<button class="send" onclick="send()">Send</button>

</div>

<div class="post2">

<div class="face2"><i class="fa-solid fa-circle-user"></i></div>

<p class="p2">Muzamil</p>

<br>
<br>

<div class="container2">

<img src="https://i.ibb.co/VTNr3Bz/Myphoto.jpg;">

</div>

<button class="like2"><i class="fa-solid fa-thumbs-up"></i></button>

<button class="heart2"><i class="fa-solid fa-heart"></i></button>

<p id="para2" class="para2"></p>

<h3>Comment</h3>

<textarea id="text2" rows="1" cols="1"></textarea>

<button class="send2" onclick="send2()">Send</button>

</div>

<script>
function changeColor1(){
 blue.classList.toggle("blue");
}

var blue = document.querySelector(".like");
blue.onclick = changeColor1;

function changeColor2(){
 red.classList.toggle("red");
}

var red = document.querySelector(".heart");
red.onclick = changeColor2;

function send(){
var text = document.getElementById("text").value;
var para = document.getElementById("para");
para.innerHTML = "<b>You :</b>" + text;
}

function changeColor3(){
 blue2.classList.toggle("blue");
}

var blue2 = document.querySelector(".like2");
blue2.onclick = changeColor3;

function changeColor4(){
 red2.classList.toggle("red");
}

var red2 = document.querySelector(".heart2");
red2.onclick = changeColor4;

function send2(){
var text2 = document.getElementById("text2").value;
var para2 = document.getElementById("para2");
para2.innerHTML = "<b>You :</b>" +  text2;
}
</script>
</body>
</html>
