<template>
<main>
  <Navigator/>
    <Logo/>
  <PageBg/>
  
</main>
  
</template>

<script>
import PageBg from '~/components/PageBg.vue'
import Logo from '~/components/Logo.vue'
import Navigator from '~/components/Navigator.vue'


export default {
  components: {
    PageBg,
    Navigator,
    Logo
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
