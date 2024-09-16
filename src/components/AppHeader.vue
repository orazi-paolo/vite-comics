<script>
export default {
  data() {
    return {
        navbarHeader: [
            "Characters",
            "Comics",
            "Movies",
            "Tv",
            "Games",
            "Collectibles",
            "Videos",
            "Fans",
            "News",
            "Shop"
        ]
      
    }
  }
}
</script>

<template>
    <header>
        <div class="container">
            <div class="col">
                <img src="../assets/img/favicon.ico" alt="Main logo">
            </div>
            <div class="navbar">
                <ul>
                    <li v-for="navItem in navbarHeader">
                        <a href="#"> {{ navItem }}</a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header{
    background-color: white;
    padding: 30px 0 30px 0;
    .container{
        display: flex;
        justify-content: space-between;
    }
    
    img{
        height: 70px;
    }
    .navbar{
        display: flex;
        align-items: center;
        justify-content: center;
        ul{
            display: flex;
            flex-wrap: wrap;
           flex-direction: row;
           align-items: center;
           justify-content: center;
           li{
            margin-right: 40px;
            text-align: center;
               a{
                   color: #4a4647;
                   &:hover{
                    color: blue;
                   }
               }
           }
        }
    }
}
</style>