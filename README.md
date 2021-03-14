
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
.mySlides {display: none}
img {vertical-align: middle;}



<!DOCTYPE html>
<html>
<head>
	<title>Image Slider CSS3</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>
<div id="slider" >
<figure>
<img src="images/France.jpg">
<img src="images/Ibiza.jpg">
<img src="images/Amsterdam.jpg">
<img src="images/France.jpg">
<img src="images/Amsterdam.jpg">
</figure>	

</div>

</body>
</html>




<!DOCTYPE html>
<html>
<head>
<style>
div {
  background-color: lightgrey;
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
</style>
</head>
<body>

Description about this website

Firstly,this is not a proffesional website because i am not a professional web developer as well.But i think it will be worked to take attention of the students.It will be specilly used for the students of class XI-tulip
Things to plot here are-




☞Renaining time for upcoming(most recent) exam.


☞Notes(If possible)


☞Class links


☞Facebook group's important posts.

 
 
 💝Developed by Miah Mohammed Aman💝
Scholarshome,Shahi Eidgah.
Xi-Tulip
(Want to be an international programmer,pray for me)


document.getElementById("app").innerHTML = `
<div class="base-timer">
  <svg class="base-timer__svg" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
    <g class="base-timer__circle">
      <circle class="base-timer__path-elapsed" cx="50" cy="50" r="45" />
    </g>
  </svg>
  <span>
    <!-- Remaining time label -->
  </span>
</div>
`;
/* Sets the containers height and width */
.base-timer {
  position: relative;
  height: 300px;
  width: 300px;
}

/* Removes SVG styling that would hide the time label */
.base-timer__circle {
  fill: none;
  stroke: none;
}

/* The SVG path that displays the timer's progress */
.base-timer__path-elapsed {
  stroke-width: 7px;
  stroke: grey;
}
function formatTimeLeft(time) {
  // The largest round integer less than or equal to the result of time divided being by 60.
  const minutes = Math.floor(time / 60);
  
  // Seconds are the remainder of the time divided by 60 (modulus operator)
  let seconds = time % 60;
  
  // If the value of seconds is less than 10, then display seconds with a leading zero
  if (seconds < 10) {
    seconds = `0${seconds}`;
  }

  // The output in MM:SS format
  return `${minutes}:${seconds}`;
}
document.getElementById("app").innerHTML = `
<div class="base-timer">
  <svg class="base-timer__svg" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
    <g class="base-timer__circle">
      <circle class="base-timer__path-elapsed" cx="50" cy="50" r="45"></circle>
    </g>
  </svg>
  <span id="base-timer-label" class="base-timer__label">
    ${formatTime(timeLeft)}
  </span>
</div>
` 
.base-timer__label {
  position: absolute;
  
  /* Size should match the parent container */
  width: 300px;
  height: 300px;
  
  /* Keep the label aligned to the top */
  top: 0;
  
  /* Create a flexible box that centers content vertically and horizontally */
  display: flex;
  align-items: center;
  justify-content: center;

  /* Sort of an arbitrary number; adjust to your liking */
  font-size: 48px;
}
// Start with an initial value of 20 seconds
const TIME_LIMIT = 20;

// Initially, no time has passed, but this will count up
// and subtract from the TIME_LIMIT
let timePassed = 0;
let timeLeft = TIME_LIMIT;







