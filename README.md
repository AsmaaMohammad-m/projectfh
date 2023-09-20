<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <style>
      body{
       
      }
       .text{
                display: inline-block;
                margin: 2%;
                margin-left: 40%;
                font-weight: bold;
                font-size: 30px;
                color: #ffc107;
                font-family: 'Courier New', Courier, monospace;
            }
      .card{
        margin: auto;
        box-shadow: 2px 2px 5px 3px gray;
      }
      .card-text{
        transition: all ease 3s;
      }
      p{
        transition: 3s;
      }
      .p{
        display: none;
        transition: all ease 3s;

      }
      .p2{
        display: none;
      }
      img{
        width: 100%;
        height: 200px;
      }
      h1{
        text-align: center;
        color:gray;
        margin: 10px;
        margin-bottom: 2%;
      }
     
	
#load{
  width: 100%;
  height: 100vh;
  position: fixed;
  top: 0;
  left:0;
  background-color: #ffc107;
}

.c {
	width: 200px;
	height: 100px;
	padding-top: 100px;
	margin: 0 auto;
}

.ball {
	width: 10px;
	height: 10px;
	margin: 10px auto;
	border-radius: 50px;
}

.ball:nth-child(1) {
	background: #ffffff;
	-webkit-animation: right 1s infinite ease-in-out;
	-moz-animation: right 1s infinite ease-in-out;
	animation: right 1s infinite ease-in-out;
}

.ball:nth-child(2) {
	background: #ffffff;
	-webkit-animation: left 1.1s infinite ease-in-out;
	-moz-animation: left 1.1s infinite ease-in-out;
	animation: left 1.1s infinite ease-in-out;
}

.ball:nth-child(3) {
	background: #ffffff;
	-webkit-animation: right 1.05s infinite ease-in-out;
	-moz-animation: right 1.05s infinite ease-in-out;
	animation: right 1.05s infinite ease-in-out;
}

.ball:nth-child(4) {
	background: #ffffff;
	-webkit-animation: left 1.15s infinite ease-in-out;
	-moz-animation: left 1.15s infinite ease-in-out;
	animation: left 1.15s infinite ease-in-out;
}

.ball:nth-child(5) {
	background: #ffffff;
	-webkit-animation: right 1.1s infinite ease-in-out;
	-moz-animation: right 1.1s infinite ease-in-out;
	animation: right 1.1s infinite ease-in-out;
}

.ball:nth-child(6) {
	background: #ffffff;
	-webkit-animation: left 1.05s infinite ease-in-out;
	-moz-animation: left 1.05s infinite ease-in-out;
	animation: left 1.05s infinite ease-in-out;
}

.ball:nth-child(7) {
	background: #ffffff;
	-webkit-animation: right 1s infinite ease-in-out;
	-moz-animation: right 1s infinite ease-in-out;
	animation: right 1s infinite ease-in-out;
}

@-webkit-keyframes right {
	0% {
		-webkit-transform: translate(-15px);
	}
	50% {
		-webkit-transform: translate(15px);
	}
	100% {
		-webkit-transform: translate(-15px);
	}
}

@-webkit-keyframes left {
	0% {
		-webkit-transform: translate(15px);
	}
	50% {
		-webkit-transform: translate(-15px);
	}
	100% {
		-webkit-transform: translate(15px);
	}
}

@-moz-keyframes right {
	0% {
		-moz-transform: translate(-15px);
	}
	50% {
		-moz-transform: translate(15px);
	}
	100% {
		-moz-transform: translate(-15px);
	}
}

@-moz-keyframes left {
	0% {
		-moz-transform: translate(15px);
	}
	50% {
		-moz-transform: translate(-15px);
	}
	100% {
		-moz-transform: translate(15px);
	}
}

@keyframes right {
	0% {
		transform: translate(-15px);
	}
	50% {
		transform: translate(15px);
	}
	100% {
		transform: translate(-15px);
	}
}

@keyframes left {
	0% {
		transform: translate(15px);
	}
	50% {
		transform: translate(-15px);
	}
	100% {
		transform: translate(15px);
	}
}
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-dark navbar-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Logo</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#head">HeadPhone</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled">Disabled</a>
              </li>
            </ul>
            
          </div>
        </div>
      </nav>
      <div class="caption">
        <span class="text" id="str"></span>
        <span class="type">|</span>
   </div>
      <h1>Wristwatch</h1>
      <div class="container">
        <div class="row">

       
      <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="images/c1.png" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">Hand Free</h5>
          <p class="card-text p" id="p">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-warning " id="btn">Go somewhere</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="images/c2.png" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">Hand Free</h5>
          <p class="card-text p2" id="p2">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-warning " id="btn2">Go somewhere</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="images/c3.png" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">Hand Free</h5>
          <p class="card-text p" id="p2">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-warning " id="btn2">Go somewhere</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img class="card-img-top" src="images/c4.png" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">Hand Free</h5>
          <p class="card-text p" id="p3">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-warning " id="btn3">Go somewhere</a>
        </div>
      </div>
  </div>
  </div>
  <h1>headphone</h1>
  <div class="container" id="head">
    <div class="row">

   
  <div class="card" style="width: 18rem;">
    <img class="card-img-top" src="images/p1.png" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Hand Free</h5>
      <p class="card-text p" id="p">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
      <a href="#" class="btn btn-warning " id="btn">Go somewhere</a>
    </div>
  </div>
  <div class="card" style="width: 18rem;">
    <img class="card-img-top" src="images/p2.png" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Hand Free</h5>
      <p class="card-text p2" id="p2">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
      <a href="#" class="btn btn-warning " id="btn2">Go somewhere</a>
    </div>
  </div>
  <div class="card" style="width: 18rem;">
    <img class="card-img-top" src="images/p3.webp" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Hand Free</h5>
      <p class="card-text p" id="p2">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
      <a href="#" class="btn btn-warning " id="btn2">Go somewhere</a>
    </div>
  </div>
  <div class="card" style="width: 18rem;">
    <img class="card-img-top" src="images/p4.png" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Hand Free</h5>
      <p class="card-text p" id="p3">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
      <a href="#" class="btn btn-warning " id="btn3">Go somewhere</a>
    </div>
  </div>
</div>
</div>
<div id="load">
  <div class="c">
    <div class="ball"></div>
    <div class="ball"></div>
    <div class="ball"></div>
    <div class="ball"></div>
    <div class="ball"></div>
    <div class="ball"></div>
    <div class="ball"></div>
  </div>
</div>




    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script>
      window.onl
      window.onload=function()
{
  setTimeout(function(){
    document.getElementById("load").style.display="none";
  },3000)
}     
 var str = "Welcome to our website",
               content = document.getElementById("str"),
               pos  = 0 ,
               speed = 250 ;
            
            function type() {
                "use strict";
                if(pos < str.length){
                    content.textContent += str.charAt(pos);
                    pos++;
                    setTimeout(type, speed);
                }else {
                    setTimeout(erase, speed);
                }
            }
            setTimeout(type, speed);
            
            function erase(){
                "use strict";
                if(pos >= 0){
                    content.textContent = str.substring(0 , pos);
                    pos= pos-1;
                    setTimeout(erase, speed);
                }else {
                    setTimeout(type , speed);
                }
            }
            
      var btn=document.getElementById("btn");
      var p=document.getElementById("p");
      btn.onclick=function(){

        p.classList.toggle("p");
      }
      var btn2=document.getElementById("btn2");
      var p2=document.getElementById("p2");
      btn2.onclick=function(){

        p2.classList.toggle("p2");
      }

    </script>

</body>
</html>
