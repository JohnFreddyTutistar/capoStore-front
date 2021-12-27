<template>
<div>
    <header-component />
  <main>
    <slider-component />
    <categories-component/>
  </main>
</div>
  
</template>

<script>
import HeaderComponent from "../components/HeaderComponent.vue";
import SliderComponent from "../components/SliderComponent.vue";
import CategoriesComponent from "../components/CategoriesComponent.vue"
export default {
  components: {
    HeaderComponent,
    SliderComponent,
    CategoriesComponent
  },
};
</script>

<style>
</style>