![Screenshot_20210130_191301](https://user-images.githubusercontent.com/80621063/111076696-91b17400-8517-11eb-813b-4ba97f17186d.jpg)


Hi THERE! 
<html>
<head>
<style>
body {
  background-color: black;
  font-family: Verdana, sans-serif;
  font-size: 16px;
  color: gray;  
}

h1 {
  font-family: Georgia, serif;
  font-size: 60px;
  color: red;
}
</style>
</head>
<body>

<h1>SCHOLARSHOME</h1>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.m![Screenshot_20210130_191307](https://user-images.githubusercontent.com/80621063/111076673-7cd4e080-8517-11eb-9228-453f064438f8.jpg)
ySlides {display: none}
img {vertical-align: middle;}




![Screenshot_20210130_191301](https://user-images.githubusercontent.com/80621063/111076696-91b17400-8517-11eb-813b-4ba97f17186d.jpg)
<!-- Display the countdown timer in an element -->
<p id="demo"></p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Jan 5, 2022 15:37:25").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

<style> p {   text-align: center; font-size: 20px; font-colour:yellow } </style>
<script> var deadline = new Date("Feb 7, 2021 11:00:00").getTime(); var x = setInterval(function() { var now = new Date().getTime(); var t = deadline - now; var days = Math.floor(t / (1000 * 60 * 60 * 24)); var hours = Math.floor((t%(1000 * 60 * 60 * 24))/(1000 * 60 * 60)); var minutes = Math.floor((t % (1000 * 60 * 60)) / (1000 * 60)); var seconds = Math.floor((t % (1000 * 60)) / 1000); document.getElementById("demo").innerHTML = days + "d "  + hours + "h " + minutes + "m " + seconds + "s ";     if (t < 0) {         clearInterval(x);         document.getElementById("demo").innerHTML = "EXPIRED";     } }, 1000); </script>    <iframe
