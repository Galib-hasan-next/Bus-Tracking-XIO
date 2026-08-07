<?php
// View only. Data is prepared by the controller.
?>

<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Bus Tracker - Sign In</title>

<style>

*{

    margin:0;

    padding:0;

    box-sizing:border-box;

    font-family:'Segoe UI',Tahoma,Geneva,Verdana,sans-serif;

}

body{

    min-height:100vh;

    background:#eaf1ff;

    display:flex;

    justify-content:center;

    align-items:center;

    padding:30px;

}

.container{

    width:1200px;

    min-height:650px;

    background:#fff;

    border-radius:25px;

    overflow:hidden;

    box-shadow:0 20px 50px rgba(0,0,0,.15);

    display:flex;

}

/* ===========================
LEFT SIDE
=========================== */

.left{

    width:55%;

    background:

    linear-gradient(rgba(0,25,80,.45),

    rgba(0,25,80,.45)),

    url('img/bus.png');

    background-size:cover;

    background-position:center;

    color:#fff;

    padding:60px;

    display:flex;

    flex-direction:column;

    justify-content:space-between;

}

.logo{

    font-size:38px;

    font-weight:bold;

}

.logo span{

    color:#7dc0ff;

}

.title{

    font-size:52px;

    font-weight:bold;

    line-height:1.2;

}

.subtitle{

    margin-top:20px;

    font-size:22px;

    line-height:1.6;

}

.features{

    width:80%;

    background:rgba(255,255,255,.15);

    padding:25px;

    border-radius:20px;

    backdrop-filter:blur(8px);

}

.features p{

    font-size:18px;

    margin:18px 0;

}

/* ===========================
RIGHT SIDE
=========================== */

.right{

    width:45%;

    display:flex;

    justify-content:center;

    align-items:center;

    padding:50px;

}

.login-box{

    width:100%;

    max-width:380px;

}

.icon{

    text-align:center;

    font-size:70px;

    margin-bottom:20px;

}

h1{

    text-align:center;

    color:#0b2b6d;

    margin-bottom:10px;

}

.welcome{

    text-align:center;

    color:#777;

    margin-bottom:40px;

}

.error{

    background:#ffe6e6;

    color:red;

    padding:12px;

    border-radius:10px;

    text-align:center;

    margin-bottom:20px;

}

.input-box{

    margin-bottom:20px;

}

.input-box input{

    width:100%;

    padding:16px;

    border:1px solid #d5d5d5;

    border-radius:12px;

    font-size:16px;

}

.input-box input:focus{

    outline:none;

    border-color:#1d5eff;

}

.btn{

    width:100%;

    padding:16px;

    border:none;

    border-radius:12px;

    background:#1d5eff;

    color:white;

    font-size:18px;

    cursor:pointer;

    transition:.3s;

}

.btn:hover{

    background:#0b45d1;

}

.footer{

    text-align:center;

    color:#777;

    margin-top:25px;

}

.footer a{

    color:#1d5eff;

    text-decoration:none;

    font-weight:bold;

}

.footer a:hover{

    text-decoration:underline;

}

@media(max-width:900px){

.container{

    flex-direction:column;

}

.left,

.right{

    width:100%;

}

.left{

    min-height:350px;

}

.title{

    font-size:38px;

}

}

</style>

</head>

<body>

<div class="container">

<div class="left">

<div class="logo">

🚌 BUS <span>TRACKER</span>

</div>

<div>

<div class="title">

Smart Tracking<br>

Better Journey

</div>

<div class="subtitle">

Track buses in real time, book tickets easily,
and enjoy a smarter travel experience.

</div>

</div>

<div class="features">

<p>📍 Live Bus Tracking</p>

<p>🎫 Online Ticket Booking</p>

<p>🚌 Multiple Bus Companies</p>

<p>🛡 Safe & Reliable Service</p>

</div>

</div>

<div class="right">

<div class="login-box">

<div class="icon">

🚌

</div>

<h1>Welcome Back!</h1>

<p class="welcome">

Sign in to continue to Bus Tracker

</p>
<?php

if($message!=""){

    echo "<div class='error'>$message</div>";

}

?>

<form method="POST">

<div class="input-box">

<input
type="email"
name="email"
placeholder="Email Address"
required>

</div>

<div class="input-box">

<input
type="password"
name="password"
placeholder="Password"
required>

</div>

<button
type="submit"
class="btn">

Sign In

</button>

</form>

<div class="footer">

Don't have an account?

<a href="index.php?page=signup">

Sign Up

</a>

</div>

</div>

</div>

</div>

</body>

</html>

