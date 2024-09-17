<script>
// importo tutti i file interessati nell app principale
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
    return {
      
    }
  }
}
</script>

<template>

    <AppHeader />
    <AppMain />
    <AppFooter /> 
    
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'Open Sans', sans-serif;
  background-color: black;
}
.container{
  max-width: 1180px;
  margin: 0 auto;
}
a{
  text-decoration: none; 
}
ul{
  list-style-type: none;
}
.button-base{
  background-color: #0082f9;
  color: white;

}
</style>