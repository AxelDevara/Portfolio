<template>
 <nav class="columns">
     <div class="column" id="title">
         <nuxt-link class="link" to="/">Home</nuxt-link>
     </div>
     <div class="column" id="about">
         <nuxt-link class="link sideway" to="/">About</nuxt-link>
     </div>
      <div class="column" id="work">
         <nuxt-link class="link sideway" to="/">Works</nuxt-link>
     </div>
     <div class="column" id="contact">
         <nuxt-link class="link" to="/">Contact</nuxt-link>
     </div>
 </nav>
</template>

<style scoped>
nav{
    margin-left: 4vw;
    z-index: 2;
    position: absolute;
}
.link{
    color: white;
}
#title {
    margin-top: 30px;
  font-size: 2.5rem;
}

.sideway{
    writing-mode: vertical-rl;
}
#about{
    margin-top: 50px;
    margin-left: 35vw;
  font-size: 1.75rem;
}

#work{
    margin-top: 80vh;
    margin-left: 15px;
      font-size: 1.75rem;
}

#contact{
    margin-top: 30px;
      font-size: 2.5rem;
      margin-left: 33vw;
}

</style>