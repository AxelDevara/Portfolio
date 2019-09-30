<template>
  <div id="atomy">
    <div class="columns">
      <div class="column is-7">
        <img src="~assets/atomy.png" width="600px" height="500px;" />
      </div>
      <div class="column" id="first">
        <p>
          <span>This is my work on backend focused project. PT.Tirta Sarana Sukses is an Indonesian cider family company known for their apple cider called Tahesta. They want to adapt their management systems to the automation.</span>
        </p>
      </div>
    </div>
    <div class="columns">
      <div class="column is-2">
        <img src="~assets/Electron.png" width="100px" height="100px;" />
      </div>
      <div class="column is-2" id="mongo">
        <img src="~assets/MongoDB.png" width="100px" height="100px;" />
      </div>

      <div class="column">
        <p id="desc">
          <span>Atomy is what the system is called. They wanted to store every sales and storage data onto database. I was tasked to build the software with 4 weeks deadline. I chose Electron.Js as the framework and MongoDB as the database.</span>
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
p {
  font-family: "Roboto 300", sans-serif;
}

#mongo{
  padding-top: 40px;
}
.is-2 img{
  padding-top: 80px;
}
#desc:hover span {
  display: none;
}
#desc:hover::before {
  content: "Why Electron.Js and MongoDB? because electron was the only 'good' javascript to desktop apps by far and as for the database, i think noSQL was the better option for the bulk nature of sales and item storage data, MongoDB is fast and efficient due to not having relational schema. The project went very well, it was finished within 3 weeks, they were very happy with the development. For me, it was a very challengine task because I only had moderate knowledge about electron and mongodb. I learned as I go and was very happy with the result.";
}

.column p {
  padding-top: 17%;
}
p img {
  display: inline;
}
div {
  color: #aeb6b9;
}
#first p {
  text-align: justify;
}
#atomy {
  margin-left: 55vw;
  margin-top: 20vh;
  position: absolute;
  height: 50vh;
  width: 40vw;
}

#atomy img {
  align-content: center;
  padding-bottom: 50px;
}
</style>