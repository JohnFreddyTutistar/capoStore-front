<template>
  <section class="slider-area">
    <div class="slider-active slick-initialized slick-slider">
      <button class="slick-prev slick-arrow" id="first-slider-prev">
        <i class="fa fa-chevron-left"></i>
      </button>
      <div class="slick-list draggable">
        <div class="slick-track owl-carousel owl-theme">
          <div
            class="
              single-slider
              slider-bg1 slider-height
              d-flex
              align-items-center
              slick-slide
            "
          >
            <div class="container">
              <div class="rowr">
                <div class="col-xxl-5 col-xl-6 col-lg-7 col-md-8 col-sm-10">
                  <div class="hero-caption text-center">
                    <span>Fashion Sale</span>
                    <h1
                      data-animation="bounceIn"
                      data-delay="0.2s"
                      class
                      style="animation-delay: 0.2s"
                    >
                      Minimal Menz Style
                    </h1>
                    <p
                      data-animation="fadeInUp"
                      data-delay="0.4s"
                      class=""
                      style="animation-delay: 0.4s"
                    >
                      Consectetur adipisicing elit. Laborum fuga incidunt
                      laboriosam voluptas iure, delectus dignissimos facilis
                      neque nulla earum.
                    </p>
                    <a
                      href="#"
                      class="btn_1 hero-btn"
                      data-animation="fadeInUp"
                      data-delay="0.7s"
                      tabindex="-1"
                      style="animation-delay: 0.7s"
                      >Shop Now</a
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!--Slider 2-->
          <div
            class="
              single-slider
              slider-bg2 slider-height
              d-flex
              align-items-center
              slick-slide
            "
          >
            <div class="container">
              <div class="rowr">
                <div class="col-xxl-5 col-xl-6 col-lg-7 col-md-8 col-sm-10">
                  <div class="hero-caption text-center">
                    <span>Fashion Sale</span>
                    <h1
                      data-animation="bounceIn"
                      data-delay="0.2s"
                      class
                      style="animation-delay: 0.2s"
                    >
                      Minimal Menz Style
                    </h1>
                    <p
                      data-animation="fadeInUp"
                      data-delay="0.4s"
                      class=""
                      style="animation-delay: 0.4s"
                    >
                      Consectetur adipisicing elit. Laborum fuga incidunt
                      laboriosam voluptas iure, delectus dignissimos facilis
                      neque nulla earum.
                    </p>
                    <a
                      href="#"
                      class="btn_1 hero-btn"
                      data-animation="fadeInUp"
                      data-delay="0.7s"
                      tabindex="-1"
                      style="animation-delay: 0.7s"
                      >Shop Now</a
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <button class="slick-next slick-arrow" id="first-slider-next">
        <i class="fa fa-chevron-right"></i>
      </button>
    </div>
  </section>
</template>

<script>
export default {
    name: 'SliderComponent'
};
</script>

<style>
.slider-area {
  background-size: cover;
  background-repeat: no-repeat;
}

.slick-initialized .slick-slide {
  outline: 0;
}

.slider-bg1 {
  background-image: url(https://preview.colorlib.com/theme/capitalshop/assets/img/hero/h1_hero1.jpg.webp);
}
.slider-bg2 {
  background-image: url(https://preview.colorlib.com/theme/capitalshop/assets/img/hero/h1_hero2.jpg.webp);
}

.slider-height {
  min-height: 700px;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
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
