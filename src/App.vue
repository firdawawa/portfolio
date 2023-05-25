<script setup>
  import { ref } from 'vue'

  const containerClass = ref('container')
</script>

<template>
    <div :class="containerClass">
      <div class="header">
      <img class="logo" src="./assets/logo.png" alt="Logo">
      <div class="nav-head">
        <a id="ahead" href="#body">About Me</a>
        <a id="ahead" href="#portfolio">Portfolio</a>
        <a id="ahead" href="#contact">Contact</a>
      </div>  
    </div>

    <div class="body-container">
    <div class="body" id="body">
      <div id="aboutme">
        <div class="namepict">
          <div class="namedesc">
            <div class="nama">FIRDAUSI BAIQ ARDANA</div>
            <h5>Undergraduate student majoring Information Technology in Brawijaya University. Having interest in tech especially design. Participate actively in college activity, but still holding on academic class greatly. Able to hold perfectly on problem solving, meticulous, ardent, and critical thinking.</h5>
          </div>
          <img class="foto-profil" src="./assets/profil.png" alt="Profile">
        </div>
        <div class="skill">
          <div class="skillhead">Skill</div>
          <div class="skilldesc">
            <div class="skillleft">
              <h5>Design Thinking</h5>
              <h5>UX Research</h5>
              <h5>Designing</h5>
              <h5>Prototyping</h5> 
            </div>
            <div class="skillright">
              <h5>Wireframe</h5>
              <h5>HTML/CSS</h5> 
              <h5>Basic JavaScript</h5> 
            </div> 
          </div>
        </div>
        <div class="experience">
          <div class="head">Experience</div>
            <div class="tabel-container">
              <table>
                <tr class="table-content"><td>RAION</td></tr>
                <tr class="table-content"><td>RAION</td></tr>
                <tr class="table-content"><td>Nuri</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>UI/UX App Designer</td></tr>
                <tr class="table-content"><td>UI/UX App Designer Intern</td></tr>
                <tr class="table-content"><td>UI/UX Designer</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
                <tr class="table-content"><td>|</td></tr>
              </table>
              <table>
                <tr class="table-content"><td>April 2023 - Present</td></tr>
                <tr class="table-content"><td>March - April 2023</td></tr>
                <tr class="table-content"><td>January 2023</td></tr>
              </table>
            </div>
          </div>
        </div>

      <div id="portfolio">
        <div class="port-container">
          <div class="porthead">Portfolio</div>
          <div class="sharejoy">
            <div class="sharehead">
              <img class="sharelogo" src="./assets/sharejoy.png" alt="ShareJoy">
              <div class="sharetitle">ShareJoy</div>
            </div>
            <div class="share-content">
              <h5>Social purpose platform that allows the user to donate money or things. With main target user for teenagers and millennials, to rise their social empathy with others. Beside that, this app can help them who have struggle with unused things the have to bring more goodness through donation.</h5>
              <img class="phoneshare" src="./assets/dev1.png" alt="phone sharejoy">
            </div>
            <div class="shareui">
              <img class="shareuides" src="./assets/shareui1.png">
              <img class="shareuides" src="./assets/shareui2.png">
              <img class="shareuides" src="./assets/shareui3.png">
              <img class="shareuides" src="./assets/shareui4.png">
            </div>
          </div>
          <div class="studyhive">
            <div class="studyhead">
              <img class="studylogo" src="./assets/studyhive.png" alt="ShareJoy">
              <div class="studytitle">StudyHive</div>
            </div>
            <div class="study-content">
              <img class="phonestudy" src="./assets/dev2.png" alt="phone sharejoy">
              <h5>IT course and training platform, where the user can register their participants to take the class and build excellent portfolio as an attempt to prepare their career. The main target participants are they who have difficulties on economic status or have disability issue. Hope through this app, we can give the chance and portion to them equal with other people who are luckier.</h5>
            </div>
            <div class="studyui">
              <img class="studyuides" src="./assets/studyui1.png">
              <img class="studyuides" src="./assets/studyui2.png">
              <img class="studyuides" src="./assets/studyui3.png">
              <img class="studyuides" src="./assets/studyui4.png">
            </div>
          </div>
        </div>
      </div>

      <div id="contact">
        <div class="lets">LET’S HAVING WORK TOGETHER</div>
        <div class="contact-container">
          <div class="contacthead">Contact Me</div>
          <div class="wa">
            <img class="wa-icon" src="./assets/wa.png">
            <a class="wa-name" href="https://wa.me/6282330014557" target="_blank">082330014557</a>
          </div>
          <div class="gmail">
            <img class="gmail-icon" src="./assets/gmail.webp">
            <a class="gmail-name" href="mailto: firdaardana0111@gmail.com" target="_blank">firdaardana0111@gmail.com</a>
          </div>
          <div class="linkedin">
            <img class="linkedin-icon" src="./assets/linkedin.png">
            <a class="linkedin-name" href="https://www.linkedin.com/in/firdaardana/" target="_blank">https://www.linkedin.com/in/firdaardana/</a>
          </div>
        </div>
      </div>
    </div>
  </div>

    <div class="footer">
      <div class="footer-content">All Rights Reserved | 2023</div>
    </div>
  </div>
</template>