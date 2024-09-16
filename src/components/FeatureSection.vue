<script>
export default {
  data() {
    return {
      listLink: [
        {
          name: "DIGITAL COMICS",
          src: '/img/buy-comics-digital-comics.png',
          alt: "Digital Comic"
        },
        {
          name: "DC MERCHANDISE",
          src: '/img/buy-comics-merchandise.png',
          alt: "DC Merchandise"
        },
        {
          name: "SUBSCRIPTION",
          src: '/img/buy-comics-subscriptions.png',
          alt: "Subscription"
        },
        {
          name: "COMIC SHOP LOCATOR",
          src: 'img/buy-comics-shop-locator.png',
          alt: "Comic Shop Locator"
        },
        {
          name: "DC POWER VISA",
          src: '/img/buy-dc-power-visa.svg',
          alt: "DC Power VISA"
        }
      ]
    }
  }
}
</script>

<template>
  <section class="feature-section">
    <div class="container">
      <div v-for="itemLink in listLink">
        <img :src="itemLink.src" :alt="itemLink.alt">
        <p>{{ itemLink.name }}</p>
      </div>
    </div>

  </section>
</template>

<style lang="scss" scoped>
.feature-section{
  background-color: #0082f9;
  padding: 40px 0 40px 0;
  .container{
    display: flex;
    justify-content: space-around;
    img{
      height: 40px;
      margin-right: 10px;
    }
    p{
      color: white;
      font-size: 12px;
    }
    div{
      display: flex;
      align-items: center;
      cursor: pointer;
    }
  }

}
</style>