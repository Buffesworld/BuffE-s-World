# Home

### Downloads:
##### As they go down, they get more and more cursed   -- Also 1.16.5
###### Credit: [RebootGreen](https://mine.ly/RebootGreen.1) omg those textures....
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}
 .tabcontent {
  animation: fadeEffect 1s; /* Fading effect takes 1 second */
}

/* Go from zero to full opacity */
@keyframes fadeEffect {
  from {opacity: 0;}
  to {opacity: 1;}
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>
</head>
<body>

<div class="tab">
<button class="tablinks" onclick="openCity(event, 'Full Release')" id="defaultOpen">Full Release</button>
  <button class="tablinks" onclick="openCity(event, 'Beta')">Beta</button>
  <button class="tablinks" onclick="openCity(event, 'Alpha')">Alpha</button>
</div>

<div id="Full Release" id="defaultOpen" class="tabcontent">
  <p>None Yet :)</p>
</div>

<div id="Beta" class="tabcontent">
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv14%20(beta).jar?raw=true">Download Latest Beta</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv14%20(beta).jar?raw=true">Download v14</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv13%20(beta).jar?raw=true">Download v13</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv12%20(beta).jar?raw=true">Download v12</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv11%20(beta).jar?raw=true">Download v11</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv10%20(beta).jar?raw=true">Download v10</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv9%20(beta).jar?raw=true">Download v9</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv8%20(beta).jar?raw=true">Download v8</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv7%20(beta).jar?raw=true">Download v7</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv6%20(beta).jar?raw=true">Download v6</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv5%20(beta).jar?raw=true">Download v5</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv4.jar?raw=true">Download v4</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworldv3.jar?raw=true">Download v3</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buffeworld%20v2.jar?raw=true">Download v2</a><br>
 <br>
 <a href="https://github.com/Buffesworld/beta_mod_versions/blob/main/buff-e-world%20v1.jar?raw=true">Download v1</a><br>
 <br>
</div>

<div id="Alpha" class="tabcontent">
 <a href="https://www.youtube.com/embed/O91DT1pR1ew?autoplay=1&controls=0&modestbranding=1&disablekb=1&loop=1&fs=1&mouse=0&t=10">Download Final Alpha</a><br>
 <br>
 <a href="https://www.youtube.com/embed/O91DT1pR1ew?autoplay=1&controls=0&modestbranding=1&disablekb=1&loop=1&fs=1&mouse=0&t=10">Download v5</a><br>
 <br>
 <a href="https://www.youtube.com/embed/O91DT1pR1ew?autoplay=1&controls=0&modestbranding=1&disablekb=1&loop=1&fs=1&mouse=0&t=10">Download v4</a><br>
 <br>
 <a href="https://www.youtube.com/embed/O91DT1pR1ew?autoplay=1&controls=0&modestbranding=1&disablekb=1&loop=1&fs=1&mouse=0&t=10">Download v3</a><br>
 <br>
 <a href="https://www.youtube.com/embed/O91DT1pR1ew?autoplay=1&controls=0&modestbranding=1&disablekb=1&loop=1&fs=1&mouse=0&t=10">Download v2</a><br>
 <br>
 <a href="https://www.youtube.com/embed/O91DT1pR1ew?autoplay=1&controls=0&modestbranding=1&disablekb=1&loop=1&fs=1&mouse=0&t=10">Download v1</a><br>
 <br>
</div>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
 <script>
// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 

