<template>
  <div class="categories-area">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 colmd-6 col-sm-6">
          <div
            class="single-cat mb-50 wow fadeInUp text-center"
            data-wow-duration="1s"
            data-wow-delay=".2s"
          >
            <div class="cat-icon">
              <img
                src="https://preview.colorlib.com/theme/capitalshop/assets/img/icon/services1.svg"
                alt=""
              />
            </div>
            <div class="cat-cap">
              <h5>Fast & Free Delivery</h5>
              <p>Free delivery on all orders</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 colmd-6 col-sm-6">
          <div
            class="single-cat mb-50 wow fadeInUp text-center"
            data-wow-duration="1s"
            data-wow-delay=".2s"
          >
            <div class="cat-icon">
              <img
                src="https://preview.colorlib.com/theme/capitalshop/assets/img/icon/services2.svg"
                alt=""
              />
            </div>
            <div class="cat-cap">
              <h5>Secure Payment</h5>
              <p>Free delivery on all orders</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 colmd-6 col-sm-6">
          <div
            class="single-cat mb-50 wow fadeInUp text-center"
            data-wow-duration="1s"
            data-wow-delay=".2s"
          >
            <div class="cat-icon">
              <img
                src="https://preview.colorlib.com/theme/capitalshop/assets/img/icon/services3.svg"
                alt=""
              />
            </div>
            <div class="cat-cap">
              <h5>Money Back Guarantee</h5>
              <p>Free delivery on all orders</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 colmd-6 col-sm-6">
          <div
            class="single-cat mb-50 wow fadeInUp text-center"
            data-wow-duration="1s"
            data-wow-delay=".2s"
          >
            <div class="cat-icon">
              <img
                src="https://preview.colorlib.com/theme/capitalshop/assets/img/icon/services4.svg"
                alt=""
              />
            </div>
            <div class="cat-cap">
              <h5>Online Support</h5>
              <p>Free delivery on all orders</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: "Guarantee"
};
</script>

<style>
.categories-area .single-cat {
    -webkit-transition: all .4s ease-out 0s;
    -moz-transition: all .4s ease-out 0s;
    -ms-transition: all .4s ease-out 0s;
    -o-transition: all .4s ease-out 0s;
    transition: all .4s ease-out 0s;
    z-index: 1;
    position: relative;
}

.mb-50 {
    margin-bottom: 50px;
}

.mb-35 {
    margin-bottom: 35px;
}

.categories-area .single-cat .cat-icon img {
    margin-bottom: 26px;
    display: inline-block;
}

.cat-cap h5 {
    font-size: 20px;
    font-weight: 500;
    margin-bottom: 12px;
    display: block;
    text-transform: capitalize;
    color: #2b2b2b;
    font-family: "Jost",sans-serif;
}

.categories-area .single-cat .cat-cap p {
    color: #57667e;
    font-size: 16px;
    -webkit-transition: all .2s ease-out 0s;
    -moz-transition: all .2s ease-out 0s;
    -ms-transition: all .2s ease-out 0s;
    -o-transition: all .2s ease-out 0s;
    transition: all .2s ease-out 0s;
}
</style>