<template>
  <div>
    <VueSlickCarousel :arrows="true" :dots="true">
      <div>872364985723095723</div>
      <div>kjdgfkjsdhkgfsd</div>
      <div>jdd</div>
      <div class="img">
        <img src="../assets/sky.jpeg" alt="waaat" />
      </div>
    </VueSlickCarousel>
  </div>
</template>
<style>
img {
  max-width: 200px;
  max-height: 200px;
}
</style>

<script>
import VueSlickCarousel from "vue-slick-carousel";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "MyComponent",
  components: { VueSlickCarousel },
};
</script>
