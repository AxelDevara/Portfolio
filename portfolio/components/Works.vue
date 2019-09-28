<template>
  <div id="position">
    <div class="tile is-ancestor">
      <div class="tile is-4 is-vertical is-parent">
        <div class="tile is-child animated slideInDown" id="atomy">
          <nuxt-link to="/atomy" class="title">Atomy</nuxt-link>
          <p>Desktop application project using Electron.Js as backend administration system for Indonesian company, PT.Tirta Sarana Sukses.</p>
        </div>
        <div class="tile is-child animated slideInDown" id="mobile">
          <nuxt-link to="/mobile"><p class="title">Mobile Design</p></nuxt-link>
          <p>I do mobile application design on my spare time. I like the interactivity we can develop onto mobile application. Flutter has been my go-to framework.</p>
        </div>
      </div>
      <div class="tile is-parent">
        <div class="tile is-child animated slideInDown" id="athalia">
          <nuxt-link to="/athalia"><p class="title">Athalia</p></nuxt-link>
          <p>Part of my freelancing project. I designed a fashion/digital marketing website for a friend of mine. Featuring simplicity, strong, and bold color, I challenged myself to be efficient using whitespaces and engaging "Art as Marketing" aspect into my design.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
#atomy{
      animation-duration: 3s;
}
#athalia{
      animation-duration: 4s;
}
#mobile{
      animation-duration: 2s;

}
.title{
    color: #AEB6B9;
}

.tile p{
    color: #AEB6B9;
}
#position{
    margin-left: 55vw;
    margin-top:25vh;
    position: absolute;
    height: 50vh;
    width: 40vw;
}
</style>