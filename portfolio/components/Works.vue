<template>
  <div id="position">
    <div class="columns">
      <div class="column is-6">
        <div class="animated slideInDown" id="atomy">
          <nuxt-link to="/atomy" class="title">Atomy</nuxt-link>
          <p>Desktop application project using Electron.Js as backend administration system for Indonesian company, PT.Tirta Sarana Sukses.</p>
        </div>
      </div>
      <div class="column is-6">
        <div class="animated slideInDown" id="athalia">
          <nuxt-link class="title" to="/athalia">Athalia</nuxt-link>
          <p>Part of my freelancing project. I designed a fashion/digital marketing website for a friend of mine. Featuring simplicity, strong, and bold color, I challenged myself to be efficient using whitespaces and engaging "Art as Marketing" aspect into my design.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
#atomy {
  text-align: justify;
  animation-duration: 3s;
}
#athalia {
  text-align: justify;
  animation-duration: 4s;
}

.title {
  color: black;
}

.tile p {
  color: black;
}
#position {
  z-index: 3;
  margin-left: 31%;
  margin-top: 15vh;
  width: 40vw;
}
</style>