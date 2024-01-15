<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <link rel="stylesheet" href="style.css">
 <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous"/>
 <link rel="stylesheet" href="https://fonts.google.com/specimen/Poppins">
 <title>Huddle</title>
</head>
<body>
<header class="header">
 <img src="../huddle/img/logo.svg">
</header>
<main>
<section class="container">
<div class="box1">
 <img src="../huddle/img/illustration-mockups.svg">
</div>
<div class="box2">
 <h1>Build The Community Your Fans Will Love</h1>
 <p>Huddle re-imagines the way we build communities. You have a voice but so does your audience. Create connections with your users as you engage in genuine discussion. </p>
 <a href="#" class="btn">Register</a>
</div>
</section>
</main>
<footer>
 <i class="fab fa-facebook-f" id="gif"></i>
 <i class="fab fa-twitter" id="gif"></i>
 <i class="fab fa-instagram" id="gif"></i>
</footer>
</body>
</html>

* {
margin:0;
padding: 0;
box-sizing: border-box;
}
body {
background-image: url(../projects/images/bg-desktop.svg);
background-color: hsl(257, 40%, 49%);
color: #fff;
}
h1 {
font-size: 35px;
}
p{
margin-top: 15px;
line-height: 1.6;
}
.header {
margin: 20px;
padding: 20px;
}
main {
margin: 20px;
padding: 20px;
}
.container {
display: flex;
}
.box1 {
width: 60%;
}
.box2 {
width: 40%;
margin: 10px;
padding:20px;
}
.btn {
background: #fff;
color: purple;
text-align: center;
border-radius: 10px;
margin-top: 20px;
text-decoration: none;
display: block;
width: 40%;
padding: 5px;
}
footer{
text-align: end;
margin-right: 60px;
margin-bottom: 50px;
word-spacing: 10px;   
}
#gif{
width: 30px;
height: 30px;
line-height: 30px ;
text-align: center;
display: inline-block;
border: 1px solid #fff;
border-radius: 50%;
}
@media(max-width:768px) {
body {
background-image: url(../projects/images/bg-mobile.svg) no-repeat center center/cover;
background-color: hsl(257, 40%, 49%);
color: #fff;
}
p{
font-size: 20px;
}
.box1 img{
width:430px;
}
.container{
flex-direction: column;
justify-content: center;
}
.box2{
text-align: center;
width: 100%;
margin-top: 10px;
}
.btn{
margin: auto;
margin-top: 15px;
padding:10px;
}
footer{
text-align:center;
}
}
