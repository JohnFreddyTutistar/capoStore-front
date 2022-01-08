<template>
<div>
    <header-component />
  <main>
    <slider-component />
    <categories-component/>
    <latest-items-component/>
    <recomendations-component/>
    <guarantee-component/>
  </main>
  <footer-component/>
</div>
  
</template>

<script>
import HeaderComponent from "../components/HeaderComponent.vue";
import SliderComponent from "../components/SliderComponent.vue";
import CategoriesComponent from "../components/CategoriesComponent.vue";
import LatestItemsComponent from "../components/LatestItemsComponent.vue";
import RecomendationsComponent from "../components/RecomendationsComponent.vue";
import GuaranteeComponent from "../components/GuaranteeCompontent.vue";
import FooterComponent from "../components/FooterComponent.vue";

export default {
  components: {
    HeaderComponent,
    SliderComponent,
    CategoriesComponent,
    LatestItemsComponent,
    RecomendationsComponent,
    GuaranteeComponent,
    FooterComponent
  },
};
</script>

<style>
</style>