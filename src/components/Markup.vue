<template> 
<div>
<div class="block-1">
      <div class="container">
        <div class="navbar">
          <a href="">adventure</a>
          <a href="">crew</a>
          <a href="">gallery</a>
          <a href="">contact</a>
        </div>
        <div class="block-1-content">
          <div class="block-1-title"></div>
          <div class="block-1-title2"></div>
          <div class="block-1-button"></div>
        </div>
      </div>
  </div>
  <div class="delimiter"></div>
  <div class="block-2">
      <div class="block-2-left">
        <div class="block-2-left-img1"></div>
        <div class="block-2-left-img2"></div>
      </div>
      <div class="block-2-right">
        <p class="t1">ABOUT</p>
        <p class="t2">LOREM IPSUM</p>
        <div class="block-2-content"><div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores nulla, dignissimos voluptas repellat assumenda, similique aliquam? Enim similique nostrum magnam quod, quas nesciunt veritatis minus veniam culpa, mollitia accusamus odit.</div>
        <br>
        <div>Magnam amet repudiandae a, autem eligendi quas porro quibusdam dolore sint quo, doloremque dolorum molestiae ab vitae minima perspiciatis esse illo vel quam eveniet modi quidem aut rem totam! Libero.</div>
        <div>Nobis veritatis, corporis voluptatum blanditiis. Esse sed, consequatur tenetur aut odit nostrum fugit, aperiam laboriosam dolor ipsum nihil, blanditiis. Accusantium suscipit consequuntur rem similique architecto deleniti sint, atque eos officiis!</div></div>
      </div>
  </div>
  <div class="delimiter"></div>
  <div class="block-3"></div>
  <div class="delimiter"></div>
  <div class="block-4"></div>  
</div>  
</template>

<style type="text/css">
  
@font-face {
font-family: "Outrunfuture";  
src: url("../fonts/Outrun future.otf"); 
}

body{
  margin: 0 auto;
}
.container{
  width: 1280px;
  margin: 0 auto;
}
.block-1{
  width: 100%;
  height: 800px;
  background: url("../img/bg1.png");
  background-repeat: no-repeat;
  background-size: cover;
}
.navbar{
  display:flex;
  justify-content: space-between;
  align-items: center;
  width: 600px;
  padding-top:100px;
  margin: 0 auto;
}
.navbar a{
  color: #fff;
  text-decoration: none;
  font-size: 24px;
  font-family:'Outrunfuture';
  transition:.2s;
}
.navbar a:hover{
  color: #ff443c;
  transform: scale(1.2);
  }
.block-1-content{
  margin-top: 50px;
}
.block-1-title{
  width: 800px;
  height: 239px;
  background: url("../img/bg1_logo.png");
  background-size: cover;
  margin: 0 auto;
}
.block-1-title2{
  width: 492px;
  height: 52px;
  background: url("../img/bg1_logo2.png");
  background-size: cover;
  margin: 30px auto;
}
.block-1-button{
  width: 247px;
  height: 53px;
  background: url("../img/bg1_Button.png");
  margin: 0 auto;
  cursor: pointer;
  transition:.2s;
}
.block-1-button:hover{
  opacity:.5;
  box-shadow: 0px 0px 30px 15px #ff443c;
  border-radius: 4px;
  transform: scale(1.2);
}
.delimiter{
  width: 100%;
  height: 1px; 
  box-shadow: 0px 0px 30px 15px #000;
  background-color: #000;
}
.block-2{
  width: 100%;
  height: 800px;
  background: url("../img/bg2.jpg");
  box-shadow: inset 0 0 0 1000px rgba(0,0,0,.8);
  background-repeat: no-repeat;
  background-size: cover;
}
.block-2-left{
  float: left;
  margin-left: 214px;
}
.block-2-left-img1{
  width: 619px;
  height: 412px;
  position: relative;
  background: url("../img/bg2_img.png");
  top: 50px; z-index: 1; 
  box-shadow: 0px 0px 10px 4px #ff443c;
  border-radius:4px;
}
.block-2-left-img2{
  width: 502px;
  height: 334px;
  position: relative;
  background: url("../img/bg2_img2.png");
  left: -100px; top: -100px; z-index: 2;
  box-shadow: 0px 0px 10px 4px #ff443c;
  border-radius:4px;
}
.block-2-right{
  float: right;
  margin-right: 214px;
  font-family:'Outrunfuture';
}
.t1{font-size: 20px;color: #95a7ff;}
.t2{font-size: 50px;color: #fff;}

.block-2-content{
  width: 300px;
  text-align: left;
  font-family:'Verdana';
  font-size: 1rem;
  color: #ff443c;
}
.block-3{
  width: 100%;
  height: 800px;
  background: url("../img/bg3.png");
  box-shadow: inset 0 0 0 1000px rgba(0,0,0,.7);
  background-repeat: no-repeat;
  background-size: cover;
}

.block-4{
  width: 100%;
  height: 800px;
  background: url("../img/bg4.png");
  box-shadow: inset 0 0 0 1000px rgba(0,0,0,.7);
  background-repeat: no-repeat;
  background-size: cover;
}


/*@media screen and (max-width: 1500px){
  .block-1{height: 600px;}
  .navbar{width: 400px;padding-top:70px;}
  .block-1-content{margin-top:-200px;}
  .block-2{height: 600px;}
  .block-3{height: 600px;}
  .block-4{height: 600px;}
  
}

@media screen and (max-width: 1280px){
  .block-1{height: 400px;}
  .navbar{padding-top:50px;}
  .block-1-content{width: 90%; margin-top:-160px;}
  .block-2{height: 400px;}
  .block-3{height: 400px;}
  .block-4{height: 400px;}
}
@media screen and (max-width: 960px){
  .block-1-content{width: 80%; margin-top:-110px;}
}*/

@media screen and (max-width: 768px){
  .block-1{height: 300px;}
  .navbar{padding-top:20px;}
  .block-1-content{margin-top:-100px;}
  .block-2{height: 300px;}
  .block-3{height: 300px;}
  .block-4{height: 300px;}
}

@media screen and (max-width: 480px){
  .block-1{height: 200px;}
  .navbar{display: none;}
  .block-1-content{margin-top:0px;}
  .block-2{height: 200px;}
  .block-3{height: 200px;}
  .block-4{height: 200px;}
}

@media screen and (max-width: 320px){
  .block-1{height: 200px;}
  .block-2{height: 200px;}
  .block-3{height: 200px;}
  .block-4{height: 200px;}
}
</style>



