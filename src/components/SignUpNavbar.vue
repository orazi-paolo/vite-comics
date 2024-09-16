<script>
export default {
  data() {
    return {
      
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
        <a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a>
        <a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a>
        <a href="#"><img src="../assets/img/footer-youtube.png" alt="Youtube"></a>
        <a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a>
        <a href="#"><img src="../assets/img/footer-periscope.png" alt="Periscope"></a>
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