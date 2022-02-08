<template>
  <Navbar />
  <Home />
  <About />
  <Resume />
  <Projects />
  <Testimonials />
  <Contact />
  <!-- back to top button -->
  <div id="back-top" style="display: block">
    <a href="#home"><i class="fa fa-chevron-up"></i></a>
  </div>

  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Home from "./components/Home.vue";
import About from "./components/About.vue";
import Resume from "./components/Resume.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
import Projects from "./components/Projects.vue";
import Testimonials from "./components/Testimonials.vue";

export default {
  components: {
    About,
    Home,
    Contact,
    Navbar,
    Footer,
    Resume,
    Projects,
    Testimonials,
  },
};
</script>

<style>
body {
  margin: 0px;
  overflow-x: hidden;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.fa {
  position: relative;
  font-size: 22px;
  text-align: center;

  padding-left: 2px;
  color: #423d3d;
  padding-top: 5px;
}
.social a:hover {
  color: red;
}
.social a {
  color: white;
}
#back-top {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 999999999;
  color: #eee;
  background-color: rgba(0, 0, 0, 0.3);
  transition: all 0.25s ease;
  padding: 10px;
  border-radius: 5px;
  text-align: center;
}
@media screen and (max-width: 600px) {
  body {
    overflow-x: hidden;
  }
}
</style>
