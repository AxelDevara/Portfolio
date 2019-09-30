<template>
  <div id="position">
    <div class="columns">
      <div class="column is-8">
        <img src="~assets/atha.png" width="500px" height="300px" alt />
      </div>
      <div class="column" id="text">
        <p class="lightBlue"><span >Strong and bold monotone color </span></p>
        <p>Designed to immerse viewer with intimate theme color</p>
     
        
        <p></p>
      </div>
    </div>
    <div class="columns">
      <div class="column"><h1>Project took 15 days to design and create the base using Nuxt.js and Strapi as the CMS</h1></div>
      <div class="column is-7"><img src="~assets/athalia2.jpg" width="400px" height="200px" alt /></div>
    </div>
  </div>
</template>

<style scoped>
h1{
  padding-top: 80px;
}
#text{
  padding-top: 13%;
}
div{
  color: #aeb6b9;
}
.lightBlue:hover span{
  display: none;
}
.lightBlue:hover::before{
  content: "Dividing details between contents and focal point with 3 tones red, black, and white";
}
p {
  font-family: "Roboto 300", sans-serif;

  display: inline-block;
}
#position {
  margin-left: 55vw;
  margin-top: 20vh;
  position: absolute;
  height: 50vh;
  width: 40vw;
}
</style>