<template>
  <section class="slider-area">
    <div class="slider-active slick-initialized slick-slider">
      <button class="slick-prev slick-arrow" @click="prev">
        <i class="fa fa-chevron-left"></i>
      </button>
      <div>
        <div class="slider-container">
          <single-slider-component
            v-for="(img, index) in imgs"
            :key="img"
            :index="index"
            :background="img"
            :visibleSlide="visibleSlide"
            :direction="direction"
          />
        </div>
      </div>
      <button class="slick-next slick-arrow" @click="next">
        <i class="fa fa-chevron-right"></i>
      </button>
    </div>
  </section>
</template>

<script>
import SingleSliderComponent from "./SingleSlideComponent.vue";

export default {
  name: "SliderComponent",
  components: {
    SingleSliderComponent,
  },
  data() {
    return {
      imgs: [
        "https://preview.colorlib.com/theme/capitalshop/assets/img/hero/h1_hero1.jpg.webp",
        "https://preview.colorlib.com/theme/capitalshop/assets/img/hero/h1_hero2.jpg.webp",
      ],
      visibleSlide: 0,
      direction: 'left'
    };
  },
  computed: {
    slidesLen() {
      return this.imgs.length
    }
  },
  methods: {
    next() {
      if(this.visibleSlide >= this.slidesLen -1) {
        this.visibleSlide = 0
      } else {
        this.visibleSlide++
      }
      this.direction = 'right'
    },
    prev() {
      if(this.visibleSlide <= 0) {
        this.visibleSlide = this.slidesLen -1
      } else {
        this.visibleSlide--
      }
      this.direction = 'left'
    }
  }
};
</script>

<style>
.slider-area {
  background-size: cover;
  background-repeat: no-repeat;
}

.slider-container {
  position: relative;
}

.slick-initialized .slick-slide {
  outline: 0;
}

.slider-area .hero-caption {
  text-align: center;
}

.slider-area .hero-caption span {
  color: var(--primary);
  font-family: "Clicker Script", cursive;
  font-size: 50px;
  line-height: 1.2;
  font-weight: 400;
  margin-bottom: 1px;
  display: block;
}

.slider-area .hero-caption h1 {
  font-size: 55px;
  font-weight: 500;
  color: #292621;
  line-height: 1.3;
  margin-bottom: 2px;
}

.slider-area .hero-caption p {
  color: #74706b;
  font-size: 18px;
  font-weight: 400;
  margin-bottom: 31px;
  padding: 0 50px;
}

.slider-active button.slick-arrow {
  -webkit-transition: all 0.4s ease-out 0s;
  -moz-transition: all 0.4s ease-out 0s;
  -ms-transition: all 0.4s ease-out 0s;
  -o-transition: all 0.4s ease-out 0s;
  transition: all 0.4s ease-out 0s;
  position: absolute;
  top: 50%;
  left: 0px;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
  background: none;
  border: 0;
  padding: 0;
  z-index: 2;
  height: 100px;
  width: 50px;
  cursor: pointer;
  background: rgba(41, 38, 33, 0.2);
}

.slider-active button.slick-arrow i {
  font-size: 20px;
  line-height: 60px;
}

.slider-active button.slick-next {
  left: auto;
  right: 0px;
}
</style>
