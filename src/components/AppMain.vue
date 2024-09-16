<script>
import FeatureSection from './FeatureSection.vue';

export default {
    components: {
        FeatureSection
    },
  data() {
    return {
      
    }
  }
}
</script>

<template>
<main class="container">
  <p> <strong>--> Content goes here <--</strong></p>
</main>

<FeatureSection />
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