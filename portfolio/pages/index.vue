<template>
<main>
  <Navigator/>
  <nuxt-child />
  <Works v-if="$route.path === '/'"/>
    <Logo/>
  <PageBg/>
  
</main>
  
</template>

<script>
import Atomy from '~/components/Navigator/Atomy.vue'
import Works from '~/components/Works.vue'
import PageBg from '~/components/PageBg.vue'
import Logo from '~/components/Logo.vue'
import Navigator from '~/components/Navigator.vue'


export default {
  components: {
    PageBg,
    Navigator,
    Works,
    Atomy,
    Logo
  },
  methods(){

  }
}
</script>

<style>
body, html{
  background-color: #3DBEEF;
    width:100vw;
    margin: 0;
    height: 100vh;
    overflow:hidden;
}




</style>
