<template>
  <div id="logo">
    <p id="Heading"><span>//HELLO WORLD</span></p>
    <!-- <p class="primary" id="nonHeading"><span>Full Stack Web Developer</span></p> -->
  </div>
</template>

<script>
export default {
  head() {
    return {
      link: [
        {
          rel: "stylesheet",
          href: "https://fonts.googleapis.com/css?family=Roboto&display=swap"
        },
        {
          rel: "stylesheet",
          href:
            "https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.css"
        }
      ],
      methods: {
        
      },
    };
  }
};
</script>

<style scoped>

/* #nonHeading {
  font-family: 'Roboto 400', sans-serif;
  padding-top: 3vh;
  font-size: 25px;
} */

#Heading {
  animation: slideInDown 1s;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  margin-left: 4.5vw;
  margin-top: 12vh;
  font-size: 4VW;
}

/* #nonHeading:hover span{
  display: none;
}
#nonHeading:hover::before{
  content: "UI/UX Designer";
} */

#Heading:hover span{
  display: none;
}
#Heading:hover::before{
  content: "//Welcome to my portfolio";
}
#logo {
  z-index: 3;
  position: absolute;
  margin-top: 25vh;
  margin-left: 5vw;
}
</style>

