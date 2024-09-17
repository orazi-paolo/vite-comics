<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
    <section class="jumbotron">
        <div class="container">
            <button class="button-base"><strong>CURRENT SERIES</strong></button>
        </div>
    </section>

</template>

<style lang="scss" scoped>
section.jumbotron{
    height: 300px;
    background-image: url(/public/img/jumbotron.jpg);
    background-size: cover;
    div{
        position: relative;
        height: 100%;
        button{
            font-size: 16px;
            padding: 10px 20px;
            position: absolute;
            bottom: -20px;
            left: 0;
            cursor: pointer;
        }
    }
}
</style>