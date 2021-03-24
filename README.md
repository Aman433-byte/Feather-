<html>
<title>W3.CSS Template</title>
<meta charset="UTF-7">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
html,body,h1,h2,h3,h4,h5 {font-family: "Raleway", sans-serif}
</style>
<body class="w3-light blue">

<!-- Top container -->
<div class="w3-bar w3-top w3-light-white w3-large" style="z-index:4">
  <button class="w3-bar-item w3-button w3-hide-large w3-hover-none w3-hover-text-blue" onclick="w3_open();"><i class="fa fa-bars"></i>  Menu</button>
<span class="w3-bar-item w3-right">💓</span>
</div>

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-collapse w3-blue w3-animate-left" style="z-index:3;width:300px;" id="mySidebar"><br>
  <div class="w3-container w3-row">
    <div class="w3-col s4">
      <img src="/w3images/avatar2.png" class="w3-circle w3-margin-right" style="width:46px">
    </div>
    <div class="w3-col s8 w3-bar">
      <span>Hello, <strong>It's Aman</strong></span><br>
      <a href="#" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i></a>
      <a href="#" class="w3-bar-item w3-button"><i class="fa fa-user"></i></a>
      <a href="#" class="w3-bar-item w3-button"><i class="fa fa-cog"></i></a>
</div>
  </div>
  <hr>
  <div class="w3-container">
    <h5>Classes</h5>
  </div>
  <div class="w3-bar-block">
    <a href="#" class="w3-bar-item w3-button w3-padding-16 w3-hide-large w3-dark-grey w3-hover-black" onclick="w3_close()" title="close menu"><i class="fa fa-remove fa-fw"></i>  Close Menu</a>
    <a href="http://learn.p2.blog/2021/03/16/online-class-schedule/" class="w3-bar-item w3-button w3-padding w3-blue"><i class="fa fa-users fa-fw"></i>  Sunday</a>
    <a href="http://learn.p2.blog/2021/03/16/online-class-monday/" class="w3-bar-item w3-button w3-padding"><i class="fa fa-eye fa-fw"></i>  Monday</a>
    <a href="http://learn.p2.blog/2021/03/16/online-class-tuesday/" class="w3-bar-item w3-button w3-padding"><i class="fa fa-users fa-fw"></i>  Tuesday</a>
    <a href="http://learn.p2.blog/2021/03/16/online-class-wednesday/" class="w3-bar-item w3-button w3-padding"><i class="fa fa-bullseye fa-fw"></i>  Wednesday</a>
    <a href="http://learn.p2.blog/2021/03/16/online-class-thursday/" class="w3-bar-item w3-button w3-padding"><i class="fa fa-diamond fa-fw"></i>  Thursday</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-bell fa-fw"></i>  Facebook Group</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-bell fa-fw"></i>  Google ClassRooms</a>
</div>
  <hr>
  <div class="w3-container">
<h5>My Portfolio</h5>
  </div>
  <div class="w3-bar-block">
    <a href="#" class="w3-bar-item w3-button w3-padding-16 w3-hide-large w3-dark-grey w3-hover-black" onclick="w3_close()" title="close menu"><i class="fa fa-remove fa-fw"></i>  Close Menu</a>
    <a href="#" class="w3-bar-item w3-button w3-padding w3-blue"><i class="fa fa-users fa-fw"></i>  Name:Miah Mohammed Aman</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-eye fa-fw"></i>  Class:XI</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-users fa-fw"></i>  Section:Tulip</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-education fa-fw"></i>  Aim:Want to take graduation in CSE from BUET</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-books fa-fw"></i>  Recent:Not a prpffesional but want to be an international</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-bell fa-fw"></i>  News</a>
<a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-bank fa-fw"></i>  General</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-history fa-fw"></i>  History</a>
    <a href="#" class="w3-bar-item w3-button w3-padding"><i class="fa fa-cog fa-fw"></i>  Settings</a><br><br>
  </div>    
</nav>


<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>
<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px;margin-top:43px;">

  <!-- Header -->
  <header class="w3-container" style="padding-top:22px">
    <h5><b><i class="fa fa-dashboard"></i> Class Details</b></h5>
  </header>

  <div class="w3-row-padding w3-margin-bottom">
    <div class="w3-quarter">
      <div class="w3-container w3-red w3-padding-16">
        <div class="w3-left"><i class="fa fa-comment w3-xxxlarge"></i></div>
 <div class="w3-right">
          <h3>68</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>Students</h4>
      </div>
    </div>
    <div class="w3-quarter">
      <div class="w3-container w3-blue w3-padding-16">
        <div class="w3-left"><i class="fa fa-eye w3-xxxlarge"></i></div>
        <div class="w3-right">
          <h3>25</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>Teachers</h4>
</div>
    </div>
    <div class="w3-quarter">
      <div class="w3-container w3-teal w3-padding-16">
        <div class="w3-left"><i class="fa fa-share-alt w3-xxxlarge"></i></div>
        <div class="w3-right">
          <h3>Active Students</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>Classes</h4>
      </div>
    </div>
    <div class="w3-quarter">
      <div class="w3-container w3-orange w3-text-white w3-padding-16">
<div class="w3-left"><i class="fa fa-users w3-xxxlarge"></i></div>
        <div class="w3-right">
          <h3>Presents</h3>
        </div>
        <div class="w3-clear"></div>
        <h4>Absetns</h4>
      </div>
    </div>
  </div>

  
    <h5>Daily Overview</h5>
    <p>Total Presents</p>
    <div class="w3-grey">
      <div class="w3-container w3-center w3-padding w3-green" style="width:60%">+60%</div>
    </div>

    <p>Absents</p>
    <div class="w3-grey">
      <div class="w3-container w3-center w3-padding w3-orange" style="width:30%">30%</div>
    </div>

    <p>Leave</p>
<div class="w3-grey">
      <div class="w3-container w3-center w3-padding w3-red" style="width:10%">10%</div>
    </div>
  <hr>

  <div class="w3-container">
    <table class="w3-table w3-striped w3-bordered w3-border w3-hoverable w3-white">
      <tr>
<h2>Contact Me</h2>
        
    <button class="w3-button w3-dark-grey">my email:miahmohammedaman@gmail.com  <i class="fa fa-arrow-right"></i></button>
  <hr>
  <div class="w3-container">
    <h5>CAPTAINS</h5>
    <ul class="w3-ul w3-card-4 w3-white">
      <li class="w3-padding-16">
        <img src="/w3images/avatar2.png" class="w3-left w3-circle w3-margin-right" style="width:35px">
        <span class="w3-
xlarge">MAHADI</span><br>
      </li>
      <li class="w3-padding-16">
        <img src="/w3images/avatar5.png" class="w3-left w3-circle w3-margin-right" style="width:35px">
        <span class="w3-xlarge">JIDAN</span><br>
      </li>
      <li class="w3-padding-16">
        <img src="/w3images/avatar6.png" class="w3-left w3-circle w3-margin-right" style="width:35px">
        <span class="w3-xlarge">AYSHA</span><br>
</li>
      <li class="w3-padding-16">
        <img src="/w3images/avatar6.png" class="w3-left w3-circle w3-margin-right" style="width:35px">
        <span class="w3-xlarge">SAMIHA</span><br>
</li>
    </ul>
  </div>
  <hr>

  
  <br>
  <div class="w3-container w3-dark-grey w3-padding-32">
    <div class="w3-row">
      <div class="w3-container w3-third">
<h5 class="w3-bottombar w3-border-green">Demographic</h5>
        <p>Language</p>
        <p>Country</p>
        <p>City</p>
      </div>
      <div class="w3-container w3-third">
<h5 class="w3-bottombar w3-border-red">System</h5>
        <p>Browser</p>
        <p>OS</p>
        <p>More</p>
      </div>
      <div class="w3-container w3-third">
        <h5 class="w3-bottombar w3-border-orange">Target</h5>
        <p>Users</p>
        <p>Active</p>
        <p>Geo</p>
        <p>Interests</p>
      </div>
    </div>
  </div>
<!-- Footer -->
  <footer class="w3-container w3-padding-16 w3-light-grey">
    <h4>ধন্যবাদ</h4>

  <!-- End page content -->
</div>

<script>
// Get the Sidebar
var mySidebar = document.getElementById("mySidebar");
// Toggle between showing and hiding the sidebar, and add overlay effect
function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
    overlayBg.style.display = "none";
  } else {
mySidebar.style.display = 'block';
    overlayBg.style.display = "block";
  }
}

// Close the sidebar with the close button
function w3_close() {
  mySidebar.style.display = "none";
  overlayBg.style.display = "none";
}
</script>
আবার আসবেন।
div {
    background: linear-gradient(to bottom right, #33ccff 22%, #ff99cc 107%);
}

<h1>Welcome</h1>
<p>Feed Back</p>

</body>
</html>

 

<form>
<input style="width: 200px; padding: 20px; cursor: pointer; box-shadow: 6px 6px 5px; #999; -webkit-box-shadow: 6px 6px 5px #999; -moz-box-shadow: 6px 6px 5px #999; font-weight: bold; background: #ffff00; color: #000; border-radius: 10px; border: 1px solid #999; font-size: 140%;" type="button" value="FeedBack" onclick="window.location.href=https://forms.gle/2B9YuxwvC6q42BwYA/">
</form>


Powered & Developed by MIAH MOHAMMED AMAN
Studies at SCHOLARSHOME, Shahi Eidgah
 

