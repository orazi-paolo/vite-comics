<script>
export default {
  data() {
    return {
      listSocial: [
        {
          name: 'Facebook',
          src:'/img/footer-facebook.png'
        },
        {
          name: 'Twitter',
          src:'/img/footer-twitter.png'
        },
        {
          name: 'Youtube',
          src:'/img/footer-youtube.png'
        },
        {
          name: 'Pinterest',
          src:'/img/footer-pinterest.png'
        },
        {
          name: 'Periscope',
          src:'/img/footer-periscope.png'
        }
      ]
    }
  }
}
</script>

<template>
  <div class="navbar-footer">
    <div class="container">
      <button type="button">SIGN-UP NOW!</button>
      <div class="nav-footer">
        <p>FOLLOW US</p>
        <a href="#" v-for="listSocialItem in listSocial"><img :src=listSocialItem.src :alt=listSocialItem.name></a>
      </div>

    </div>
  </div>
  
</template>

<style scoped>
.navbar-footer{
  background-color: #303030;
  padding: 40px 0 40px 0;
    .container{
      display: flex;
      justify-content: space-between;
      button{
        border-color: #0082f9;
        background-color: #303030;
        padding: 10px;
        color: white;
        cursor: pointer;
      }
      .nav-footer{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 30%;
        p{
          color: #0082f9;
          font-weight: bold;
        }
        img{
          height: 30px;
        }
      }
    }

}
</style>