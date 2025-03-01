### Index.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" contect="IE-edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Personal Portfolio Website - Understanding Tutorials</title>
    <link rel="stylesheet" href="styles.css" />
    <script src="https://kit.fontawesome.com/93dd7fcf78.js" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="header">
      <div class="container">
        <nav>
          <img src="images/logo.png" class="log0" />
          <ul id="sodemenu">
            <li><a href="#header">Home</a></li>
            <li><a href="#header-text">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#Contact">Contact</a></li>
            <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
          </ul>
          <i class="fa-solid fa-bars" onclick="openmenu()"></i>
        </nav>
        <div class="header-text">
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          
          <h6>Wed designer</h6>
          <h1>Hi, I'm <span>Mounika</span> <br />from Hyderabad</h1>
        </div>
      </div>
    </div>
    <!------about------>
    <div id="header-text">
      <div class="container">
        <div class="row">
          <div class="about-col-1">
            <img src="images/Mounika.png" />
          </div>
          <div class="about-col-2">
            <h1 class="sub-title">About Me</h1>
            <p>
              Seeking a beginner role to enhance and explore my technical knowledge gained at Institute of Aeronautical Engineering Collage (IARE) in the last three years. I hold a B.Tech degree from IARE college and won the quiz,debate,art,coding challenge held at the campus. I'm much like talented in the art making and graphic designing, wed application designing and ecthical hacking, etc.
            </p>
            <div class="tab-titles">
              <p class="tab-links active-link" onclick="opentab('skills')">
                Skills
              </p>
              <p class="tab-links" onclick="opentab("certifications")">
                Certifications
              </p>
              <p class="tab-links" onclick="opentab("education")">Education</p>
            </div>
            <div class="tab-contents active-tab" id="Skills">
              <ul>
                <li><span>Web development</span><br />Designing Wed page</li>
                <li>
                  <span>Ethical Hacking</span><br />Beginner skills on the security
                </li>
                <li>
                  <span>Graphic desiging</span><br />Designing amazing grapic
                  designs
                </li>
              </ul>
            </div>
            <div class="tab-contents" id="Certificstions">
              <ul>
                <li><span>2021</span><br />Advent of cyber 2021 - TryHackMe</li>
                <li>
                  <span>2022</span><br />Advent of cyber 2022 - TryHackMe<br />
                  Got certified by the Codechef in Python<br />
                  Got course completion certificate of IOT201 in Infosys
                </li>
                <li>
                  <span>2022 - 2023</span><br />Got certified by <br />
                  AWS cloud testing <br />
                  AWS security Fundamentals<br>
                  Ethical hacking 201 <br />
                  AI development
                </li>
              </ul>
            </div>
            <div class="tab-contents" id="Education">
                <ul>
                  <li><span>2021</span><br />Get into IARE collage for specilization in CYBER SECURITY</li>
                  <li><span>2022</span><br />Completed full internship on Cyber security<br />
                                          Completed python programming languag</li>
                  <li><span>2022 - 2023</span><br />Wed application development successful<br>
                                          Application programming running</li>
                </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!------services-->
    <div id="services">
      <div id="container">
        <h1 class="sub-title">My Services</h1>
        <div class="services-list">
          <div>
            <i class="fa-solid fa-code"></i>
            <h2>Web Design</h2>
            <p>Web design is the process of creating visually engaging and user-friendly websites, incorporating elements like layout, typography, and imagery to deliver a compelling digital experience. It focuses on enhancing user interactions and optimizing the overall aesthetic appeal of a website.</p>
            <a href="#">Learn More</a>
          </div>
          <div>
              <i class="fa-solid fa-hat-cowboy"></i>
              <h2>Ethical Hacking</h2>
              <p>Ethical hacking, also known as penetration testing, is the practice of systematically probing computer systems and networks to identify and rectify security vulnerabilities. Ethical hackers work to protect digital assets by identifying weaknesses before malicious hackers can exploit them.<a href="#">Learn More</a>
            </div>
            <div>
                <i class="fa-solid fa-brush"></i>
                <h2>Graphic Design</h2>
                <p>Graphic design is the art of creating visual content to communicate messages and ideas effectively. It involves the use of typography, imagery, and layout to convey information, enhance branding, and captivate audiences through various mediums.</p>
                <a href="#">Learn More</a>
            </div>
        </div>
      </div>
    </div>
    <!------portfolio-->
    <div id="portfolio">
      <div id="container">
        <h1 class="sub-title">My Work</h1>
        <div class="work-list">
          <div class="work">
            <img src="images/wed des.jpg" width="70" height="400">
            <div class="layer">
              <h3>HTML, CSS and JS</h3>
              <p>Web design is the art of creating visually appealing and user-friendly websites that engage, captivate visitors, color schemes to convey desired message effectively.</p>
              <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
            </div>
          </div>
          <div class="work">
              <img src="images/ethihack.jpg" width="70" height="400">
              <div class="layer">
                <h3>Security Test</h3>
                <p>Ethical hacking, also known as white-hat hacking, involves identifying & addressing security vulnerabilities within computer system networks.</p>
                <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
              </div>
          </div>
          <div class="work">
              <img src="images/graph.jpg" width="70" height="400">
              <div class="layer">
                <h3>visual communication design</h3>
                <p>Graphic design is the creative process of using visual elements, imagery to convey ideas and messages effectively.</p>
                <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
              </div>
          </div>
        </div>
      <a href="#" class="btn">See more</a>
      </div>
    </div>
    <!----contact-->
    <div id="Contact">
      <div class="container">
        <div class="row">
          <div class="contact-left">
            <h1 class="sub-title">contact Me</h1>
            <p><i class="fa-brands fa-telegram"></i>contact@example.com</p>
            <p><i class="fa-solid fa-square-phone"></i>0123456789</p>
            <div class="social-icons">
              <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
              <a href="#"><i class="fa-brands fa-instagram"></i></a>
              <a href="#"><i class="fa-brands fa-linkedin"></i></a>
              <a href="#"><i class="fa-brands fa-github"></i></a>
            </div>
            <a href="images/my-cv.pdf" download class="btn btn2">Download CV</a>
          </div>
          <div class="contact-right">
            <form name="submit-to-google-sheet">
              <input type="text" name="Name" placeholder="Your Name" required>
              <input type="email" name="email" placeholder="Your Email" required>
              <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
              <button type="submit" class="btn btn2">Submit</button>
            </form>
          </div>
        </div>
      </div>
      <div class="copyright">
        <p>Copyright @mounika. Made with<i class="fa-solid fa-heart"></i> by understanding tutorials</p>
      </div>
    </div>

    <script>
          var tablinks = document.getElementById("tab-link");
          var tabcontents = document.getElementById("tab-content");
      
          function opentab(tabname) {
            for (let tablink of tablinks) {
              tablink.classList.remove("active-link");
            }
            for (let tabcontent of tabcontents) {
              tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classlist.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
          }
    </script>
    <script>

      var sidemenu = document.getElementById("sidemenu");

      function openmenu(){
        sidemenu.style.right = "0";
      }
      function closemenu(){
        sidemenu.style.right = "-200px";
      }

      <script>
          const scriptURL = '<https://script.google.com/macros/s/AKfycbyVd-qF1Vo99SC9P7L43l3gO197QbSqaoes9rFu2FgtMdIm9tH5JwMcyeLiGwUpfyOF/exec>'
          const form = document.forms['submit-to-google-sheet']

          form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
          .then(response => console.log('Success!', response))
          .catch(error => console.error('Error!', error.message))
          })
      </script>
  
  </body>
</html>




### styles.css

* {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}
body {
  background: #080808;
  color: #fff;
}
#header {
  width: 100%;
  height: 100vh;
  background-image: url(images/images.jpg);
  background-size: cover;
  background-position: none;
  background-color: #080808;
}
.container {
  padding: 10px 10%;
}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

.logo {
  width: 140px;
}

nav ul li {
  display: inline-block;
  list-style: none;
  margin: 10px 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 18px;
  position: relative;
}

nav ul li a::after {
  content: "";
  width: 0;
  height: 3px;
  background: #ff004f;
  position: absolute;
  left: 0;
  bottom: -6px;
  transition: 2s;
}

nav ul li a:hover::after {
  width: 100%;
}

.header-text {
  margin-top: 20px;
  font-size: 30px;
}

.header-text h1 {
  font-size: 60px;
  margin-top: 20px;
}

.header-text h1 span {
  color: #ff004f;
}

/*------about--------*/
#about {
  padding: 80px 0;
  color: #ababab;
}
.row {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.about-col-1 {
  flex-basis: 35%;
}

.about-col-1 img {
  width: 100%;
  border-radius: 15px;
}

.about-col-2 {
  flex-basis: 60%;
}

.sub-title {
  font-size: 60px;
  font-weight: 600;
  color: #fff;
}

.tab-titles {
  display: flex;
  margin: 20px 0 40px;
}

.tab-links {
  margin-right: 50px;
  font-size: 18px;
  font-weight: 500;
  cursor: pointer;
  position: relative;
}

.tab-links::after {
  content: "";
  width: 0;
  height: 3px;
  background: #ff004f;
  position: absolute;
  left: 0;
  bottom: -8px;
  transition: background 0.5s transform 0.5s;
}

.tab-links.active-link::after {
  width: 50%;
}

.tab-contents ul li {
  list-style: none;
  margin: 10px 0;
}

.tab-contents ul li span {
  color: #b54769;
  font-size: 14px;
}

.tab-contents {
  display: none;
}

.tab-contents.active-tab {
  display: block;
}

/*----services----*/
#services {
  padding: 10px 0;
}

.sub-title {
  padding: 30px 10%;
}

.services-list {
  padding: 10px 10%;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 40px;
  margin-top: 50px;
}

.services-list div {
  background: #262626;
  padding: 40px;
  font-size: 13px;
  font-weight: 300;
  border-radius: 10px;
  transition: background 0.5s transform 0.5s;
}

.services-list div i {
  font-size: 50px;
  margin-bottom: 30px;
}

.services-list div h2 {
  font-size: 30px;
  font-weight: 500;
  margin-bottom: 15px;
}

.services-list div a {
  text-decoration: none;
  color: #fff;
  font-size: 12px;
  margin-top: 20px;
  display: inline-block;
}

.services-list div:hover {
  background: #ff004f;
  transform: translateY(-10px);
}

/*-----portflio---*/
#portfolio {
  padding: 50px 0;
}
.work-list {
  padding: 30px 10%;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 40px;
  margin-top: 50px;
}
.work {
  border-radius: 10px;
  position: relative;
  overflow: hidden;
}
.work img {
  width: 100%;
  border-radius: 10px;
  display: block;
  transition: transform 0.5s;
}
.layer {
  width: 100%;
  height: 0;
  background: linear-gradient(rgba(0, 0, 0, 0.6), #ff004f);
  border-radius: 10px;
  position: absolute;
  left: 0;
  bottom: 0;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 0 40px;
  text-align: center;
  transition: height 0.5s;
}
.layer h3 {
  font-weight: 500;
  margin-bottom: 20px;
}
.layer a {
  margin-top: 20px;
  color: #ff004f;
  text-decoration: none;
  font-size: 18px;
  line-height: 60px;
  background: #fff;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  text-align: center;
}
.work:hover img {
  transform: scale(1.1);
}
.work:hover .layer {
  height: 100%;
}
.btn {
  text-decoration: none;
  display: block;
  margin: 50px auto;
  width: fit-content;
  border: 1px solid #ff004f;
  padding: 14px 50px;
  border-radius: 6px;
  color: #fff;
  transition: background 0.5s;
}
.btn:hover {
  background: #ff004f;
}
/*-----contat---*/
.contact-left {
  flex-basis: 25%;
}
.contact-right {
  flex-basis: 60%;
}
.contact-left p {
  margin-top: 30px;
}
.contact-left p i {
  color: #ff004f;
  margin-right: 15px;
  font-size: 25px;
}
.social-icons {
  margin-top: 30px;
}
.social-icons a {
  text-decoration: none;
  font-size: 30px;
  margin-right: 15px;
  color: #ababab;
  display: inline-block;
  transition: transform 0.5s;
}
.social-icons a:hover {
  color: #ff004f;
  transform: translateY(-5px);
}
.btn.btn2 {
  display: inline-block;
  background: #ff004f;
}
.contact-rignt form {
  width: 100%;
}
form input,
form textarea {
  width: 100%;
  border: 0;
  outline: none;
  background: #262626;
  padding: 15px;
  margin: 15px 0;
  color: #fff;
  font-size: 18px;
  border-radius: 6px;
}
form .btn2 {
  padding: 14px 60px;
  font-size: 18px;
  margin-top: 20px;
  cursor: pointer;
}
.copyright {
  width: 100%;
  text-align: center;
  padding: 25px 0;
  background: #262626;
  font-weight: 300;
  margin-top: 20px;
}
.copyright i {
  color: #ff004f;
}

/*-----css for small screens---*/
nav .fas {
  display: none;
}

@media only screen and (max-width: 600px) {
  #header {
    background-image: url(images/images.jpg);
  }
  .header-text {
    margin-top: 100%;
    font-size: 16px;
  }
  .header-text h1 {
    display: block;
    font-size: 25px;
  }
  nav ul {
    background: #ff004f;
    position: fixed;
    top: 0;
    right: -200px;
    width: 200px;
    height: 100vh;
    padding-top: 50px;
    z-index: 2;
  }
  nav ul li {
    display: block;
    margin: 25px;
  }
  nav ul .fas {
    position: absolute;
    top: 25px;
    left: 25px;
    cursor: pointer;
  }
  .sub-title {
    font-size: 40px;
  }
  .about-col-1,
  .about-col-2 {
    flex-basis: 100%;
  }
  .about-col-1 {
    margin-bottom: 30px;
  }
  .about-col-2 {
    font-size: 14px;
  }
  .tab-links {
    font-size: 16px;
    margin-right: 20px;
  }
  .contact-left,
  .contact-right {
    flex-basis: 100%;
  }
  .copyright {
    font-size: 14px;
  }
}
