<template>
  <div id="position">
   <h1><span>I LOVE <strong>WEB</strong></span></h1>
    <h3 id="me"><span>I taught myself <strong>design and programming</strong> since I was 15</span></h3>
    <h2><span>Decided to study and move to <strong>Melbourne</strong></span></h2>
     <h3 id="career"><span>To pursue <strong>career and passion</strong></span></h3>
  </div>
</template>

<style scoped>
div{
    font-family: "Roboto 300", sans-serif;
}
h3{
  font-size: 2.5vw;
}
h2{
  font-size: 3.6vw;
}
a{
  color: #aeb6b9;
}
h1{
  font-size:5vw;
}

strong{
  color: #3DBEEF;
}
h1:hover span{
  display: none;
}
h1:hover::before{
  content: "REALLY LOVE IT";
}
h2:hover span{
  display: none;
}
h2:hover::before{
  content: "I was from Surabaya, Indonesia. Born and raised :)";
}
#me:hover span{
  display: none;
}
#me:hover::before{
  content: "I wanted to build my own kind of facebook!"
}
#career:hover span{
  display: none;
}
#career:hover::before{
  content: "Contact me, I'd be happy to work together!"
}
#position {
  color: white;
  margin-left: 55vw;
  margin-top: 15vh;
  position: absolute;
  height: 50vh;
  width: 40vw;
}
</style>