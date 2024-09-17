<script>
import AppMainFeatureSection from './AppMainFeatureSection.vue';
import AppMainJumbotron from './AppMainJumbotron.vue';

export default {
    components: {
        AppMainFeatureSection,
        AppMainJumbotron
    },
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <AppMainJumbotron />
<main class="container">
  <p> <strong>--> Content goes here <--</strong></p>
</main>

<AppMainFeatureSection />
</template>

<style lang="scss" scoped>
main{
  padding: 40px 0 40px 0;
  p{
    color: white;
    font-size: 24px;
  }
}
</style>