<template>
  <transition :name="direction" mode="in-out">
    <div
      v-if="visibleSlide === index"
      class="single-slider slider-height d-flex align-items-center"
      :style="{ backgroundImage: 'url(' + background + ')' }"
    >
      <div class="container">
        <div class="rowr">
          <div class="col-xxl-5 col-xl-6 col-lg-7 col-md-8 col-sm-10">
            <div class="hero-caption text-center">
              <span>Fashion Sale</span>
              <h1>Minimal Menz Style</h1>
              <p>
                Consectetur adipisicing elit. Laborum fuga incidunt laboriosam
                voluptas iure, delectus dignissimos facilis neque nulla earum.
              </p>
              <a href="#" class="btn_1 hero-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </transition>
</template>

<script>
export default {
  props: {
    background: {
      type: String,
    },
    visibleSlide: {
      type: Number,
    },
    index: {
      type: Number,
    },
    direction: {
      type: String,
    },
  },
};
</script>
<style>
.single-slider {
  position: relative;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}

.slider-height {
  min-height: 700px;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}

.left-enter-active {
  animation: leftInAnimation 0.4s ease-in-out;
}
.left-leave-active {
  animation: leftOutAnimation 0.4s ease-in-out;
}

@keyframes leftInAnimation {
  from {
    transform: translateX(100%);
  }
  to {
    transform: translateX(0%);
  }
}

@keyframes leftOutAnimation {
  from {
    transform: translateX(0%);
  }
  to {
    transform: translateX(-100%);
  }
}

.right-enter-active {
  animation: rightInAnimation 0.4s ease-in-out;
}
.right-leave-active {
  animation: rightOutAnimation 0.4s ease-in-out;
}

@keyframes rightInAnimation {
  from {
    transform: translateX(-100%);
  }
  to {
    transform: translateX(0%);
  }
}

@keyframes rightOutAnimation {
  from {
    transform: translateX(0%);
  }
  to {
    transform: translateX(100%);
  }
}
</style>