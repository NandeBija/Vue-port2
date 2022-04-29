<template>
  <section id="section">
    <div class="curved" id="Abt">
      <div class="AB">
        <h1 class="h1">Get to know me</h1>
        <h2 class="h2">
          <span style="border-bottom: 3px solid red">About</span>
        </h2>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-4">
            <div class="col-6">
              <img src="../assets/picture.jpg" alt="Nande" />
              <div class="aboutImg"></div>
            </div>
          </div>

          <div class="col">
            <div class="col-sm" id="abtcont">
              <p>
                <strong>Bio:</strong><br />
                I enjoy turning complex problems into smaller and simpler,
                manageable bits. Always eager to take on new challenges. <br />I
                can be a bit shy and nervous around new people but warm up as
                soon as I read the energy in the room.<br />

                <strong>Passion for coding:</strong><br />
                I fell in love with the tech industry as soon as I had access to
                free Wi-Fi at University in 2017, <br />but only had the chance
                to venture into the industry recently. The tech industry is the
                future, and the future is now.
              </p>
              <p style="text-align: justify; padding-top: 14px">
                <strong>Soft Skills:</strong><br />
                Strong verbal and written communication skills, strategic
                planning, time management skills.
              </p>
              <p style="text-align: justify">
                <strong>Technical Skills: Computer-literate;</strong><br />
                Data collection, capturing and processing; Computer software
                [ArcGIS, QGIS, MS Excel, MS Word]
              </p>
            </div>
          </div>
        </div>
        <!-- skills rows -->
      </div>

      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#fff"
          fill-opacity="1"
          d="M0,160L48,176C96,192,192,224,288,245.3C384,267,480,277,576,256C672,235,768,181,864,176C960,171,1056,213,1152,229.3C1248,245,1344,235,1392,229.3L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
        ></path>
      </svg>
    </div>
  </section>
  <section>
    <div class="skills-section">
      <div class="skills-header">
        <h1 class="h1">some of my skills</h1>
      </div>
      <div class="skills-container">
        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="https://cdn.freebiesupply.com/logos/large/2x/html-5-logo-png-transparent.png"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>HTML</h3>
          </div>
        </div>

        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="https://upload.wikimedia.org/wikipedia/commons/3/3d/CSS.3.svg"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>CSS</h3>
          </div>
        </div>

        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYmY834Fvxg9FGodkJzqfzJxenMr25Fhxey0poBrG8P0sk4i1FnegpkfceqikubDBUpWI&usqp=CAU"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>JAVASCRIPT</h3>
          </div>
        </div>

        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="http://pluspng.com/img-png/nodejs-logo-png-nice-images-collection-node-js-desktop-wallpapers-370.png"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>NODE.JS</h3>
          </div>
        </div>

        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="https://www.logo.wine/a/logo/MySQL/MySQL-Logo.wine.svg"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>MySQL</h3>
          </div>
        </div>
        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>Vue.JS</h3>
          </div>
        </div>
        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="data:image/png;base64,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"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>WordPress</h3>
          </div>
        </div>
        <div class="skills-box">
          <div class="skills-title">
            <div class="skills-img">
              <img
                src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/1200px-Bootstrap_logo.svg.png"
                alt=""
                class="skills-icons"
              />
            </div>
            <h3>Bootstrap</h3>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style scoped>
#About {
  background-color: #f5d3d52c;
  padding-top: 59px;
  min-height: 120vh;
  font-size: 1.2em;
}
.h2,
h2 {
  text-align: center;
  padding-bottom: 8px;
  color: white;
}
.h1,
h1 {
  padding-top: 9px;
  text-align: center;
  color: gray;
  font-size: medium;
}

#abtcont {
  padding-top: 50px;
  text-align: justify;
}
#myAbt {
  justify-items: start;
  border-left: solid red 1px;
}

.sp {
  font-size: large;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  padding-top: 10px;
}

.col-6 img {
  border-radius: 50%;
  object-fit: cover;
  height: 350px;
  width: 260px;
  position: relative;
  padding-bottom: 40px;
  padding-top: 40px;
}
@media screen and (max-width: 600px) {
  .col-6 {
    display: none;
  }
  #abtcont {
    padding-top: 20px;
    text-align: justify;
  }
  #About {
    background-color: #f5d3d52c;
    padding-top: 59px;
    min-height: 120vh;
  }
  #myAbt {
    justify-items: start;
    border-left: none;
    width: 100%;
  }
  .col-4 {
    display: none;
  }
}

@media screen and (max-width:977){
  
}

/* RECENT ABOUT STYLES */
.curved {
  background-color: brown;
  color: white;
  text-align: center;
  background-size: cover;
  background-repeat: no-repeat;
  padding-top: 60px;
}
.container {
  min-height: 30vh;
  padding-top: 10px;
}

img {
  max-width: 500px;
}
.curved p {
  font-size: 1rem;
  margin: 0 5rem, 0, 5rem;
}
span {
  color: white;
}
svg {
  display: block;
}
button {
  color: greenyellow;
  background-color: rgb(220, 227, 245);
  position: relative;
  bottom: 100px;
}

/* lol lol  */

.skills-section {
  padding-top: 20px;
}

.skills-header {
  text-align: center;
  color: #fff;
  padding: 1rem;
  position: relative;
}

.skills-header:after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 100px;
  height: 4px;
  background-color: red;
  border-radius: 2px;
}

.skills-container {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  justify-content: center;
  align-items: center;
  text-align: center;
  grid-gap: 1rem;
  padding: 1rem 80px;
  font-size: 1.2rem;
}
.skills-box {
  padding: 1rem;
  color: #000;
  cursor: pointer;
}

.skills-box:hover .skills-img {
  transform: translateX(-20px);
}

.skills-title {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0.5rem;
  margin-bottom: 0.5rem;
  position: relative;
}

.skills-title:after {
  content: "";
  position: absolute;
  bottom: 0;
  rigth: 50%;
  width: 20px;
  height: 4px;
  border-radius: 2px 0 0 2px;
  background-color: red;
  transition: 0.5s;
}

.skills-title:before {
  content: "";
  position: absolute;
  bottom: 0;
  left: 50%;
  width: 100px;
  height: 4px;
  border-radius: 0 2px 2px 0;
  background-color: red;
}

.skills-icons {
  width: 50px;
  z-index: 2;
}

.skills-img {
  width: 90px;
  height: 90px;
  position: relative;
  border-radius: 45px;
  background-color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: 0.5s;
}

.skills-img:after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 50%;
  height: 90px;
  background: rgba(100, 100, 100, 0.5);
  border-radius: 45px 0 0 45px;
}
.skills-title h3 {
  color: #333;
  margin-top: 0.5rem;
}
@media screen and (max-width: 990px) {
  .skills-container {
    grid-template-columns: repeat(2, 1fr);
    padding: 2rem 50px;
  }
}

@media screen and (max-width: 650px) {
  .skills-container {
    grid-template-columns: 2fr;
    padding: 2rem 50px;
  }
}
</style>
