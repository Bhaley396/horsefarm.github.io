
<html>
<head>
<meta charset="utf-8">
<style>
*{
	margin:0;
	padding:0;
}
body{
	background:url(images/chema-photo-XAW98NjONmM-unsplash.jpg);
	background-position:center;
	background-repeat:no-repeat;
	background-size:cover;
	height:50vh;
	margin:0;
	width:79%;
	transition:2s ease-in-out;
}
body:hover{
	transition:2s ease-in-out;
	transition-delay:4s;
	background:url(images/helena-lopes-4QWoSS56ScA-unsplash.jpg);
	background-size:cover;
	height:50vh;
	background-repeat:no-repeat;
	background-position:center;
	margin:0;
	width:79%;
}
.dropdown{
	float:right;
	display:flex;
	flex:100%;
	width:100%px;
	margin:10px -50px;
	padding:0 -5px;
}
.dropdown ul{
	list-style:none;
}
.dropdown ul li{
	font-family:"Montserrat", Sans-serif;
	font-size:15px;
	font-weight:bold;
	color:white;
	text-shadow:0 0 5px black;
	background: none;
	width:150px;
	height:50px;
	line-height:50px;
	text-align:center;
	float:left;
	text-transform:uppercase;
	transition:0.5s;
	cursor:pointer;
}
.dropdown ul li:hover{
	cursor:pointer;
	text-shadow:none;
	color: #630;
	background:#FFF;
	font-weight:bold;
	border-radius:5px;
	text-decoration:underline;	
}
.dropdown ul ul{
	display:none;
}
.dropdown ul li:hover > ul{
	display:inline-block;
}
.dropdown ul li:hover > ul li{
	color:#630;
	text-shadow:none;
	background:#fff;
	border-radius:5px;
}
.dropdown ul li > ul li:hover{
	color:#630;
}


.mainheading{
	text-transform:uppercase;
	font-family:"Montserrat", Sans-serif;
	color:white;
	text-shadow:0 0 10px black;
	font-size:70px;
	font-weight:bolder;
	text-align:center;
	margin-top:130px;
	width:500px;
	margin-left:200px;
}
h3{
	font-family:"montserrat",sans-serif;
	text-transform:capitalize;
	font-size:17px;
	font-weight:normal;
	margin-left:120px;
	text-align:center;
	text-justify:auto;
	width:800px;
	color:#FFF;
	text-shadow:0 0 5px black;
}
.icon{
	margin:0;
	margin-top:-400px;
	margin-left:30px;
}
.iconheading{
	text-justify:auto;
	text-align:center;
	color:#fff;
	font-weight:bolder;
	font-size:18px;
	font-family:"Montserrat", Sans-serif;
	text-transform:uppercase;
	margin-left:100px;
	margin-top:-60px;
	max-width:100px;
	transition:1s linear;
	text-decoration:overline;
}
.iconheading:hover{
	text-decoration:underline;
	cursor:pointer;
	color:#09F;
	text-shadow:0 0 5px black;
}

input[type=text] {
  width: 130px;
  box-sizing: border-box;
  border: 2px solid #FFF;
  border-radius: 5px;
  float:right;
  font-size: 16px;
  margin-left:4000px;
  margin-right:-23%;
  margin-top:-60px;
  background-color: transparent;
  background-image: url('searchicon.png');
  background-position: 10px 10px; 
  background-repeat: no-repeat;
  padding: 12px 20px 12px 40px;
  -webkit-transition: width 0.4s ease-in-out;
  transition: width 0.4s ease-in-out;
  color:white;
  box-shadow:0 0 5px black;
  font-weight:bold;
  outline: white;
}
::placeholder{
	color:#fff;
	text-shadow:0 0 5px black;
}
input[type=text]:focus {
	border-radius:15px;
	outline:#A0522D;
	box-shadow:0 0 5px #fff;
	background: transparent;
  outline:#A0522D;
  width: 40%;
  margin-left:30%;
  margin-right:-40%;
  margin-top:30px;
  color:#000;
}


.box{
	width:120%;
	margin-left:100px;
	margin:50px;
	margin-top:20px;
	position:relative;
	overflow:hidden;
}
.box img{
	margin-left:100px;
	width:360px;
	height:500px;
	margin-top:20px;
	display:inline;
}
.content{
	margin-left:100px;
	margin-top:20px;
	position:absolute;
	top:0;
	right:120%;
	background-color:rgba(0,0,0,0.7);
	color:white;
	height:500px;
	width:360px;
	padding:20px;
	border-radius:20px;
	box-sizing:border-box;
	transition:all 0.8s ease-in-out 0.2s;
}
.box:hover .content{
	right:15%;
}


.services{    /*Services Section starts from here*/
	font-family:"montserrat",sans-serif;
	text-align:center;
	background:#fff;
	margin-top:515px;
	width:126.6%;
	margin-bottom:100px;
}
.services h1{
	display:inline-block;
	text-transform:uppercase;
	border-bottom: 4px solid #3498db;
	font-size:40px;
	color:#333;
	font-weight:lighter;
	padding-bottom:10px;
	margin-top:40px;
	margin-bottom:10PX;
}
.cen{
	max-width: 100%;
	height:70vh;
	margin:auto;
	margin-bottom:10px;
	overflow:hidden;
	padding:10px;
}
.service{
	display:inline-block;
	width: calc(100% / 3);
	margin: 0 -2px;
	padding: 20px;
	box-sizing: border-box;
	cursor:pointer;
	transition:0.4s;
	color:#333;
}
.service:hover{
	font-size: bold 700;
	color:black;
	background:#ddd;
}
.service i{
	color:#3498db;
	font-size: 34px;
	margin-bottom: 30px;
}
.service:hover i{
	color:blue;
}
.service h2{
	font-size:18px;
	text-transform:uppercase;
	font-weight:500;
	margin:0;
}
.service p{
	color:gray;
	font-size:15px;
	font-weight:500;
}
.services p{
	color:gray;
	margin:20px 50px;
}
@media screen and (max-width:800px)  {
	.service{
		width:50%;
	}
}
@media screen and (max-width:500px)  {
	.service{
		width:100%;
	}
}

.loginformpic{
	background:url(images/cesar-viteri-XpnKLnJVBNE-unsplash.jpg) no-repeat fixed;
	background-attachment:fixed;
	background-size:cover;
	width:1077px;
	height:500px;
}
.loginformpic2{
	width:50%;
	padding:30px 60px;
	opacity:0.95;
	margin:50px;
	margin-left:0;
	margin-top:90px;
	background:#FFF;
	position:absolute;
}
a:link, a:visited { /*Starting of submit button styling*/
  background-color: gray;
  color: #fff;
  font-weight:bold;
  text-transform:uppercase;
  padding: 10px 20px;
  text-align: center;
  display: inline-block;
  text-decoration:none;
  transition:0.5s ease-in-out;
  transition-property:all;
}
a:hover, a:active {
  background-color: #09F;
  color: white;
  font-weight:bolder;
  border-radius:15px;
  text-decoration:underline;
} /*Ending of submit button styling*/

.imagess{
	transition:0.5s;
}
.imagess:hover{
	cursor:pointer;
	opacity:0.5;
	height:90%;
	width:90%;
}

footer{
	height:170px;
	margin-right:-226px;
	background: #CCC;
	padding:60px;
}

.footicons{
	transition:0.5s;
	transition-timing-function:ease-in-out;
  text-align: center;
  padding:10px;
  margin:2px;
  font-size:32px;
  text-decoration: none;
}
.insta{
	font-size:large;
	border-radius:5px;
}
.insta:hover{
	border-radius:50%;
	background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%,#d6249f 60%,#285AEB 90%);
	color:white;
}
.twitter{
	font-size:large;
	border-radius:5px;
}
.twitter:hover{
	font-size:large;
	border-radius:50%;
	color:white;
	background-color:#00acee;
}
.google{
	font-size:large;
	border-radius:5px;
}
.google:hover{
	font-size:large;
	border-radius:50%;
	color:#db3236;
	background:white;
}
.facebook{
	font-size:large;
	border-radius:5px;
}
.facebook:hover{
	font-size:large;
	border-radius:50%;
	color:white;
	background:#3b5998;
}

.footheading1{
	text-justify:auto;
	text-align:center;
	color:#000;
	font-weight:bold;
	font-size:24px;
	font-family:"Montserrat", Sans-serif;
	text-transform:uppercase;
	transition:0.9s linear;
	opacity:0.7;
}
.footheading1:hover{
	cursor:text;
	opacity:1;
}
.footimage{
	display:inline-block;
	font-size:50px;
}
.lastline{
	text-shadow:0 0 5px gray;
	margin-bottom:5px;
	text-justify:auto;
	text-align:center;
	font-size:15px;
	font-family:"Montserrat", Sans-serif;
	text-transform:capitalize;
	opacity:1;
	color:black;
	font-weight:lighter;
}
.lastline:hover{
	color:white;
	text-shadow:0 0 5px black;
}





</style>
<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
<link href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" type="text/css" rel="stylesheet">
<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
</head>

<body>
<div class="dropdown">
	<ul>
    	<li>Home</li>
        <li>About</li>
        <li>Services <i class="fa fa-angle-down"></i>
        <ul>
            	<li>Horse Farming <i class="fa fa-angle-right"></i>
                <ul style="margin-left:150px; margin-top:-50px;">
                <li>Horse Riding</li>
                <li>Horse Care</li>
                <li>Horse Racing</li>
                </ul>
                </li>
            </ul>
        </li>
        <li>Contact</li>
    </ul>
</div>
<br>
<div>
	<center><div class="mainheading">horse farming</div></center>
    <br>
    <center><h3>Horses are used for riding and transport. They are also used for carrying things or pulling carts, or to help plow farmer's fields in agriculture. People have used selective breeding to make bigger horses to do heavy work. They are still used for work and transportation in some places, such as where there are no roads.</h3></center>
</div>

<div class="icon"><img src="images/wild-black-horse-lifting-front-foot.png" style="width:70px; height:70px;"></div>
<div class="iconheading">horse farming</div>

<div>
	<input type="text" name="search" placeholder="Search..">
</div>


<br>
<div>
	
    <div class="services">
	<center><h1>O U R  &nbsp; S E R V I C E S</h1><br><br>
    
    <p>Our services are very different as compare to other farmhouses, we care alot our horses & our clients happy with us always, we never give them a chance to any type of complain.</p>
    </center>
<div class="cen">
	<div class="service">
    	<i class="fas fa-headset"></i>
        <h2>24/7 Service</h2>
        <p>This is our service number one</p>
        </div>
        
        <div class="service">
    	<i class="fas fa-clock"></i>
        <h2>Our Time Management</h2>
        <p>This is our service number two</p>
        </div>
        
        <div class="service">
    	<i class="fas fa-hospital-user"></i>
        <h2>Customer Care</h2>
        <p>This is our service number 3</p>
        </div>
        
        <div class="service">
    	<i class="fas fa-layer-group"></i>
        <h2>Web Designing</h2>
        <p>This is our service number four</p>
        </div>
        
        <div class="service">
    	<i class="fas fa-apple-alt"></i>
        <h2>IOS Development</h2>
        <p>This is our service number five</p>
        </div>
        
        
        <div class="service">
        <i class="fab fa-android"></i>
        <h2>Android Development</h2>
        <p>This is our service number six</p>
        </div>
</div>
</div></div>

    
	<div><center><h4 style="font-weight:lighter; font-size:40px; margin-left:200px; color:#333; font-weight:500; margin-top:100px; font-family:sans-serif;">O U R  &nbsp; P R O J E C T S  &nbsp; & &nbsp;<br> W O R K</h4>
    
    <p style="margin-left:200px; font-weight:400; font-family:sans-serif; color:gray;">Our workers are very honest instead of other employees, we care alot our horses & our clients happy with us always, we never give them a chance to any type of complain.</p>
    </center>
<br>
</div>

<section style="max-width:100%; margin-left:100px; margin-right:-100px; margin-top:20px; font-family:"montserrat",sans-serif;"><center>
  <img class="imagess" src="images/mathew-schwartz-5qRWQEdK7Sg-unsplash.jpg" width="100%" height="100%"><br>
  <h4 style="font-family:Montserrat, Sans-serif; color:#333; font-weight:lighter; border-bottom: 3px solid #333; border-width:4px; display:inline-block; margin:15px; font-size:x-large;">HORSE RACING</h4>
  <p style="color:gray; font-family:Montserrat, Sans-serif;">We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></center>
</section>

<br>
<br>

<section style="max-width:100%; margin-left:100px; margin-right:-100px; margin-top:20px; font-family:"montserrat",sans-serif;"><center>
  <img class="imagess" src="images/philippe-oursel-D6HO8EHZ5bY-unsplash.jpg" width="100%" height="100%"><br>
  <h4 style="font-family:Montserrat, Sans-serif; color:#333; border-bottom: 3px solid #333; font-weight:lighter; border-width:4px; display:inline-block; margin:15px; font-size:x-large;">HORSE FARMING</h4>
  <p style="color:gray; font-family:Montserrat, Sans-serif;">We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></center>
</section>

<br>
<br>

<section style="max-width:100%; margin-left:100px; margin-right:-100px; margin-top:20px; font-family:"montserrat",sans-serif;"><center>
  <img class="imagess" src="images/philippe-oursel-lvSYFKau2Y8-unsplash.jpg" width="100%" height="100%"><br>
  <h4 style="font-family:Montserrat, Sans-serif; color:#333; border-bottom: 3px solid #333; font-weight:lighter; border-width:4px; display:inline-block; margin:15px; font-size:x-large;">HORSE RIDING</h4>
 <br>
  <p style="color:gray; font-family:Montserrat, Sans-serif;">We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p></center>
</section>

<br>
<br>


<div class="box" style="margin-top:20px; margin-left:50px;">
	<img src="images/elisa-pitkanen-MLtTdNgHw30-unsplash.jpg" width="360" height="500" style="border-radius:20px">    
    <div class="content">
    	<h4><i><center>HORSE RIDING</center></i></h4>
        <br><hr>
        <p>A riding horse or a saddle horse is a horse used by mounted horse riders for recreation or transportation. It is unclear exactly when horses were first ridden because early domestication did not create noticeable physical changes in the horse.</p>
        <hr>
        <br><br>
        <br>
        <h4><i><center>HORSE MANAGEMENT</center></i></h4>
        <br><hr>
        <p>There are many aspects to horse management. Horses, ponies, mules, donkeys and other domesticated equids require attention from humans for optimal health and long life.</p>
        <hr>
        <br>
    </div>
    
    <div style="margin: 20px 200px;"><center>
	<p style="text-align:center; font-family:Montserrat, Sans-serif; color:#000; border-bottom: 3px solid #630; border-width:4px; display:inline-block; margin:15px; font-weight:lighter; font-size:x-large;"><b>Q. What is a riding horse called?</b><br>
    <p style="color:gray; font-family:Montserrat, Sans-serif;">Ans:
 Equestrianism (from Latin equester, equestr-, equus, 'horseman', 'horse'), commonly known as horse riding (British English) or horseback riding (American English), includes the disciplines of riding, driving, or vaulting with horses.</p></p></div></center>
</div>



<div class="box" style="margin-top:10px; margin-left:50px;">
	<img src="images/markus-spiske-PBHi3bKJgHk-unsplash.jpg" width="360" height="500" style="border-radius:20px">
    
    <div class="content">
    	<h4><i><center>HORSE CARE</center></i></h4>
        <br><hr>
        <p><ul>
        		Daily Stable Management and Horse Care Routine
					<li>Feed horses hay and/or grain morning and night.</li>
					<li>Clean and refill water buckets morning and night.</li>
					<li>Muck out stalls morning and night.</li>
					<li>Replace fresh bedding.</li>
					<li>Check and pick out hooves daily.</li>
					<li>Remove blankets in the morning and replace in the evening during winter months.</li>
           </ul>
       </p>
        <hr>
        <br><br>
        <br>
        <h4><i><center>HORSE NEED</center></i></h4>
        <br><hr>
        <p>
They need daily care. Provide your horse with fresh clean water. Clean, readily available water is essential for good horse care. Provide your horse with adequate fodder and concentrates. If feeding hay, your horse will eat approximately two to three percent of its body weight every day.</p>
        <hr>
        <br>
    </div>
    
    <div style="margin: 20px 200px;"><center>
	<p style="text-align:center; font-family:Montserrat, Sans-serif; color:#333; border-bottom: 3px solid #333; border-width:4px; display:inline-block; margin:15px; font-weight:lighter; font-size:x-large;"><b>Q. What is a riding horse called?</b><br>
    <p style="color:gray; font-family:Montserrat, Sans-serif;">Ans:
 Equestrianism (from Latin equester, equestr-, equus, 'horseman', 'horse'), commonly known as horse riding (British English) or horseback riding (American English), includes the disciplines of riding, driving, or vaulting with horses.</p></p></div></center>
</div>


<div class="box" style="margin-top:10px; margin-left:50px;">
	<img src="images/paula-palmieri-s1B0_SB66uM-unsplash.jpg" width="360" height="500" style="border-radius:20px;">
    
    <div class="content">
    	<h4><i><center>HORSE CARE</center></i></h4>
        <br><hr>
        <p><ul>
        		Daily Stable Management and Horse Care Routine
					<li>Feed horses hay and/or grain morning and night.</li>
					<li>Clean and refill water buckets morning and night.</li>
					<li>Muck out stalls morning and night.</li>
					<li>Replace fresh bedding.</li>
					<li>Check and pick out hooves daily.</li>
					<li>Remove blankets in the morning and replace in the evening during winter months.</li>
           </ul>
       </p>
        <hr>
        <br><br>
        <br>
        <h4><i><center>HORSE NEED</center></i></h4>
        <br><hr>
        <p>
They need daily care. Provide your horse with fresh clean water. Clean, readily available water is essential for good horse care. Provide your horse with adequate fodder and concentrates. If feeding hay, your horse will eat approximately two to three percent of its body weight every day.</p>
        <hr>
        <br>
    </div>
    
    <div style="margin: 20px 200px;"><center>
	<p style="text-align:center; font-family:Montserrat, Sans-serif; color:#333; border-bottom: 3px solid #333; border-width:4px; display:inline-block; margin:15px; font-weight:lighter; font-size:x-large;"><b>Q. What is a riding horse called?</b><br>
    <p style="color:gray; font-family:Montserrat, Sans-serif;">Ans:
 Equestrianism (from Latin equester, equestr-, equus, 'horseman', 'horse'), commonly known as horse riding (British English) or horseback riding (American English), includes the disciplines of riding, driving, or vaulting with horses.</p></p></div></center>
</div>
</div>

<div class="loginformpic">
	<div class="loginformpic2">
    	<h1 style="font-family:Montserrat, Sans-serif; color:#333; font-weight:300; text-align:center;">O U R  &nbsp; M O D E R N &nbsp; L I F E </h1><br>
    	<p style="font-family:Montserrat, Sans-serif; color:gray; font-weight:lighter; text-align:center;">Our services are very different as compare to other farmhouses, we care alot our horses & our clients happy with us always, we never give them a chance to any type of complain Our services are very different as compare to other farmhouses, we care alot our horses & our clients happy with us always, we never give them a chance to any type of complain Our services are very different as compare to other farmhouses, we care alot our horses & our clients happy with us always, we never give them a chance to any type of complain.</p>
        <br>
        <br>
        <center><a href="#" target="_blank">View Our Work</a></center>
    </div>
</div>

<footer class="footheading1"><center>
<div>
  <a href="#" class="facebook"><i class="fa fa-facebook"></i></a>
  <a href="#" class="insta"><i class="fa fa-instagram"></i></a>
  <a href="#" class="twitter"><i class="fa fa-twitter"></i></a>
  <a href="#" class="google" class="right"><i class="fa fa-google"></i></a>
</div>
 <br>horse farming<br><br>
	<div class="footimage"><img src="images/wild-black-horse-lifting-front-foot.png" style="width:70px; height:70px;">
    <br><div class="lastline">&#169; 2020 All Rights Reserved. - Created By Sami-Siddiqui</div>
    
</center>
</div>
</footer>

</body>
</html>
