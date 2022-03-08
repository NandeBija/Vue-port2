<template>
  <html>
  <body id="bod">
    <header id="home" class="home">
      <h1><span style="color:white;">Hello, <br>I'm </span> NANDE BIJA</h1>
      <div id="content" class="container">
     <p class="headerContent">
          | Junior Full-stack developer  |<br /><span class="social">
            <a href="https://www.linkedin.com/in/nande-bija-6333441b8/" target="_blank" class="fa fa-linkedin"></a>
            <a
              href="https://github.com/NandeBija"
              target="_blank"
              class="fa fa-github"
            ></a>
            
          </span>
        </p>
    </div> 
    
    <a href="#About" class="btn">More about me</a>
    </header>
    
   
  </body>
</html>
</template>

<script>
export default {

}
</script>

<style scoped>
*{
  margin: 0px;
  padding: 0px;
}
#bod{
  min-height:100 hv;
}

.home {
  min-height: 100vh;
  background-image: url("https://ucarecdn.com/118482c6-5bbc-4de5-ade2-63c59873006f/image.png");
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
}

body{
  font-family: Ariel, Helvetica, sans-serif;
  color: white;
  line-height: 1.8;
  text-align: center;
}
.headerContent {
  font-size: 2.5em;
  color: #ece8e8ef;
  position: relative;
  bottom: 65px;
}
.headerContent a {
  padding-left: 10px;
  padding-right: 10px;
}

.container{
  max-width: 960px;
  margin: auto;
  padding: 0 30px;
}

/* #showcase{
  height: 300px;
} */

#home h1{
   font-size: 5.9em;
  color: #ff0000b8;
  line-height: 1.3;
  position: relative;
  animation: heading;
  animation-duration: 3s;
  animation-fill-mode: forwards;
  font-weight: 800;
}

@keyframes heading{
  0% {top: -50px;}
  100% {top: 200px;}
}

#content {
  position: relative;
  top:300px;
  animation-name: content;
  animation-duration: 3s;
  animation-fill-mode: forwards;
}

@keyframes content{
  0% {left: -1000px;}
  100% {left: 0px;}
}

.btn{
    display: inline-block;
    color: rgb(255, 255, 255);
    position: relative;
    top:250px;
    text-decoration: none;
    padding: 1rem 2rem;
    border: rgb(255, 253, 253) 2px solid;
    border-radius: 30%;
    margin-top: 40px;
    opacity: 0;
    animation-name: btn;
    animation-duration: 3s;
    animation-delay: 2s;
    animation-fill-mode: forwards;
    transition-property: transform;
    transition-duration: 1s;
  }

.btn:hover{
  transform: rotateY(360deg);
}
@media screen and (max-width: 600px) {
  .home {
    height: 200vh;
  }
  #home h1{
   font-size: 4.9em;
  color: #ff0000b8;
  line-height: 1.3;
  position: relative;
  animation: heading;
  animation-duration: 3s;
  animation-fill-mode: forwards;
  font-weight: 800;
}
}
@keyframes btn {
  0% {opacity: 0}
  100% {opacity: 1}
}
</style>