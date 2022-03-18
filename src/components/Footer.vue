<template>
  <div>
    <footer>
      <p>
        © 2021 Copyright Nande Bija <br />

        <span class="hov"
          ><a
            href="https://za.linkedin.com/"
            target="_blank"
            class="fa fa-linkedin"
          ></a
        ></span>
        <span class="hov"
          ><a
            href="https://github.com/"
            target="_blank"
            class="fa fa-github"
          ></a
        ></span>
      </p>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

p {
  padding-top: 9px;
}
a {
  text-decoration: none;
}
.hov a {
  padding-left: 15px;
}
a:hover {
  padding-left: 15px;
  color: #fc5356;
}
@media screen and (max-width: 600px) {
  p {
    padding-top: 9px;
  }
}
</style>
