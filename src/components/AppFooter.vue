<script>
import SignUpNavbar from './SignUpNavbar.vue';

export default {
    components: {
        SignUpNavbar
    },
  data() {
    return {
      dcComicsList: [
        "Characters",
        "Comics",
        "Movies",
        "TV",
        "Games",
        "Videos",
        "News"
      ],
      shopList: [
        "Shop DC",
        "Shop DC Collectibles",
      ],
      dcList: [
        "Terms Of Use",
        "Privacy policy (New)",
        "Ad Choices",
        "Advertising",
        "Jobs",
        "Subscriptions",
        "Talent Workshops",
        "CPSC Certificates",
        "Ratings",
        "Shop Help",
        "Contact Us"
      ],
      sitesList: [
        "DC",
        "MAD Magazine",
        "DC Kids",
        "DC Universe",
        "DC Power Visa"
      ]
      
    }
  }
}
</script>

<template>
  <footer>
    <section class="main-footer container">
      <div>
        <h5>DC COMICS</h5>
        <ul>
          <li v-for="dcComicsItem in dcComicsList">
            <a href="#">{{ dcComicsItem }}</a>
          </li>
        </ul>
        <h5>SHOP</h5>
        <ul>
          <li v-for="shopListItem in shopList">
            <a href="#">{{ shopListItem }}</a>
          </li>
        </ul>
      </div>
      <div>
        <h5>DC</h5>
        <ul>
          <li v-for="dcItem in dcList">
            <a href="#">{{ dcItem }}</a>
          </li>
        </ul>
      </div>
      <div>
        <h5>SITES</h5>
        <ul>
          <li v-for="sitesItem in sitesList">
            <a href="#">{{ sitesItem }}</a>
          </li>
        </ul>
      </div>
      <div class="background-logo">
      </div>
    </section>

    <SignUpNavbar />
  </footer>


</template>

<style lang="scss" scoped>
footer{
  background-image: url(/img/footer-bg.jpg);
  .main-footer{
    height: 300px;
    display: flex;
    justify-content: space-between;
      h5{
        color: white;
        margin: 20px 0 10px;
      }
        
        a{
          color: gray;
          font-size: 10px;
          &:hover{
            color: lightblue;
          }
        }
    .background-logo{
      height: 300px;
      width: 50%;
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      background-image: url(/img/dc-logo-bg.png);
    }
  }
}
</style>