<template>
  <section>
    <div class="container" id="Projects">
      <div class="pro">
        <h1 class="h1">Some of my latest work</h1>
        <h2 class="h2">
          <span style="border-bottom: 3px solid red">Projects</span>
        </h2>
      </div>
      <div class="row" v-if="projects">
        <!-- feaure box -->
        <div
          v-for="project of projects"
          :key="project.title"
          class="col-sm-6 col-lg-4"
        >
          <div class="feature-box-1">
            <div class="card-body">
              <h5 class="card-title">{{ project.title }}</h5>
              <img
                :src="project.img"
                class="card-img-top"
                alt="Timeline project"
              />
              <div class="hov">
                <a :href="project.github" target="_blank">Github</a>
                <a :href="project.live" target="_blank">Netlify</a>
                <a :href="project.heroku" target="_blank">Backend</a>
              </div>
              <p>{{ project.description }}</p>
              <p></p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: null,
      projects: [
        {
          title: "BMI calculator",
          github: "https://github.com/NandeBija/BMI.git",
          live: "https://vigorous-austin-12a137.netlify.app/",
          // heroku:"",
          description: "|Calculate your Body Mass Index ",
          img: "https://i.postimg.cc/7LmrVPqp/BMI.png",
          techStacks: ["HTML", "CSS", "JavaScript"],
        },
        {
          title: "Point of Sale",
          github: "https://github.com/NandeBija/Glasses-ecommerce.git",
          live: "https://elastic-saha-6c5e72.netlify.app/",
          // heroku:"",
          description: "|Sunglasses ecommerce store",
          img: "https://i.postimg.cc/SRzWdsbd/ecommerce.png",
          techStacks: ["HTML", "CSS", "JavaScript", "Vue JS"],
        },
        {
          title: "Maths calculator",
          github: "https://github.com/NandeBija/calculator.git",
          live: "https://distracted-varahamihira-8bbd1d.netlify.app/",
          // heroku:"",
          description: "|Perform maths calculations",
          img: "https://i.postimg.cc/GhmBbt55/calculator.png",
          techStacks: ["HTML", "CSS", "JavaScript"],
        },
        {
          title: "Speed reactor game",
          github: "https://github.com/NandeBija/ReactionTImer_game.git",
          live: "https://silly-kare-81e9a0.netlify.app/",
          // heroku:"",
          description: "|Reaction timer game to test your reflexes",
          img: "https://i.postimg.cc/DzzM7rKM/reactor.png",
          techStacks: ["HTML", "CSS", "JavaScript"],
        },
        {
          title: "Fullstack project",
          github: "https://github.com/NandeBija/Prac3_Cardss.git",
          live: "https://jamylee-fullstack-project.netlify.app/",
          heroku: "https://projectbackendnande.herokuapp.com/users",
          description: "|Group project Fullstack point of Sale",
          img: "https://i.postimg.cc/1R2fXg68/Screenshot-from-2022-03-23-14-27-37.png",
          techStacks: ["HTML", "CSS"],
        },
        {
          title: "CRUD operations ",
          github: "https://github.com/Jamy-lee/Fullstack-project.git",
          live: "https://dreamy-bassi-bf5eb4.netlify.app/",
          // heroku:"",
          description: "|Create, Read, Update, and Delete",
          img: "https://i.postimg.cc/kGxLZ7xN/CRUD.png",
          techStacks: ["HTML", "CSS"],
        },
      ],
    };
  },
  // mounted() {
  //   fetch("http://localhost:7000")
  //     .then((res) => res.json())
  //     .then((data) => {
  //       console.log(data);
  //       this.projects = data;
  //     });
  // },
};
</script>

<style scoped>
#Projects {
  padding-top: 59px;
  padding-bottom: 50px;
}
section {
  background-color: #f5d3d52c;
}
body {
  margin-top: 20px;
}
a {
  text-decoration: none;
}

.feature-box-1 {
  padding: 32px;
  box-shadow: 0 0 30px rgba(31, 45, 61, 0.125);
  margin: 15px 0;
  position: relative;
  z-index: 1;
  border-radius: 10px;
  overflow: hidden;
  -moz-transition: ease all 0.35s;
  -o-transition: ease all 0.35s;
  -webkit-transition: ease all 0.35s;
  transition: ease all 0.35s;
  top: 0;
}
.feature-box-1 * {
  -moz-transition: ease all 0.35s;
  -o-transition: ease all 0.35s;
  -webkit-transition: ease all 0.35s;
  transition: ease all 0.35s;
}
.feature-box-1 .icon {
  width: 70px;
  height: 70px;
  line-height: 70px;
  background: #fc5356;
  color: #ffffff;
  text-align: center;
  border-radius: 50%;
  margin-bottom: 22px;
  font-size: 27px;
}
.feature-box-1 .icon i {
  line-height: 70px;
}
.feature-box-1 h5 {
  font-weight: 600;
}
.feature-box-1 p {
  margin: 0;
}
.feature-box-1:after {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: auto;
  right: 0;
  border-radius: 10px;
  width: 0;
  background: #f08c93f3;
  z-index: -1;
  -moz-transition: ease all 0.35s;
  -o-transition: ease all 0.35s;
  -webkit-transition: ease all 0.35s;
  transition: ease all 0.35s;
}
.feature-box-1:hover {
  top: -5px;
}
.feature-box-1:hover h5 {
  color: #ffffff;
}
.feature-box-1:hover p {
  color: rgba(255, 255, 255, 0.8);
}
.feature-box-1:hover:after {
  width: 100%;
  height: 100%;
  border-radius: 10px;
  left: 0;
  right: auto;
}
.section {
  padding: 100px 0;
  position: relative;
}
.section-title {
  padding-bottom: 45px;
}
.pro {
  padding-bottom: 4%;
}
#projects {
  min-height: 110vh;
  padding-top: 54px;
  padding-bottom: 54px;
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
.section-title h2 {
  font-weight: 700;
  color: #20247b;
  font-size: 45px;
  margin: 0 0 15px;
  border-left: 5px solid #fc5356;
  padding-left: 15px;
}
.card-body img {
  height: 18%;
  border-radius: 3%;
  width: 100%;
}
@media screen and (max-width: 600px) {
  #projects {
    background-color: #f5d3d52c;
    min-height: 110vh;
    padding-top: 54px;
    padding-top: 10%;
  }
  .card img {
    height: 110px;
  }
  #projects {
    background-color: #f5d3d52c;
    min-height: 275vh;
    padding-top: 54px;
  }
  .card {
    height: 430px;
    width: 90%;
    margin-left: 4%;
  }
  .card-body img {
    min-height: 180px;
    border-radius: 3%;
  }
}
.hov a {
  color: red;
  display: inline-block;
  padding: 3px;
}
/*





.card {
  column-gap: 50px;

  border-radius: 15px;
  background: #eeccb71e;
  box-shadow: 0 8px 32px 0 rgba(135, 31, 31, 0.37);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border-radius: 10px;
  border: 1px solid rgba(255, 255, 255, 0.18);
}
.card:hover {
  transition: transform 0.5s ease-in-out;
  transform: scale(1.04);
}


 */
</style>
