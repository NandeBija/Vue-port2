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
            <h3>HTML 5</h3>
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
            <h3>CSS3</h3>
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

/* RECENT ABOUT STYLES */
.curved {
  background-color: brown;
  color: white;
  text-align: center;
  background-size: cover;
  background-repeat: no-repeat;
  padding-top: 150px;
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
