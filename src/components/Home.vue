<template>
  <section>
    <div id="home">
      <div class="box">
        <h1>
          <span class="helloText"><strong>Hello.</strong><br /></span>
          <div class="myName">I'm Nande Bija.</div>
          <br />
        </h1>
        <br />
        <p class="headerContent">
          | Full-stack developer |<br /><span class="social">
            <a href="" target="_blank" class="fa fa-linkedin"></a>
            <a
              href="https://github.com"
              target="_blank"
              class="fa fa-github"
            ></a>
            <a
              href="https://github.com"
              target="_blank"
              class="fa fa-instagram"
            ></a>
          </span>
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.myName {
  width: 15ch;
  animation: typing 3s steps(28) 1 normal both;
  white-space: nowrap;
  overflow: hidden;

  font-size: 3.7em;
  color: #ff0000b8;
  padding-top: 0%;
  font-weight: 900;
}

@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

body {
  margin: 0px;
}
#home {
  height: 100vh;
  background-image: url("https://ucarecdn.com/118482c6-5bbc-4de5-ade2-63c59873006f/image.png");
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
}
h1 {
}
.box {
  text-align: center;
  padding-top: 9%;
}
.helloText {
  font-size: 3.5em;
  color: #f5f5f5;
  text-align: center;
}

.headerContent {
  font-size: 2.5em;
  color: #ece8e8ef;
}
.headerContent a {
  padding-left: 10px;
  padding-right: 10px;
}
@media screen and (max-width: 600px) {
  #home {
    height: 80vh;
  }
  .box {
    text-align: center;
  }
  .hellotext {
    padding-right: 68px;
  }
  .myName {
    font-size: 2.8em;
    color: #ff0000b8;
  }
  .headerContent {
    font-size: 2.5em;
    color: #ece8e8ef;
    padding-right: 9%;
  }
  .wrapper {
    height: 100vh;
    display: flex;
  }
  .myName {
    white-space: nowrap;
    overflow: hidden;
    font-family: monospace;
    font-size: 2.1em;
    color: #ff0000b8;
    padding-top: 0%;
    font-weight: 900;
    font-family: "proxima nova bold", "Helvetica Neue", Helvetica, Arial,
      Sans-serif;
  }

  @keyframes typing {
    from {
      width: 0;
    }
  }
}
</style>
