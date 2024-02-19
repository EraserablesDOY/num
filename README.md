<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Eraserables</title>
</head>
<body>
	<div class="square"></div>
<style>
body
{
	background-color: #F9E79F;
}
.navbar {
    display: flex;
    align-items: center;
    height: 100px;
    background-color: #D7BDE2;
    padding: 0 2%;
}

#logo {
    width: 100px;
    height: 100px;
    margin-right: 10px;
}

ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
}

li {
    margin-left: 20px;
    position: relative; /* For dropdown positioning */
}

a {
    color: #F9E79F;
    text-decoration: none;
    font-size: 29px;
}

a:hover {
    color: #3658F0;
}

.dropdown {
    position: absolute;
    background-color: silver;
    display: none;
    top: 100%; /* Align with the bottom of the navbar */
    left: 0;
    font-size: 18px;
    color: black;
}

.navbar li:hover .dropdown {
    display: block;
}

.dropdown ul {
    padding: 20px;
    margin: 0;
}

.dropdown li {
    margin-top: 10px;
}
.circle2 {
    display: block;
    justify-content: space-around;
    align-items: center;
    background-color: #F9E79F;
    height: 100px; 
    width: 25%;
    /* position: relative; */
    margin-top: 10px;
    padding-left: 100px;
    float:right;
}

.circle {
    background-color: silver;
    border-radius: 50%;
    height: 100px;
    width: 100px;
    overflow: hidden;
    margin: 10% auto 0; /* Centers the div and moves it down */
    overflow: hidden; /* Ensures the image does not exceed the circular boundary */
    display: flex; /* Centers the image within the circle */
    justify-content: center; /* Center horizontally */
    align-items: center; /* Center vertically */
    border:3px solid #000;
    position: relative;
}
.circle:hover
{
	opacity: 50%;
}
#photo
{
	text-align: left;
	width: 900px;
	font-size: 30px;
    margin-top: 10%;
    margin-left: 3%;
    display: block;
}
.footer
{
	height: 100px;
	width: 100%;
	background-color: #B8E0D2;
	margin-top: 35%;
}
#phony
{
	height:40px;
	width: 40px;
}
#cateraser
{
	background-image:url("/Users/avantikanambiar/Desktop/coding stuff/eraser.jpeg");
	width: 100%; /* Make the image fill the container */
    height: auto; /* Maintain aspect ratio */
}
#sonicbutdead
{
	background-image:url("/Users/avantikanambiar/Desktop/coding stuff/sonicbutdead.jpeg");
	width: 100%;
	height: auto;
}
#panda
{
	background-image:url("/Users/avantikanambiar/Desktop/coding stuff/KUNGFO.jpeg");
	width: 100%;
	height: auto;
}
#pinterest
{
	background-image:url("/Users/avantikanambiar/Desktop/coding stuff/pinterest.png");
	height: 40px;
	width: 40px;
}
.circle {
    position: relative;
    display: inline-block; 
 
    margin-left: 200px; 
}

.allcircle {
    height: 150px;
    width: 20%;
    background-color: darkblue;
    position: absolute;
    top: 50%; 
    left: -100%; 
    transform: translateY(-50%); 
    display: none; 
    white-space: nowrap;
    z-index: 1;
  
    transition: opacity 0.3s ease-in-out;
    opacity: 0; 
}
.circle:hover .allcircle
{
	display: block;
	opacity: 1;
}
#collage
{
    height: 70%;
    width: 70%;
    margin-top: 20%;
    display: block;
}
.main
{
    display: flex;
    justify-content: space-between;
}
</style>
<div class="navbar">
    <img src="logocoding.jpeg" id="logo">
    <ul>
        <li><a href="">Home</a></li>
        <li><a href="">About me</a></li>
        <li><a href="">Buy</a></li>
        <li>
            <a href="">Courses</a>
            <div class="dropdown">
                <ul>
                    <li>html/css</li>
                    <li>Javascript</li>
                    <li>Python</li>
                </ul>
            </div>
        </li>
    </ul>
</div>
<div class="main">
    

<p id="photo">At Eraserables, we believe every eraser is more than just a tool; it's a partner in your creative and correctional journey. Our erasers are crafted to not only remove pencil marks but also to last, reducing waste and encouraging a more sustainable approach to stationery.</p>
<div class="collage">
    <img src="/Users/avantikanambiar/Desktop/coding stuff/Eraserables.jpg" alt=collage id="collage">
</div>
<div class="circle2">
    <div class="circle"><img src="/Users/avantikanambiar/Desktop/coding stuff/eraser.jpeg" alt="Cat Eraser" id="cateraser"><div class="allcircle">circles</div></div>
    <div class="circle"><img src="/Users/avantikanambiar/Desktop/coding stuff/sonicbutdead.jpeg" alt="Sonic" id="sonicbutdead"><div class="allcircle">circles</div></div>
    <div class="circle"><img src="/Users/avantikanambiar/Desktop/coding stuff/KUNGFO.jpeg" alt="panda" id="panda"><div class="allcircle">circles</div></div>
</div>
</div>
<div class="footer"> 
	<img src="phone-call.png" id="phony"> <img src="pinterest.png" id="pinterest">
<ul>
		<li>+1(693)275-1342</li>

</ul>
</div>
</body>
</html>
