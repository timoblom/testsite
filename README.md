

Siirry sisältöön
Gmail ja käyttö näytönlukuohjelmilla
Meet
Uusi kokous
Liity kokoukseen
Hangouts

Keskustelut
7,25 Gt / 15 Gt käytössä
Ehdot · Tietosuoja · Käytön säännöt
Viimeinen toiminta tällä tilillä: 28 minuuttia sitten
Tiedot
<!DOCTYPE html>
<html lang="en">
<title>Foundation of Web</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Raleway", sans-serif}
.w3-third img{margin-bottom: -6px; opacity: 0.8; cursor: pointer}
.w3-third img:hover{opacity: 1}
</style>
<body class="w3-light-grey w3-content" style="max-width:1600px">

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-bar-block w3-white w3-animate-left w3-text-grey w3-collapse w3-top w3-center" style="z-index:3;width:300px;font-weight:bold" id="mySidebar"><br>
  <h3 class="w3-padding-64 w3-center"><b>Ianna<br>Ilmonen</b></h3>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-padding w3-hide-large">CLOSE</a>
  <a href="#" onclick="w3_close()" class="w3-bar-item w3-button">PORTFOLIO</a> 
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT ME</a> 
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-white w3-xlarge w3-padding-16">
  <span class="w3-left w3-padding">Mysterious Unknown</span>
  <a href="javascript:void(0)" class="w3-right w3-button w3-white" onclick="w3_open()">☰</a>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px">

  <!-- Push down content on small screens --> 
  <div class="w3-hide-large" style="margin-top:83px"></div>
  
  <!-- Photo grid -->
  <div class="w3-row">
    <div class="w3-third">
      <img src="https://pixabay.com/get/g551ed17f5684575c2bacac6a735fe26940d984b668abb890439cc8b8333da79580337b339b60f1c8333a56742542b28f_640.png" style="width:100%" onclick="onClick(this)" alt="">
      <img src="https://pixabay.com/get/gb1afd0f7c49f52de930102f28359d0c00b21288a92401522061e6a66aca771fb52c2f849383fec3ac9a5b208774374326f63d757b154a236d512c68334a091fb_1280.jpg" style="width:100%" onclick="onClick(this)" alt="">
      <img src="https://pixabay.com/get/ga085e59e74676b315cb48db7301286b7ccb935f6a25285a2ac083ed1cc7f87e26a8073181324ce463ae95d6be742baa84de17f68dafc04822424d823b749f167_1920.jpg" style="width:100%" onclick="onClick(this)" alt="">
    </div>

    <div class="w3-third">
      <img src="https://pixabay.com/get/g742b422948e450d455df09506db7ff349e87798f7c9f750acdfd98a6f0b12918c2797f7afc56c1a3482fc446ce02dca4cf6f25397fbc49578f51dff5890954e1_1920.jpg" style="width:100%" onclick="onClick(this)" alt="">
      <img src="https://pixabay.com/get/g5b50e10158ff03455889eac9c8a31cf42980b4e8c762b9f688962cd61a5ba5bd0767c3d46161fc59aa58324a3c1d15977df18916dedeb35d7eb7d4829a021316_1920.jpg" style="width:100%" onclick="onClick(this)" alt="">
      <img src="https://pixabay.com/get/gba59c18ddd6b4b7240efd4f1c6aae255013a18165bec17417c391ee5dd5d7975b98bcf0b9e1bc5a4b1ce83fb8fa5c99a_1920.jpg" style="width:100%" onclick="onClick(this)" alt="">
    </div>
    
    <div class="w3-third">
      <img src="https://pixabay.com/get/gf6120ed4ccd104631cc3904ec1088c24b10f62a0399d8a57099b8771e058e13af47961bb55df94c9983ec1df4304828874d9f6eab1314ed40f0328415dded37d_1920.jpg" style="width:100%" onclick="onClick(this)" alt="">
      <img src="https://pixabay.com/get/gfe3a67786a3f6d84c2ddf27b0607dde58d4584307791209ed432377859de049fa19f3c9dc5da111049a1cbcddde9cd35a91d131ba62022e730e80dd0b000f92f_1920.jpg" style="width:100%" onclick="onClick(this)" alt="">
      <img src="https://pixabay.com/get/g41a86b0dcb3b29f2af46c93859575d7040edc29aee1ae06a913d1e9b34e52c8fecb4a8bfe6575a27305fbbadfa55577eeef0ae9413b2dbe310eaedc930e6d640_1920.jpg" style="width:100%" onclick="onClick(this)" alt="">
    </div>
  </div>

  <!-- Pagination -->
  <div class="w3-center w3-padding-32">
    <div class="w3-bar">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  </div>
  
  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>

  <!-- About section -->
  <div class="w3-container w3-dark-grey w3-center w3-text-light-grey w3-padding-32" id="about">
    <h4><b>About Me</b></h4>
    <img src="https://pixabay.com/get/g995330195e28c45994879cce2b76c87a25db419ae3ead3f1b8b73900ffe96eb8d837d1d261e79fb209360182b140e7d3.jpg" alt="Me" class="w3-image w3-padding-32" width="600" height="650">
    <div class="w3-content w3-justify" style="max-width:600px">
      <h4>My Name</h4>
      <p>Some text about me. I love taking photos of PEOPLE. I am lorem ipsum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure
        dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor
        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </p>
      <p>mail: example@example.com</p>
      <p>tel: 5353 35531</p>
      <hr class="w3-opacity">
      <h4 class="w3-padding-16">Technical Skills</h4>
      <p class="w3-wide">Photography</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:95%">95%</div>
      </div>
      <p class="w3-wide">Web Design</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:85%">85%</div>
      </div>
      <p class="w3-wide">Photoshop</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:80%">80%</div>
      </div>
      <p><button class="w3-button w3-light-grey w3-padding-large w3-margin-top w3-margin-bottom">Download Resume</button></p>
      <hr class="w3-opacity">

      <h4 class="w3-padding-16">How much I charge</h4>
      <div class="w3-row-padding" style="margin:0 -16px">
        <div class="w3-half w3-margin-bottom">
          <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
            <li class="w3-black w3-xlarge w3-padding-32">Basic</li>
            <li class="w3-padding-16">Web Design</li>
            <li class="w3-padding-16">Photography</li>
            <li class="w3-padding-16">5GB Storage</li>
            <li class="w3-padding-16">Mail Support</li>
            <li class="w3-padding-16">
              <h2>$ 10</h2>
              <span class="w3-opacity">per month</span>
            </li>
            <li class="w3-light-grey w3-padding-24">
              <button class="w3-button w3-white w3-padding-large">Sign Up</button>
            </li>
          </ul>
        </div>
        
        <div class="w3-half">
          <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
            <li class="w3-black w3-xlarge w3-padding-32">Pro</li>
            <li class="w3-padding-16">Web Design</li>
            <li class="w3-padding-16">Photography</li>
            <li class="w3-padding-16">50GB Storage</li>
            <li class="w3-padding-16">Endless Support</li>
            <li class="w3-padding-16">
              <h2>$ 25</h2>
              <span class="w3-opacity">per month</span>
            </li>
            <li class="w3-light-grey w3-padding-24">
              <button class="w3-button w3-white w3-padding-large">Sign Up</button>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- Contact section -->
  <div class="w3-container w3-light-grey w3-padding-32 w3-padding-large" id="contact">
    <div class="w3-content" style="max-width:600px">
      <h4 class="w3-center"><b>Contact Me</b></h4>
      <p>Do you want me to photograph you? Fill out the form and fill me in with the details :) I love meeting new people!</p>
      <form action="/action_page.php" target="_blank">
        <div class="w3-section">
          <label>Name</label>
          <input class="w3-input w3-border" type="text" name="Name" required>
        </div>
        <div class="w3-section">
          <label>Email</label>
          <input class="w3-input w3-border" type="text" name="Email" required>
        </div>
        <div class="w3-section">
          <label>Message</label>
          <input class="w3-input w3-border" type="text" name="Message" required>
        </div>
        <button type="submit" class="w3-button w3-block w3-black w3-margin-bottom">Send Message</button>
      </form>
    </div>
  </div>

  <!-- Footer -->
  <footer class="w3-container w3-padding-32 w3-grey">  
    <div class="w3-row-padding">
      <div class="w3-third">
        <h3>INFO</h3>
        <p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>      
      </div>
    
      <div class="w3-third">
        <h3>BLOG POSTS</h3>
        <ul class="w3-ul">
          <li class="w3-padding-16 w3-hover-black">
            <img src="https://pixabay.com/get/g05832b91606a43c95d0a89690842682263cb71180b12d4772c9ecaf78d07fc64c2dc600451a676f2780762cf0e61716cdaba53221a0a68dffe21c1c1e1978c5d_1920.jpg" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Lorem</span><br>
            <span>Sed mattis nunc</span>
          </li>
          <li class="w3-padding-16 w3-hover-black">
            <img src="https://pixabay.com/get/gfb0c998386a838e1bf048b65ad27894582dd4c8d1d0eec8a556ae4f8e3752bbf719fbdc9305359b6d80c392c0fe08abe7dfcc38b6ea3d8aef367e64493a6a1f8_1920.jpg" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Ipsum</span><br>
            <span>Praes tinci sed</span>
          </li> 
        </ul>
      </div>

      <div class="w3-third">
        <h3>POPULAR TAGS</h3>
        <p>
          <span class="w3-tag w3-black w3-margin-bottom">Travel</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">New York</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">London</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">IKEA</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">NORWAY</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">DIY</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Ideas</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Baby</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Family</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">News</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Clothing</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Shopping</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Sports</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Games</span>
        </p>
      </div>
    </div>
  </footer>
  
  <div class="w3-black w3-center w3-padding-24">Foundation of Web <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity">Ianna Ilmonen</a></div>

<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

</script>


</body>
</html>
codes.txt
Näytetään codes.txt.
