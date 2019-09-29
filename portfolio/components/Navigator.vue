<template>
  <nav class="columns">
    <div class="column" id="title">
      <nuxt-link class="link" to="/">HOME</nuxt-link>
    </div>
    <div class="column" id="about">
      <nuxt-link class="link" to="/about">ABOUT</nuxt-link>
    </div>
    <div class="column" id="contact">
      <nuxt-link class="link" to="/contact">CONTACT</nuxt-link>
    </div>
    <div class="column" id="work">
      <div class="navbar-item has-dropdown is-hoverable">
        <nuxt-link class="link" to="/">WORKS</nuxt-link>
        <div class="navbar-dropdown">
          <nuxt-link to="/athalia" class="navbar-item">Athalia</nuxt-link>
          <nuxt-link to="/atomy" class="navbar-item">Atomy</nuxt-link>
          <nuxt-link to="/mobile" class="navbar-item">Mobile Design</nuxt-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
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

#about {
  font-family: "Roboto", sans-serif;
  margin-top: 45px;
  margin-left: 5vw;
  font-size: 1.25rem;
}

#contact {
  font-family: "Roboto", sans-serif;
  margin-top: 45px;
  margin-left: 5vw;
  font-size: 1.25rem;
}

#work {
  font-family: "Roboto", sans-serif;
  margin-top: 45px;
  font-size: 1.25rem;
  margin-left: 5vw;
}
</style>