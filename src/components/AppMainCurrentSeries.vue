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
            <p>{{ thumbSeries.toUpperCase() }}</p>
        </div>
</template>

<style lang="scss" scoped>
    .thumb{
        height: 250px;
        width: calc((100% / 6) - 20px);
        text-align: center;
        cursor: pointer;
        img{
            height: 200px;
            width: 100%;
            object-fit: contain;
            object-position: top;
       }
        p{
            color: white;
            text-align: center;
            padding-top: 10px;
            font-size: 12px;
        }
    }
</style>