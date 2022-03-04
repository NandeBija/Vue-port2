<template>
  <section id="projects">
    <div class="container" id="Projects">
      <div class="pro">
        <h1 class="h1">Some of my latest work</h1>
        <h2 class="h2">
          <span style="border-bottom: 3px solid red">Projects</span>
        </h2>
      </div>
      <div class="row" v-if="projects">
        <div v-for="project of projects" :key="project.title" class="col-sm-4">
          <div class="card mb-3 shadow-lg">
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
          description: "|Calculate your Body Mass Index ",
          img: "https://i.postimg.cc/7LmrVPqp/BMI.png",
          techStacks: ["HTML", "CSS", "JavaScript"],
        },
        {
          title: "Point of Sale",
          github: "https://github.com/NandeBija/Glasses-ecommerce.git",
          live: "https://elastic-saha-6c5e72.netlify.app/",
          description: "|Sunglasses ecommerce store",
          img: "https://i.postimg.cc/SRzWdsbd/ecommerce.png",
          techStacks: ["HTML", "CSS", "JavaScript", "Vue JS"],
        },
        {
          title: "Maths calculator",
          github: "https://github.com/NandeBija/calculator.git",
          live: "https://distracted-varahamihira-8bbd1d.netlify.app/",
          description: "Description:|Perform mathematical calculations",
          img: "https://i.postimg.cc/GhmBbt55/calculator.png",
          techStacks: ["HTML", "CSS", "JavaScript"],
        },
        {
          title: "Speed reactor game",
          github: "https://github.com/NandeBija/ReactionTImer_game.git",
          live: "https://silly-kare-81e9a0.netlify.app/",
          description: "|Reaction timer game to test your reflexes",
          img: "https://i.postimg.cc/DzzM7rKM/reactor.png",
          techStacks: ["HTML", "CSS", "JavaScript"],
        },
        {
          title: "Cards projects",
          github: "https://github.com/NandeBija/Prac3_Cardss.git",
          //   live: "",
          description: "Description:|Card display",
          img: "https://i.postimg.cc/fT3p9jtn/cards2.png",
          techStacks: ["HTML", "CSS"],
        },
        {
          title: "CRUD operations ",
          github: "https://github.com/NandeBija/CRUD-exersice.git",
          live: "https://dreamy-bassi-bf5eb4.netlify.app/",
          description: "Description:|Create, Read, Update, and Delete",
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
#projects {
  background-color: #f5d3d52c;
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
.pro {
  padding-bottom: 4%;
}
.card-body img {
  height: 18%;
  border-radius: 3%;
  width: 100%;
}

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
.hov a {
  color: red;
  display: inline-block;
  padding: 3px;
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
</style>
