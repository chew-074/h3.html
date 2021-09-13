# h3.html
<!DOCTYPE html>
<html>
<meta charset="utf-8">
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css">

<head>
	<style type="text/css">
		
		.topnav {
  overflow: hidden;
  background-color: #333;box-sizing: border-box;
 
}

.topnav a {
float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 12px 16px;margin: 12px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #04AA6D;
  color: white;
}
	body {
  margin: 0;color: black; height: 100%;
  font-family: Arial, Helvetica, sans-serif;font-size: 18px; }
  .img-fluid{
  	width: 100%;height: 454px;
  }
.c {
  position: relative;
  font-family: Arial;
}

.text-block {
  position: absolute;
  bottom: 45px;
  right: 20px;
  background-color: rgb(0,0,0,0.5);
  color: white;
  padding-left: 20px;
  padding-right: 20px;
}
.t{
  border: 1px solid white;background-color: #3895D3;
  width: 477px;font-size: 20px;font-family: sans-serif;
  font-style: italic;height: 45px;padding:4px;color:  white;margin: 34px;font-size: 23px

}.b{
  background-color: white;border :1px solid white;width: 511px;color:  #3895D3;font-style: italic;height:433px;margin: 32px;font-size:21px;padding: 12px ;font-family: cursive;font-weight: bold;
}.p{
  color: black;font-family: serif;font-size: 20px
}.bb{
  background-color: #EEA47FFF
}.co{
  float: left;margin-left: auto;
  margin-right: auto;
margin: 34px;
 }


.ro::after {
  content: "";
  clear: both;
  display:table;}
 .mySlides {display: none;}

.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}



.active {
  background-color: #717171;
}

.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
.l{
  padding: 12px
}


	</style>
	
</head>
<body>
	<div class="topnav">
<h2 style="float: left;padding: 10px;color: white;font-style: italic;font-family: cursive;font-style: italic;font-size: 17px;color: #F2AA4CFF">Lauxry and Passion</h2>
		<a href="#">Home </a> 
		<a href="ya.html">Yacht Charter </a> 
		<a href="d.html">Desnitations</a> 
		<a href="co.html">Contant</a>
	</div>
	<div class="c">
 	<img src="8.jpg" class="img-fluid" alt="img"id="myimg">
 	<div class="text-block">
 		<a href="#" id="nex"><img src="1.png" width="57px"  ></a>
    <h4 style="font-family: cursive;font-size: 25px">Only good things from Luxury and Passinon</h4>
    <p style="font-family: cursive;">Call us Now to book a vacation of a life time<br>
09-3548593859
    </p>
  </div>
</div>
<div class="ro">
  <div class="co">
<div class="t">
  Destinations</div>
  <div class="b">

Relax is Good things.
<p class="p">
Covid 19 infection causes a lot of stress and people forget to rest due to work stress. People really need to love and relax. Our page offers great places to relax and unwind.


</p>
<div class="slideshow-container">

<div class="mySlides fade">

  <img src="g.jpg" style="width:93%">

</div>

<div class="mySlides fade">

  <img src="f.jpg" style="width:93%">

</div>

<div class="mySlides fade">
  
  <img src="e.jpg" style="width:93%">

</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>


</div></div>


<div class="co">
<div class="t bb" >
  Destinations</div>
  <div class="b">

Relax is Good things.
<p class="p">
Covid 19 infection causes a lot of stress and people forget to rest due to work stress. People really need to love and relax. Our page offers great places to relax and unwind.</p>
<img src="a.jpg" width="226px"  height="140px" class="l">
<img src="b.jpg" width="225px"  height="140px" class="l">
<img src="c.jpg" width="230px" height="140px" class="l">
<img src="d.jpg" width="225px" height="140px" class="l">
</div></div></div>
<script type="text/javascript">
	var img=['8.jpg','a.jpg','c.jpg'];
		var currentimg=0;
		document.getElementById('nex').onclick=nextp;
		function nextp(){
			currentimg++;
			if(currentimg>img.length-1){
				currentimg=0;
			}
			document.getElementById('myimg').src=img[currentimg];
		}

var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 1000); // Change image every 2 seconds
}
</script>
</body>
</html>



