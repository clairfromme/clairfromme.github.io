<!DOCTYPE html>
<html>

<head>
  <title>W3.CSS Template</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link href="clairfrommeportfolio2.css" rel="stylesheet" type="text/css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
    integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
    integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
    crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
    integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
    crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
    integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
    crossorigin="anonymous"></script>
</head>

<body>

  <!-- Navbar (sit on top) -->
  <div class="w3-top">
    <div class="w3-bar w3-card w3-animate-top w3-white" id="myNavbar">
      <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium
          w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
        <i class="fa fa-bars"></i>
      </a>
      <a href="#home" class="w3-bar-item w3-button">HOME</a>
      <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a>
      <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> PORTFOLIO</a>
      <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>

      </a>
    </div>

    <!-- Navbar on small screens -->
    <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large
      w3-hide-medium">
      <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
      <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">PORTFOLIO</a>
      <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
      <a href="#" class="w3-bar-item w3-button">SEARCH</a>
    </div>
  </div>


  <!-- First Parallax Image with Logo Text -->

  <div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
    <div class="w3-display-middle" style="white-space:nowrap;">
      <span class="w3-center w3-padding-large w3-black w3-xxlarge w3-wide
        w3-animate-opacity">CLAIR <span class="w3-hide-small">FROMME</span>
    </div>
  </div>



  <!-- Container (About Section) -->
  <div class="w3-content w3-container w3-padding-64" id="about">
    <h3 class="w3-center">ABOUT ME</h3>
    <p class="w3-center"><em>2020 Architecture Graduate</em></p>
    <p>Hello, welcome to my website! I am a recent Architecture graduate from
      Dalhousie University. My standout skills include; strong verbal
      communication and customer service skills, creative and artistic
      abilities, logical problem solving, and the ability to learn quickly. I
      am interested in multiple facets of design. In particular, I would love
      to learn more about graphic design, web design, and UX/UI design.
    </p>
    <div class="w3-row">
      <div class="w3-col m6 w3-center w3-padding-large">
        <p><b><i class="fa fa-user w3-margin-right"></i>Clair Fromme</b></p><br>
        <img src="me.JPG" class="w3-round w3-image
            w3-opacity w3-hover-opacity-off" alt="Photo of Me" width="500" height="333">

        <div class="text-left ">
        <div class="padding-40"></div>
        <span class="w3-large">Extracurricular</span>
          <div class="padding-10"></div>
          <p1>CASA (Canadian Architecture Student Association) Undergrad Rep for
            Dalhousie May 2019 - January 2020.</p1>
          <p>Roles: Post for and manage CASA's Instagram. Manage student
            relations. Attend DASA and communication committee meetings.</p>
          <p4>UNBC Women's Centre Volunteer September 2016 - April 2017.</p4>
          <p>Roles: Provide support services for women. Maintain the cleanliness
            of the center.</p>
          <span class="w3-large">References</span>
          <div class="padding-10"></div>
          <p4>Bob Lilly, BLA, BCSLA, CSLA</p4>
          <p>Principal, Landscape Architect
            P: 604-306-0674</p>
          <p4>Darin Postulo</p4>
          <p>Manager at Princess Auto
            P: 604-777-0735</p>
          <p4>Luke deBruijn, M.Eng., E.I.T.</p4>
          <p>Project Engineer
            604-992-6420</p>
        </div>
      </div>






      <!-- Hide this text on small devices -->
      <div class="w3-col m6 w3-hide-small w3-padding-large">
        <div class="padding-55"></div>
        <span class="w3-large">Education</span>
        <div class="padding-10"></div>
        <p>Bachelor's of Environmental Design Dalhousie University Graduated
          April 2020. </p>
        <span class="w3-large">Work Experience</span>
        <div class="padding-10"></div>
        <p4> Architecture Co-op Student
          Attentus Landscape Architecture September 2019 - December 2019.</p4>
        <p>Tasks: Created a "Working Farm", Golfcourse conversion project
          proposal.
          Drafted site plan and section markups in AutoCAD. Photographed and
          converted paper architectural drawings to a digital format.
        </p>
        <p4>Office Administrator Fromme Engineering Ltd. May 2018 - August
          2018.</p4>
        <p>Tasks: Communicated with clients via phone and email. Drafted and
          sent marketing booklets to potential clients. Created invoices and
          followed up with outstanding balances. Converted over twenty years
          of paper engineering documentation to a digital format.</p>
        <p4>Cashier at Princess Auto May 2017 - December 2017.</p4>
        <p>Tasks: Assisted customers with the purchasing of merchandise and
          the location of products within our store. Created unique displays
          for storewide promotional events. Stocked and organized merchandise.</p>
        <p4>Deli Staff at Independent Foods May 2016 - September 2016.</p4>
        <p>Tasks: Prepared and restocked food products. Assisted customers
          with deli meat and cheese selection. Cleaned and closed the deli.
          Ordered food from vendors to fulfill customer requests. </p>


      </div>

    </div>
    <p class="w3-large w3-center w3-padding-16">Skills Include:</p>
    <p class="w3-wide"><i class="fa fa-laptop"></i>Illustrator</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:70%">70%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-laptop"></i>Photoshop</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:65%">65%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-laptop"></i>InDesign</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:60%">60%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-laptop"></i>AutoCAD</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:70%">70%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-laptop"></i>Rhino</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:40%">40%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-laptop"></i>HTML</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:20%">20%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-laptop"></i>CSS</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:20%">20%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-photo"></i>Hand Modeling</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:40%">40%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-photo"></i>Hand Drawing</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:75%">75%</div>
    </div>
    <p class="w3-wide"><i class="fa fa-camera"></i>Photography</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:30%">30%</div>
    </div>
  </div>
  </div>


  <div class="w3-row w3-center w3-mycoral w3-padding-16 w3-opacity
      w3-hover-opacity-off">

    <div class="w3-quarter w3-section">
      <span class="w3-xlarge"></span><br>

    </div>
  </div>

  <!-- Second Parallax Image with Portfolio Text -->
  <div class="bgimg-2 w3-display-container w3-opacity-min">
    <div class="w3-display-middle">
      <span class="w3-xxlarge w3-text-mycoral w3-wide">PORTFOLIO</span>
    </div>
  </div>

  <!-- Container (Portfolio Section) -->
  <div class="w3-content w3-container w3-padding-64" id="portfolio">
    <h3 class="w3-center">MY WORK</h3>
    <p class="w3-center w3-mygrey"><em>Here is some of my favourite work.
        <br> Click on the arrows or wait for the carousel.</em></p><br>
    <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
    <div class="container">
      <div class="w-100 h-100">
        <div class="carousel slide" id="carouselExample" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExample" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExample" data-slide-to="1"></li>
            <li data-target="#carouselExample" data-slide-to="2"></li>
            <li data-target="#carouselExample" data-slide-to="3"></li>
            <li data-target="#carouselExample" data-slide-to="4"></li>
            <li data-target="#carouselExample" data-slide-to="5"></li>
            <li data-target="#carouselExample" data-slide-to="6"></li>
            <li data-target="#carouselExample" data-slide-to="7"></li>
            <li data-target="#carouselExample" data-slide-to="8"></li>
            <li data-target="#carouselExample" data-slide-to="9"></li>
            <li data-target="#carouselExample" data-slide-to="10"></li>
            <li data-target="#carouselExample" data-slide-to="11"></li>
            <li data-target="#carouselExample" data-slide-to="12"></li>
            <li data-target="#carouselExample" data-slide-to="13"></li>
            <li data-target="#carouselExample" data-slide-to="14"></li>
            <li data-target="#carouselExample" data-slide-to="15"></li>
            <li data-target="#carouselExample" data-slide-to="16"></li>
            <li data-target="#carouselExample" data-slide-to="17"></li>
            <li data-target="#carouselExample" data-slide-to="18"></li>
            <li data-target="#carouselExample" data-slide-to="19"></li>
            <li data-target="#carouselExample" data-slide-to="20"></li>
            <li data-target="#carouselExample" data-slide-to="21"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="SITE_PLAN_W-H_DESIGN_STATEMENT.jpg" alt="First Slide" class="d-block w-100 h-100">
              <div class="carousel-caption d-none d-md-block">
                <h5>BATHHOUSE SITE PLAN</h5>
                <p5> Bathhouse on Halifax's Waterfront</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="boaredwalk_render_fixed_copy.jpg" alt="Second Slide" class="d-block w-100 h-100">
              <div class="carousel-caption d-none d-md-block">
                <h5>BOARDWALK RENDER</h5>
                <p5>Bathhouse on the Boardwalk</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="ISO_SW_Render.jpg" alt="Third Slide" class="d-block w-100 h-100">
              <div class="carousel-caption d-none d-md-block">
                <h5>SOUTHWEST ISOMETRIC RENDER</h5>
                <p5>Bathhouse in an Isometric View</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="Vignette_small_change.jpg" alt="Fourth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption d-none d-md-block">
                <h5>VIGNETTE</h5>
                <p5>Vignette of the Large Change Room</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="vignette _big_change.jpg" alt="Fifth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption d-none d-md-block">
                <h5>VIGNETTE</h5>
                <p5>Vignette of the Small Change Room</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="Large_Sauna_Vignette.jpg" alt="Sixth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption d-none d-md-block">
                <h5>VIGNETTE</h5>
                <p5>Vignette of the Large Sauna</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="Wall_Section_June_21st.png" alt="Seventh Slide" class="d-block w-100 h-100">
              <div class="carousel-caption7 d-none d-md-block">
                <h5>Wall Section</h5>
                <p5>June 21st Large Sauna Wall Section</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="Wall_Section_Dec_21st.png" alt="Eighth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption8 d-none d-md-block">
                <h5>Wall Section</h5>
                <p5>Dec 21st Large Sauna Wall Section</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="Rep2-01.png" alt="Ninth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption9 d-none d-md-block">
                <h5>Shadow Play</h5>
                <p5>Exploring Shadows, Sound, and Circulation as an
                  Architectural Element</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="Rep_2b_Poster-01.png" alt="Tenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption10 d-none d-md-block">
                <h5>Colour Play</h5>
                <p10>Colour and the Intersection of Circulation</p10>
              </div>
            </div>
            <div class="carousel-item">
              <img src="burnham_sketch.jpg" alt="Eleventh Slide" class="d-block w-100 h-100">
              <div class="carousel-caption d-none d-md-block">
                <h5>Burnham Pavilion</h5>
                <p5>Sketch of the Burnham Pavillion</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="bunham_model .png" alt="Twelfth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption12 d-none d-md-block">
                <h5>Burnham Pavilion Model</h5>
                <p10>Model made by Clair Fromme and Kathleen McMahon</p10>
              </div>
            </div>
            <div class="carousel-item">
              <img src="finalmodel2copy.jpg" alt="Thirteenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption13 d-none d-md-block">
                <h5>Assembly Centre Model</h5>
                <p5>Performance Stage and Outdoor Gathering Space</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="finalmodel3copy.jpg" alt="Fourteenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption14 d-none d-md-block">
                <h5>Assembly Centre Model</h5>
                <p5>Performance Stage and Underground Entrance</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="finalmodel1.jpg" alt="Fifteenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption15 d-none d-md-block">
                <h5>Assembly Centre Model</h5>
                <p5>Main Assembly Hall and Ramp to the Underground Cafe</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="fullviewsidepng.jpg" alt="Sixteenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption16 d-none d-md-block">
                <h5>Five Stages of Grief Model</h5>
                <p5>Side View of the Five Stages Pavilion</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="anger2.png" alt="Seventeenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption17 d-none d-md-block">
                <h5>Five Stages of Grief Model</h5>
                <p5>Erratic Walls Representing Anger</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="bargining2copy.png" alt="Eighteenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption18 d-none d-md-block">
                <h5>Five Stages of Grief Model</h5>
                <p5>Glass Building Looking Back, Representing Bargaining</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="acceptancecopy.png" alt="Nineteenth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption19 d-none d-md-block">
                <h5>Five Stages of Grief Model</h5>
                <p5>The Walls Have Disappeared and the Ground is Flat,
                  Representing Acceptance</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="coloured_smoke_shack.png" alt="Twentieth Slide" class="d-block w-100 h-100">
              <div class="carousel-caption20 d-none d-md-block">
                <h5>Smoke Shack</h5>
                <p5>Illustration of an Abandoned Smoke Shack</p5>
              </div>
            </div>
            <div class="carousel-item">
              <img src="mom.jpg" alt="Twenty-first Slide" class="d-block w-100 h-100">
              <div class="carousel-caption21 d-none d-md-block">
                <h5>Portrait</h5>
                <p10>Personal Portrait of Grief</p10>
              </div>
            </div>
            <div class="carousel-item">
              <img src="Resume_June_2020_copy.jpg" alt="Twenty-second Slide" class="d-block w-100 h-100">
              <div class="carousel-caption22 d-none d-md-block">
                <h5>Resume</h5>

              </div>
            </div>
          </div>
          <a href="#carouselExample" class="carousel-control-prev" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a href="#carouselExample" class="carousel-control-next" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>

    <div class="w3-padding-64"></div>
  </div>

  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-white" onclick="this.style.display='none'">
    <span class="w3-button w3-large w3-white w3-display-topright" title="Close Modal Image"><i
        class="fa fa-remove"></i></span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent
        w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption" class="w3-opacity w3-large"></p>
    </div>
  </div>

  <!-- Third Parallax Image with Portfolio Text -->
  <div class="bgimg-3 w3-display-container w3-opacity-min">
    <div class="w3-display-middle">
      <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
    </div>
  </div>

  <!-- Container (Contact Section) -->
  <div class="w3-content w3-container w3-padding-64" id="contact">
    <h3 class="w3-center">LOCATION AND CONTACT</h3>
    <p class="w3-center w3-mygrey"><em>I'd love your feedback!</em></p>

    <div class="w3-row w3-padding-32 w3-section">
      <div class="w3-col m4 w3-container">
        <img src="./Main_protest_photo.jpeg" class="w3-image w3-round" style="width:100%">
      </div>
      <div class="w3-col m8 w3-panel">
        <div class="w3-large w3-margin-bottom">
          <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge
              w3-margin-right"></i> Vancouver, BC<br>
          <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge
              w3-margin-right"></i> Phone: 778-952-4627<br>
          <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge
              w3-margin-right"></i> Email: cffliveca40@gmail.com<br>
        </div>

        <form action="/action_page.php" target="_blank">
          <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
            </div>
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
            </div>
          </div>
          <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
          <button class="w3-button w3-black w3-right w3-section" type="submit">
            <i class="fa fa-paper-plane"></i> SEND MESSAGE
          </button>
        </form>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="w3-center w3-black w3-padding-64 w3-opacity
      w3-hover-opacity-off">
    <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up
          w3-margin-right"></i>To the top</a>
    <div class="w3-xlarge w3-section">
      <i class="fa fa-facebook-official w3-hover-opacity"></i>
      <i class="fa fa-instagram w3-hover-opacity"></i>
      <i class="fa fa-snapchat w3-hover-opacity"></i>
      <i class="fa fa-pinterest-p w3-hover-opacity"></i>
      <i class="fa fa-twitter w3-hover-opacity"></i>
      <i class="fa fa-linkedin w3-hover-opacity"></i>
    </div>
    <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank"
        class="w3-hover-text-green">w3.css</a></p>
  </footer>

  <script>
    // Modal Image Gallery
    function onClick(element) {
      document.getElementById("img01").src = element.src;
      document.getElementById("modal01").style.display = "block";
      var captionText = document.getElementById("caption");
      captionText.innerHTML = element.alt;
    }

    // Change style of navbar on scroll
    window.onscroll = function () { myFunction() };
    function myFunction() {
      var navbar = document.getElementById("myNavbar");
      if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
      } else {
        navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
      }
    }

    // Used to toggle the menu on small screens when clicking on the menu button
    function toggleFunction() {
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
