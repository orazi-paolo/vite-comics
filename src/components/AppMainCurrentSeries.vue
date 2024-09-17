<script>
export default {
  data() {
    return {
      
    }
  },
  props: {
    thumbImageUrl: {
      type: String,
      required: true
    },
    thumbPrice: {
      type: String,
      required: false
    },
    thumbSeries: {
      type: String,
      required: true
    },
    thumbType: {
      type: String,
      required: false
    }
  }
}
</script>

<template>
        <div class="thumb">
            <img :src="thumbImageUrl" :alt="thumbSeries" />
            <p>{{ thumbSeries }}</p>
        </div>
</template>

<style lang="scss" scoped>
    .thumb{
        height: 150px;
        width: calc((100% / 6) - 20px);
        text-align: center;
        img{
            height: 100px;
            width: 100%;
            object-fit: cover;
            object-position: top;
       }
        p{
            color: white;
            text-align: center;
        }
    }
</style>