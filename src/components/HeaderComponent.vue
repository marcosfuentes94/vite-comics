<script>
export default {
name: "HeaderComponent",
data(){
  return{

  }
},
methods: {

}
}
</script>

<template>
  <header>
      <div class="container">
  
        <div class="header-top">
            <div class="logo-container">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>

            <div class="links">
                <ul>
                  <li>
                      <a href="#">
                          CHARACTERS
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          COMICS
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          MOVIES
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          TV
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          GAMES
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          COLLECTIBLES
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          VIDEOS
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          FANS
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          NEWS
                      </a>
                  </li>
                  <li>
                      <a href="#">
                          SHOP
                      </a>
                  </li>
                </ul>
            </div>
        </div>
      </div>
    </header>
</template>

<style lang="scss" scoped>
header{
height: 70px;
padding: 10px 0;
margin-top: 20px;
}
.header-top{
display: flex;
flex-wrap: nowrap;
justify-content: space-between;
align-items: center;
}

ul{
font-size: 0.7em;

li{
  display: inline-block;
  padding: 0 10px;
}
a{
  color: black;
  text-decoration: none;
  text-transform: uppercase;
  font-weight: bold;
}
}

.logo-container{
height: 60px;
width: 60px;
margin-left: 300px;


img{
width: 100%;
}
}
</style>