<template>
  <div id="atomy">
    <img src="~assets/atomy.png" width="600px" height="500px;" />
    <h1 class="lightBlue">ATOMY</h1>
    <div class="lightBlue">
        <p>PT.Tirta Sarana Sukses is an Indonesian cider family company known for their apple cider called Tahesta. They want to adapt their management systems to the internet age. Atomy is what the system is called. They wanted to store every sales and storage data onto database. </p>
         <p>    I was tasked to build the software with 4 weeks deadline. I chose Electron.Js as the framework and MongoDB as the database. Why Electron.Js and MongoDB? because electron was the only "good" javascript to desktop apps by far and as for the database, i think noSQL was the better option for the bulk nature of sales and item storage data, MongoDB is fast and efficient due to not having relational schema. The project went very well, it was finished within 3 weeks, they were very happy with the development. For me, it was a very challengine task because I only had moderate knowledge about electron and mongodb. I learned as I go and was very happy with the result.</p>
        <p>Reference : Ronald, Director of PT.Tirta Sarana Sukes +62 818520429</p>
    </div>
  </div>
</template>

<style scoped>
h1{
    font-size: 40px;
}
p img{
    display: inline;
}
div p{
    color: white;
    text-align: justify;
}
#atomy {
  margin-left: 55vw;
  margin-top: 10vh;
  position: absolute;
  height: 50vh;
  width: 40vw;
}

#atomy img {
    padding-bottom: 50px;
  margin-left: 5vw;
}
</style>