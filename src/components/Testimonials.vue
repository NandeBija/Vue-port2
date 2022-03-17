<template>
  <section id="testimonil">
    <div class="container">
      <div class="row">
        <h1 class="h1">More about me</h1>
        <h2 class="h2">
          <span style="border-bottom: 3px solid red">Testimonials</span>
        </h2>
      </div>
    </div>
    <div class="container">
      <div class="slider">
        <input type="radio" name="testimonial" id="t-1" />
        <input type="radio" name="testimonial" id="t-2" />
        <input type="radio" name="testimonial" id="t-3" checked />
        <input type="radio" name="testimonial" id="t-4" />
        <input type="radio" name="testimonial" id="t-5" />
        <div class="testimonials mb-8">
          <label class="item" for="t-1">
            <div class="mycard">
              <p class="cardtitle">Godwin Dzvapatsva</p>
              <div>
                <img
                  src="https://i.postimg.cc/MTGTqrsj/Godwin.jpg"
                  alt="nivel5"
                  class="cardimg"
                />
              </div>
              <div>
                <p class="carddescription">
                  I have no hesiotancy writing a recommendation for Nande. He
                  has a bright future in the industry
                </p>
              </div>
            </div>
          </label>
          <label class="item" for="t-2">
            <div class="mycard">
              <p class="cardtitle">Nomvuyiseko Mpofu</p>
              <div>
                <img
                  src="https://i.postimg.cc/mkXfgFCj/Whats-App-Image-2022-01-31-at-2-06-43-PM.jpg"
                  alt="Nomvuyiseko Mpofu's picture"
                  class="cardimg"
                />
              </div>
              <div>
                <p class="carddescription">
                  Nande is a very professional, hard-working individual and a
                  talanted developer. He will be a success in the industry.
                </p>
              </div>
            </div>
          </label>
          <label class="item" for="t-3">
            <div class="mycard">
              <p class="cardtitle">Emanuel Fente</p>
              <div>
                <img
                  src="https://i.postimg.cc/NMrqw3hM/emma.jpg"
                  alt="nivel5"
                  class="cardimg"
                />
              </div>
              <div>
                <p class="carddescription">
                  I have known Nande as a collegue and a friend outside the
                  workplace for long. He is a creative individual and very fun
                  to work with.
                </p>
              </div>
            </div>
          </label>
          <label class="item" for="t-4">
            <div class="mycard">
              <p class="cardtitle">Kagiso Mphayi</p>
              <div>
                <img
                  src="https://i.postimg.cc/7L8SV7xW/Whats-App-Image-2022-02-01-at-1-10-34-PM.jpg"
                  alt="nivel5"
                  class="cardimg"
                />
              </div>
              <div>
                <p class="carddescription">
                  I've had the chance to know Nande and work with him over the
                  past few months. He has a dedicated individual and has a great
                  work ethic
                </p>
              </div>
            </div>
          </label>
          <label class="item" for="t-5">
            <div class="mycard">
              <p class="cardtitle">Siyanda Ncamazana</p>
              <div>
                <img
                  src="https://i.postimg.cc/XJNyJ6cV/Siyanda1.jpg"
                  alt="nivel5"
                  class="cardimg"
                />
              </div>
              <div>
                <p class="carddescription">
                  I have had the chance to work with Nande within a team and as
                  an individual. He has a very positive work spirit and an eye
                  for the prize
                </p>
              </div>
            </div>
          </label>
        </div>
        <div class="dots">
          <label for="t-1"></label>
          <label for="t-2"></label>
          <label for="t-3"></label>
          <label for="t-4"></label>
          <label for="t-5"></label>
        </div>
      </div>
    </div>
  </section>
</template>

//
<script>
export default {
  data() {
    return {
      // testimonial: [
      //   {
      //     img: "https://i.postimg.cc/MTGTqrsj/Godwin.jpg",
      //     text: "I have no hesiotancy writing a recommendation for Nande. He has a bright future in the industry",
      //     name: "Godwin Dzvapatsva",
      //     relationship: "Lecturer",
      //   },
      //   {
      //     img: "https://i.postimg.cc/mkXfgFCj/Whats-App-Image-2022-01-31-at-2-06-43-PM.jpg",
      //     text: "Nande is a very professional, hard-working individual and a talanted developer. He will be a success in the industry ",
      //     name: "Nomvuyiseko Mpofu",
      //     relationship: "Collegue",
      //   },
      //   {
      //     img: "https://i.postimg.cc/NMrqw3hM/emma.jpg",
      //     text: " I have known Nande as a collegue and a friend outside the workplace for long. He is a creative individual and very fun to work with.",
      //     name: "Emanuel Fente",
      //     relationship: "Collegue",
      //   },
      //   {
      //     img: "https://i.postimg.cc/7L8SV7xW/Whats-App-Image-2022-02-01-at-1-10-34-PM.jpg",
      //     text: "I've had the chance to know Nande and work with him over the past few months. He has a dedicated individual and has a great work ethic",
      //     name: "Kagiso Mphayi ",
      //     relationship: "Collegue",
      //   },
      //   {
      //     img: "https://i.postimg.cc/XJNyJ6cV/Siyanda1.jpg",
      //     text: "I have had the chance to work with Nande within a team and as an individual. He has a very positive work spirit and an eye for the prize",
      //     name: "Siyanda Ncamazana  ",
      //     relationship: "Collegue",
      //   },
      //   {
      //     img: "https://i.postimg.cc/L8HqvMwj/Azabenathi1.jpg",
      //     text: "Nande is very enthusiastic and is always willing to take on new challenges.",
      //     name: "Azabenathi Pupuma ",
      //     relationship: "Collegue",
      //   },
      // ],
      // testimonial2: [
      //   {
      //     name: "Godwin Dzvapatsva",
      //     img: "https://i.postimg.cc/MTGTqrsj/Godwin.jpg",
      //     text: "I have no hesiotancy writing a recommendation for Nande. He has a bright future in the industry",
      //   },
      //   {
      //     name: "Nomvuyiseko Mpofu",
      //     img: "https://i.postimg.cc/mkXfgFCj/Whats-App-Image-2022-01-31-at-2-06-43-PM.jpg",
      //     text: "Nande is a very professional, hard-working individual and a talanted developer. He will be a success in the industry ",
      //   },
      //   {
      //     name: "Emanuel Fente",
      //     img: "https://i.postimg.cc/NMrqw3hM/emma.jpg",
      //     text: " I have known Nande as a collegue and a friend outside the workplace for long. He is a creative individual and very fun to work with.",
      //   },
      //   {
      //     name: "Kagiso Mphayi ",
      //     img: "https://i.postimg.cc/7L8SV7xW/Whats-App-Image-2022-02-01-at-1-10-34-PM.jpg",
      //     text: "I've had the chance to know Nande and work with him over the past few months. He has a dedicated individual and has a great work ethic",
      //   },
      // ],
    };
  },
};
</script>

<style scoped>
#testimonil {
  min-height: 100vh;
  padding-top: 59px;
}
.h2,
h2 {
  text-align: center;
  padding-bottom: 8px;
}
.h1,
h1 {
  text-align: center;
  color: gray;
  font-size: medium;
  padding-top: 1.5%;
}

.test-img-top {
  width: 300px;
  height: 250px;
  border-radius: 8%;
  padding: 10px;
  padding-left: 3%;
  align-items: center;
}
.test {
  text-align: center;
  justify-items: start;
}
.comma {
  color: red;
  font-size: 25px;
}
.test img {
  object-fit: cover;
}
#siyanda {
  object-fit: cover;
}
/* cellphone responsiveness */
@media screen and (max-width: 600px) {
  #testimonil {
    min-height: 100vh;
    /* padding-top: 59px; */
  }
}

/* Carousel CSS */
.mycard {
  height: 100%;
  width: 100%;
  max-width: 24rem;
}
.cardtitle {
  font-weight: bold;
  --tw-text-opacity: 1;
  color: rgba(31, 41, 55, var(--tw-text-opacity));
  text-align: center;
}
.cardimg {
  margin-left: auto;
  margin-right: auto;
  margin-top: 2.75rem;
  margin-bottom: 2.75rem;
  max-height: 6.5rem;
  border-radius: 9999px;
  object-fit: cover;
}
.carddescription {
  --tw-text-opacity: 1;
  color: rgba(107, 114, 128, var(--tw-text-opacity));
  text-align: center;
}

.slider {
  width: 100%;
  min-height: 485px;
}
.slider input {
  display: none;
}
.testimonials {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  min-height: 518px;
  perspective: 559px;
  margin-top: 50px;
  overflow: hidden;
}
.testimonials .item {
  max-width: 22rem;
  border-radius: 1.5rem;
  border-width: 2px;
  --tw-border-opacity: 1;
  border-color: rgba(30, 58, 138, var(--tw-border-opacity));
  top: 0;
  position: absolute;
  box-sizing: border-box;
  background-color: #fff;
  padding: 40px;
  width: 750px;
  text-align: center;
  transition: transform 0.4s;
  /* -webkit-transform-style: preserve-3d; */
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
  user-select: none;
  cursor: pointer;
}
.testimonials .item img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 9px solid rgba(135, 31, 31, 0.37);
}
.testimonials .item p {
  color: #2c3e50;
  font-family: 16px Avenir, Arial, Helvetica, sans-serif;
}
.testimonials .item h2 {
  font-size: 24px;
}
.dots {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-bottom: 50px;
}
.dots label {
  display: block;
  height: 7px;
  width: 7px;
  border-radius: 50%;
  cursor: pointer;
  background-color: #413b52;
  margin: 7px;
  transition: transform 0.2s, color 0.2s;
} /* First */
#t-1:checked ~ .dots label[for="t-1"] {
  transform: scale(2);
  background-color: #fff;
}
#t-1:checked ~ .dots label[for="t-2"] {
  transform: scale(1.5);
}
#t-1:checked ~ .testimonials label[for="t-1"] {
  z-index: 4;
}
#t-1:checked ~ .testimonials label[for="t-2"] {
  transform: translateX(300px) translateZ(-90px) translateY(-15px);
  z-index: 3;
}
#t-1:checked ~ .testimonials label[for="t-3"] {
  transform: translateX(600px) translateZ(-180px) translateY(-30px);
  z-index: 2;
}
#t-1:checked ~ .testimonials label[for="t-4"] {
  transform: translateX(900px) translateZ(-270px) translateY(-45px);
  z-index: 1;
}
#t-1:checked ~ .testimonials label[for="t-5"] {
  transform: translateX(1200px) translateZ(-360px) translateY(-60px);
} /* Second
*/
#t-2:checked ~ .dots label[for="t-1"] {
  transform: scale(1.5);
}
#t-2:checked ~ .dots label[for="t-2"] {
  transform: scale(2);
  background-color: #fff;
}
#t-2:checked ~ .dots label[for="t-3"] {
  transform: scale(1.5);
}
#t-2:checked ~ .testimonials label[for="t-1"] {
  transform: translateX(-300px) translateZ(-90px) translateY(-15px);
}
#t-2:checked ~ .testimonials label[for="t-2"] {
  z-index: 3;
}
#t-2:checked ~ .testimonials label[for="t-3"] {
  transform: translateX(300px) translateZ(-90px) translateY(-15px);
  z-index: 2;
}
#t-2:checked ~ .testimonials label[for="t-4"] {
  transform: translateX(600px) translateZ(-180px) translateY(-30px);
  z-index: 1;
}
#t-2:checked ~ .testimonials label[for="t-5"] {
  transform: translateX(900px) translateZ(-270px) translateY(-45px);
} /* Third */
#t-3:checked ~ .dots label[for="t-2"] {
  transform: scale(1.5);
}
#t-3:checked ~ .dots label[for="t-3"] {
  transform: scale(2);
  background-color: #fff;
}
#t-3:checked ~ .dots label[for="t-4"] {
  transform: scale(1.5);
}
#t-3:checked ~ .testimonials label[for="t-1"] {
  transform: translateX(-600px) translateZ(-180px) translateY(-30px);
}
#t-3:checked ~ .testimonials label[for="t-2"] {
  transform: translateX(-300px) translateZ(-90px) translateY(-15px);
}
#t-3:checked ~ .testimonials label[for="t-3"] {
  z-index: 3;
}
#t-3:checked ~ .testimonials label[for="t-4"] {
  transform: translateX(300px) translateZ(-90px) translateY(-15px);
  z-index: 2;
}
#t-3:checked ~ .testimonials label[for="t-5"] {
  transform: translateX(600px) translateZ(-180px) translateY(-30px);
} /* Fourth */
#t-4:checked ~ .dots label[for="t-3"] {
  transform: scale(1.5);
}
#t-4:checked ~ .dots label[for="t-4"] {
  transform: scale(2);
  background-color: #fff;
}
#t-4:checked ~ .dots label[for="t-5"] {
  transform: scale(1.5);
}
#t-4:checked ~ .testimonials label[for="t-1"] {
  transform: translateX(-900px) translateZ(-270px) translateY(-45px);
}
#t-4:checked ~ .testimonials label[for="t-2"] {
  transform: translateX(-600px) translateZ(-180px) translateY(-30px);
}
#t-4:checked ~ .testimonials label[for="t-3"] {
  transform: translateX(-300px) translateZ(-90px) translateY(-15px);
  z-index: 2;
}
#t-4:checked ~ .testimonials label[for="t-4"] {
  z-index: 3;
}
#t-4:checked ~ .testimonials label[for="t-5"] {
  transform: translateX(300px) translateZ(-90px) translateY(-15px);
} /* Fifth */
#t-5:checked ~ .dots label[for="t-4"] {
  transform: scale(1.5);
}
#t-5:checked ~ .dots label[for="t-5"] {
  transform: scale(2);
  background-color: #fff;
}
#t-5:checked ~ .testimonials label[for="t-1"] {
  transform: translateX(-1200px) translateZ(-360px) translateY(-60px);
}
#t-5:checked ~ .testimonials label[for="t-2"] {
  transform: translateX(-900px) translateZ(-270px) translateY(-45px);
  z-index: 1;
}
#t-5:checked ~ .testimonials label[for="t-3"] {
  transform: translateX(-600px) translateZ(-180px) translateY(-30px);
  z-index: 2;
}
#t-5:checked ~ .testimonials label[for="t-4"] {
  transform: translateX(-300px) translateZ(-90px) translateY(-15px);
  z-index: 3;
}
#t-5:checked ~ .testimonials label[for="t-5"] {
  z-index: 4;
}
</style>
