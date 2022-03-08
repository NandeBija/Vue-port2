<template>
  <section id="About">
    <div class="container">
      <div class="container">
        <div class="AB">
          <h1 class="h1">Get to know me</h1>
          <h2 class="h2">
            <span style="border-bottom: 3px solid red">About</span>
          </h2>
        </div>
        <div class="container">
          <div class="row" style="padding-top: 80px">
            <div class="col-4">
              <div class="col-6">
                <img src="../assets/land.jpeg" alt="Nande" />
                <div class="aboutImg"></div>
              </div>
            </div>
            <div class="col-12">
              <div class="col-sm">
                <div class="aboutContent">
                  <!-- Merge skills into landing page -->
                  <strong
                    ><span style="border-bottom: 3px solid red; font-size: 25px"
                      >Skills:</span
                    ></strong
                  ><br />

                  <div class="container" id="myAbt">
                    <div class="row">
                      <div class="col-sm-6">
                        <p class="sp">HTML</p>
                        <div class="container shadow-lg" style="padding: 0%">
                          <div class="skills html">90%</div>
                        </div>
                      </div>
                      <div class="col-sm-6">
                        <p class="sp">CSS</p>
                        <div class="container shadow-lg" style="padding: 0%">
                          <div class="skills css">80%</div>
                        </div>
                      </div>
                    </div>
                    <div class="row">
                      <div class="col-sm-6">
                        <p class="sp">JavaScript</p>
                        <div class="container shadow-lg" style="padding: 0%">
                          <div class="skills js">65%</div>
                        </div>
                      </div>
                      <div class="col-sm-6">
                        <p class="sp">Vue JS</p>
                        <div class="container shadow-lg" style="padding: 0%">
                          <div class="skills bootstrap">77%</div>
                        </div>
                      </div>
                      <br />

                      <p style="text-align: justify; padding-top: 14px">
                        <strong>Soft Skills:</strong><br />
                        Strong verbal and written communication skills,
                        strategic planning, time management skills.
                      </p>
                      <p style="text-align: justify">
                        <strong>Technical Skills: Computer-literate;</strong
                        ><br />
                        Data collection, capturing and processing; Computer
                        software [ArcGIS, QGIS, MS Excel, MS Word]
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-sm" id="abtcont">
          <p>
            <strong>Bio:</strong><br />
            I enjoy turning complex problems into smaller and simpler,
            manageable bits. Always eager to take on new challenges. <br />I can
            be a bit shy and nervous around new people but warm up as soon as I
            read the energy in the room.<br />

            <strong>Passion for coding:</strong><br />
            I fell in love with the tech industry as soon as I had access to
            free Wi-Fi at University in 2017, <br />but only had the chance to
            venture into the industry recently. The tech industry is the future,
            and the future is now.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
#About {
  background-color: #f5d3d52c;
  padding-top: 59px;
  min-height: 100vh;
  font-size: 1.2em;
}
.h2,
h2 {
  text-align: center;
  padding-bottom: 8px;
}
.h1,
h1 {
  padding-top: 9px;
  text-align: center;
  color: gray;
  font-size: medium;
}
/* .hr {
  color: red;
  background-color: red;
  position: relative;
  bottom: 200px;
  left: 4%;
  height: 10px;
  margin-left: 60%;
  border-top: 1px solid rgb(134, 132, 132);
} */
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
.html {
  width: 90%;
  background-color: #f44336;

  border-radius: 10px;
}
.css {
  width: 80%;
  background-color: #f44336;
  border-radius: 10px;
}
.js {
  width: 50%;
  background-color: #f44336;
  border-radius: 10px;
}
.bootstrap {
  width: 70%;
  background-color: #f44336;

  border-radius: 10px;
}
.col-6 img {
  border-radius: 50%;
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
    min-height: 165vh;
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
</style>
