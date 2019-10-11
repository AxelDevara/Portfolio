<template>
  <nav class="columns">
    <div class="column" id="work">
      <a href="#works">WORKS</a>
    </div>
    <div class="column" id="about">
      <a href="#aboutme">ABOUT</a>
    </div>

    <div class="column" id="contact">
      <a href="#Contact">CONTACT</a>
    </div>
  </nav>
</template>

<script>
export default {};
</script>
<style scoped>
a {
  color: black;
}

nav {
  margin-left: 4vw;
  z-index: 2;
  position: absolute;
}

#about {
  font-family: "Roboto", sans-serif;
  margin-top: 5vh;
  margin-left: 5vw;
  font-weight: 100;
  font-size: 1.5vw;
}

#contact {
  font-family: "Roboto", sans-serif;
  margin-top: 5vh;
  margin-left: 5vw;
  font-weight: 100;
  font-size: 1.5vw;
}

#work {
  font-family: "Roboto", sans-serif;
  margin-top: 5vh;
  font-weight: 100;
  font-size: 1.5vw;
  margin-left: 5vw;
}
</style>