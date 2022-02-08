<template>
  <section id="resume">
    <h1 class="h1">My qualifications and work experience</h1>
    <h2 class="h2"><span style="border-bottom: 3px solid red">Resume</span></h2>
    <div class="container mt-5 mb-5">
      <div class="container">
        <div class="row">
          <div class="col-sm">
            <div class="resum">
              <div class="col-md-6 offset-md-3">
                <h4>Work</h4>
                <ul v-for="work of workExp" :key="work.title" class="timeline">
                  <li>
                    <h7 class="h7">{{ work.title }}</h7
                    ><br />

                    <p class="float-right">{{ work.date }}</p>
                    <p>
                      {{ work.description }}
                    </p>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-sm">
            <div class="resum">
              <div class="col-md-6 offset-md-3">
                <h4>Education</h4>
                <ul v-for="edu of education" :key="edu.title" class="timeline">
                  <li>
                    <h7 class="h7">{{ edu.title }}</h7
                    ><br />

                    <p class="float-right">{{ edu.date }}</p>
                    <p>{{ edu.description }}</p>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- <hr class="seperater"> </hr> -->
  </section>
</template>

<script>
export default {
  data() {
    return {
      workExp: [
        {
          title: "Research intern @ HSRC",
          date: "30 May, 2021",
          description:
            " I worked as a research assistance at Human Science Research Council of South Africa.",
        },
        {
          title: " Freelance cartographer",
          date: "June, 2020",
          description:
            " Did some freelance work creating maps for researchers within the GIS field from mid-2020",
        },
        {
          title: " Tutor",
          date: "24 February, 2019",
          description:
            " Worked as a Geographic Information Sciences tutor at the University of Western Cape from 2019 to 2020.",
        },
      ],
      education: [
        {
          title: "LifeChoices Academy",
          date: "Sep, 2021 - present",
          description: " Enrolled for a coding course at LifeCHoices Academy",
        },
        {
          title: " Honours degree ",
          date: "Feb, 2020 - Nov, 2020",
          description:
            " Completed Honours degree in GIS and Enviroonmental Management at the UNiversity of Western Cape",
        },
        {
          title: " Graduated for Honours ",
          date: "24 Feb 2017 - 20 Nov 2019",
          description:
            " Undergraduate degree in Geography and Environmental Studies at the University of Western Cape",
        },
      ],
    };
  },
 
};
</script>

<style scoped>
#resume {
  padding-top: 45px;
  font-size: 1em;
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
.h7 {
  color: rgb(0, 0, 0);
  font-size: larger;
}

ul.timeline {
  list-style-type: none;
  position: relative;
}
ul.timeline:before {
  content: " ";
  background: #d4d9df;
  display: inline-block;
  position: absolute;
  left: 29px;
  width: 2px;
  height: 100%;
  z-index: 400;
}
ul.timeline > li {
  margin: 20px 0;
  padding-left: 20px;
}
ul.timeline > li:before {
  content: " ";
  background: white;
  display: inline-block;
  position: absolute;
  border-radius: 50%;
  border: 3px solid #e83922;
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 400;
}
.mb-5 {
  display: flex;
}
h4 {
  text-align: center;
}
#cont2 {
  height: 79vh;
  padding-top: 0;
}
.resum {
  display: flex;
  flex-wrap: wrap;
}

@media screen and (max-width: 600px) {
  .resum {
    display: flex;
    flex-wrap: wrap;
    padding-top: 15px;
  }
}
@media screen and (max-width: 980px) {
  ul {
    display: flex;
    flex-wrap: wrap;
    padding-top: 15px;
    width: 100%;
  }
}
</style>
