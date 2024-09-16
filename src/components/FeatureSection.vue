<script>
export default {
  data() {
    return {
    }
  }
}
</script>

<template>
  <section class="feature-section">
    <div class="container">
      <div>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
        <p>DIGITAL COMICS</p>
      </div>
      <div>
        <img src="../assets/img/buy-comics-merchandise.png" alt="DC Merchandise">
        <p>DC MERCHANDISE</p>
      </div>
      <div>
        <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
        <p>SUBSCRIPTION</p>
      </div> 
      <div>
        <img src="../assets/img/buy-comics-shop-locator.png" alt="Comic Shop Locator">
        <p>COMIC SHOP LOCATOR</p>
      </div>
      <div>
        <img src="../assets/img/buy-dc-power-visa.svg" alt="DC Power VISA">
        <p>DC POWER VISA</p>
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