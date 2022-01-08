<template>
  <footer>
    <div class="footer-wrapper gray-bg">
      <div class="footer-area footer-padding">
        <section class="subscribe-area">
          <div class="container">
            <div class="row justify-content-between subscribe-padding">
              <div class="col-xxl-3 col-xl-3 col-lg-4">
                <div class="subscribe-caption">
                  <h3>Subscribe Newsletter</h3>
                  <p>Subscribe newsletter to get 5% on all products.</p>
                </div>
              </div>
              <div class="col-xxl-3 col-xl-3 col-lg-4">
                <div class="subscribe-caption">
                  <form action="#">
                    <input type="text" placeholder="Enter your email" />
                    <button class="subscribe-btn">Subscribe</button>
                  </form>
                </div>
              </div>
              <div class="col-xxl-3 col-xl-3 col-lg-4">
                <div class="footer-social">
                  <a href="#">
                    <i class="fa fa-facebook"></i>
                  </a>
                  <a href="#">
                    <i class="fa fa-instagram"></i>
                  </a>
                  <a href="#">
                    <i class="fa fa-youtube"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </section>
        <div class="container">
          <div class="row justify-content-between">
            <div class="col-xl-2 col-lg-2 col-md-4 col-sm-6">
              <div class="single-footer-caption mb-50">
                <div class="single-footer-caption mb-20">
                  <div class="footer-logo mb-35">
                    <a href="index.html">
                      <img
                        src="https://preview.colorlib.com/theme/capitalshop/assets/img/logo/xlogo2_footer.png.pagespeed.ic.DUxRn4vG1w.webp"
                        alt=""
                      />
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-xl-2 col-lg-2 col-md-4 col-sm-6">
              <div class="single-footer-caption mb-50">
                <div class="footer-title">
                  <h4>Shop Men</h4>
                  <ul>
                    <li>
                      <a href="#">Clothing Fashion</a>
                    </li>
                    <li>
                      <a href="#">Winter</a>
                    </li>
                    <li>
                      <a href="#">Summer</a>
                    </li>
                    <li>
                      <a href="#">Formal</a>
                    </li>
                    <li>
                      <a href="#">Casual</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-xl-2 col-lg-2 col-md-4 col-sm-6">
              <div class="single-footer-caption mb-50">
                <div class="footer-title">
                  <h4>Shop Women</h4>
                  <ul>
                    <li>
                      <a href="#">Clothing Fashion</a>
                    </li>
                    <li>
                      <a href="#">Winter</a>
                    </li>
                    <li>
                      <a href="#">Summer</a>
                    </li>
                    <li>
                      <a href="#">Formal</a>
                    </li>
                    <li>
                      <a href="#">Casual</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-xl-2 col-lg-2 col-md-4 col-sm-6">
              <div class="single-footer-caption mb-50">
                <div class="footer-title">
                  <h4>Baby Collection</h4>
                  <ul>
                    <li>
                      <a href="#">Clothing Fashion</a>
                    </li>
                    <li>
                      <a href="#">Winter</a>
                    </li>
                    <li>
                      <a href="#">Summer</a>
                    </li>
                    <li>
                      <a href="#">Formal</a>
                    </li>
                    <li>
                      <a href="#">Casual</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-xl-2 col-lg-2 col-md-4 col-sm-6">
              <div class="single-footer-caption mb-50">
                <div class="footer-title">
                  <h4>Quick Links</h4>
                  <ul>
                    <li>
                      <a href="#">Track Your Order</a>
                    </li>
                    <li>
                      <a href="#">Support</a>
                    </li>
                    <li>
                      <a href="#">FAQ</a>
                    </li>
                    <li>
                      <a href="#">Carrier</a>
                    </li>
                    <li>
                      <a href="#">About</a>
                    </li>
                    <li>
                      <a href="#">Contact Us</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="footer-bottom-area">
        <div class="container">
          <div class="footer-border">
            <div class="row">
              <div class="col-xl-12">
                <div class="footer-copy-right text-center">
                  <p>
                    Copyright ©
                    <!-- <script>
                       document.write(new Date().getFullYear());
                    </script> -->
                    All rights reserved | This template is made with
                    <i class="fa fa-heart color-danger" aria-hidden="true"></i>
                    by
                    <a
                      href="https://colorlib.com"
                      target="_blank"
                      rel="nofollow noopener"
                      >Colorlib</a
                    >
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
    name: "FooterComponent"
};
</script>

<style>
.footer-wrapper {
    background: #171613;
}

/* .gray-bg {
    background: #f1fbff;
} */

.footer-padding {
    padding-top: 63px;
    padding-bottom: 60px;
}

.subscribe-area .subscribe-padding {
    padding-bottom: 40px;
    margin-bottom: 60px;
    border-bottom: 1px solid rgba(255,255,255,.14);
}

.subscribe-area .subscribe-caption h3 {
    color: #fff;
    font-family: "Jost",sans-serif;
    font-size: 24px;
    font-weight: 500;
    line-height: 1.3;
    margin-bottom: 12px;
}

.subscribe-area .subscribe-caption p {
    color: #fff;
    font-size: 15px;
}

.subscribe-area .subscribe-caption form input {
    width: 74%;
    height: 60px;
    border: 0;
    color: #000;
    background: #fff;
    border: 1px solid rgba(255,255,255,.2);
    border-radius: 0;
    padding: 15px 24px;
    font-size: 16px;
}

.subscribe-area .subscribe-caption form button.subscribe-btn {
    width: 24%;
    height: 60px;
    border: 0;
    background: #ff2020;
    border-radius: 0;
    padding: 13px 24px;
    color: #fff;
    margin-left: 5px;
    cursor: pointer;
    font-size: 16px;
    font-weight: 500;
}

.footer-social a {
    color: #677f8b;
    font-size: 24px;
    display: inline-block;
    text-align: center;
    margin-left: 23px;
}

.footer-social a i {
    -webkit-transition: all .4s ease-out 0s;
    -moz-transition: all .4s ease-out 0s;
    -ms-transition: all .4s ease-out 0s;
    -o-transition: all .4s ease-out 0s;
    transition: all .4s ease-out 0s;
    display: inline-block;
    transform: rotateY(
0deg);
    -webkit-transform: rotateY(
0deg);
    -moz-transform: rotateY(0deg);
    -ms-transform: rotateY(0deg);
    -o-transform: rotateY(0deg);
}

.footer-wrapper .footer-area .footer-tittle h4 {
    color: #fff;
    font-size: 18px;
    margin-bottom: 30px;
    font-weight: 400;
}

.footer-wrapper .footer-area .footer-tittle ul li {
    margin-bottom: 8px;
}

.footer-wrapper .footer-area .footer-tittle ul li a {
    color: #bbb9b5;
    font-weight: 400;
    font-size: 16px;
    text-decoration: underline transparent;
}

.footer-bottom-area .footer-border {
    border-top: 1px solid rgba(255,255,255,.14);
    padding-top: 39px;
    padding-bottom: 1px;
}

.footer-bottom-area .footer-copy-right p {
    color: #bbb9b5;
    font-weight: 300;
    font-size: 16px;
    line-height: 2;
}

.footer-bottom-area .footer-copy-right p i {
    color: #ff2020;
}

.footer-bottom-area .footer-copy-right p a {
    color: #ff2020;
}

</style>