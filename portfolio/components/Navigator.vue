<template>
  <nav class="columns">
    <div class="column" id="title">
      <nuxt-link class="link" to="/">HOME</nuxt-link>
    </div>
    <div class="column" id="about">
      <nuxt-link class="link sideway" to="/about">ABOUT</nuxt-link>
    </div>
    <div class="column" id="work">
      <nuxt-link class="link sideway" to="/work">WORKS</nuxt-link>
    </div>
    <div class="column" id="contact">
      <nuxt-link class="link" to="/contact">CONTACT</nuxt-link>
    </div>
  </nav>
</template>

<script>
export default {
  
}
</script>
<style scoped>
nav {
  margin-left: 4vw;
  z-index: 2;
  position: absolute;
}
.link {
  color: white;
}
#title {
  font-family: "Roboto", sans-serif;
  margin-top: 30px;
  font-size: 2.5rem;
}

.sideway {
  writing-mode: vertical-rl;
}
#about {
  font-family: "Roboto", sans-serif;
  margin-top: 50px;
  margin-left: 35vw;
  font-size: 1.75rem;
}

#work {
  font-family: "Roboto", sans-serif;
  margin-top: 80vh;
  margin-left: 15px;
  font-size: 1.75rem;
}

#contact {
  font-family: "Roboto", sans-serif;
  margin-top: 30px;
  font-size: 2.5rem;
  margin-left: 33vw;
}
</style>