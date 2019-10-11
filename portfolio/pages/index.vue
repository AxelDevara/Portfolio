<template>
  <main>
    <div class="top">
      <Navigator />
      <Logo />
    </div>
    <div class="works" id="works">
      <div style="height:10vh;"></div>
      <div class="columns" id="nav">
        <div class="column is-4"></div>
        <div class="column is-4">
          <div class="columns">
            <div class="column">
              <nuxt-link class="link" to="/Athalia">Athalia</nuxt-link>
            </div>
            <div class="column">
              <nuxt-link class="link" to="/Atomy">Atomy</nuxt-link>
            </div>
            <div class="column">
              <nuxt-link class="link" to="/3D">3D Designs</nuxt-link>
            </div>
          </div>
        </div>
        <div class="column is-4"></div>
      </div>
      <nuxt-child />
      <Works v-if="$route.path === '/'" />
    </div>
    <div id="aboutme" style="height:120vh;">
      <About/>
    </div>
    <div id="Contact" style="background-color:black; height:100vh;">
      <Contact/>
    </div>
  </main>
</template>

<script>
import Atomy from "~/components/Navigator/Atomy.vue";
import Works from "~/components/Works.vue";
import Logo from "~/components/Logo.vue";
import Navigator from "~/components/Navigator.vue";
import About from "~/components/about.vue";
import Contact from "~/components/contact.vue";

export default {
  components: {
    Navigator,
    Works,
    About,
    Atomy,
    Logo,
    Contact
  },
  methods() {}
};
</script>

<style scoped>
body,
html {
  width: 100vw;
  margin: 0;
}
#nav {
  font-size: 1vw;
  margin-top: 15vh;
  text-align: center;
}

.top {
  background-image: url("~assets/background.jpg");
  height: 100vh;
}
.works {
  height: 100vh;
}
</style>
