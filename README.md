<!DOCTYPE html>
<html lang="en">
<title>Andrew_Datz</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif}
.w3-bar,h1,button {font-family: "Montserrat", sans-serif}
.fa-anchor,.fa-coffee {font-size:200px}
</style>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-red w3-card w3-left-align w3-large">
    <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-white w3-large w3-red" href="javascript:void(0);" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large w3-white">Home</a>
    <a href="https://www.flickr.com/people/195081609@N08/">visit About Andrew Datz flickr< class="">Link 1</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Link 2</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Link 3</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Link 4</a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium w3-large">
    <a href="#" class="w3-bar-item w3-button w3-padding-large">https://www.flickr.com/people/195081609@N08/">visit About Andrew Datz flickr< class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Link Link 1</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Link 2</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Link 3</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Link 4</a>
  </div>
</div>

<!-- Header -->
<header class="w3-container w3-red w3-center" style="padding:128px 16px">
  <h1 class="w3-margin w3-jumbo">Repository</h1>
  <p class="w3-xlarge">Andrew Datz</p>
  <button class="w3-button w3-black w3-padding-large w3-large w3-margin-top"> <>Get Started</button>
</header>

<!-- First Grid -->
<div class="w3-row-padding w3-padding-64 w3-container">
  <div class="w3-content">
    <div class="w3-twothird">
      <h1>Beginnings</h1>
      <h5 class="w3-padding-32">Hello, my name is Andrew Datz</h5>

      <p class="w3-text-grey">I am currently looking into becoming a videographer A videographer is a person that specializes in shooting and editing high-definition videos of live events and small-scale video production. this makes them presentable to clients and work on short materials such as documentaries, short-films, advertisements, and live events such as weddings, parties, and sports events.</p>
    </div>

    <div class="w3-third w3-center">
      <h2></h2>
      <img src="Images/Img_1.png" alt_Img-1 width="200" height="150">
    </div>
  </div>
</div>

<!-- Second Grid -->
<div class="w3-row-padding w3-light-grey w3-padding-64 w3-container">
  <div class="w3-content">
    <div class="w3-third w3-center">
      <i class="!H3 class= "W3-center">[Img-1](https://user-images.githubusercontent.com/100314090/159071857-56180e99-4b0f-4301-8745-49353790aa1b.png)</i>
    </div>

</picture>
    <div class="w3-twothird">
      <h1>Bio</h1>
      <h5 class="w3-padding-32">In order to start looking at my profession and what I am striving to work for in the past </h5>

      <p class="w3-text-grey">Working up from my highschool years I took interest to an engineering class and continued throughout my freshmen to senior years. During those classes I had to work on numerous projects such as a programmable all terrain remote vehicle in my sophmore year. I looked into video production as a major and started taking a video class. My projects there included making a video during the school year. During the winter break I had to make a stopmotion film that is a minute long and I did that utilizing stopmotion, and post-production audio editing. Overtime I decided to utilize the ingenuity from the all-terrain vehicle and placed this into my video production.
    </div>                 
  </div>
</div>

<div class="w3-container w3-black w3-center w3-opacity w3-padding-64">
    <h1 class="w3-margin w3-xlarge">Quote of the day: Work is like food, if you add too much or too little flavor it becomes ruined.</h1>
</div>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-opacity">
  <div class="w3-xlarge w3-padding-32">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
 </div>
 <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
</footer>

<script>
// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else {
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>

</body>
</html>
