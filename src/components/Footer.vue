<template>
  <footer class="footer">
    <div class="footer__logo-box">
      <picture class="footer__logo">
        <source
          srcset="
            ../assets/img/logo-green-small-1x.png 1x,
            ../assets/img/logo-green-small-2x.png 2x
          "
          media="(max-width:37.5em)"
        />
        <img
          srcset="
            ../assets/img/logo-green-2x.png 1x,
            ../assets/img/logo-green-1x.png 2x
          "
          alt="full-logo"
          class="footer__logo"
        />
      </picture>
      <!-- <img
        srcset="
          ../assets/img/logo-green-2x.png 1x,
          ../assets/img/logo-green-2x.png 2x
        "
        alt="full-logo"
        class="footer__logo"
      /> -->
    </div>
    <div class="row">
      <div class="col-1-of-2">
        <div class="footer__navigation">
          <ul class="footer__list">
            <li class="footer__item">
              <a href="#" class="footer__link">Company</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Contact Us</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Careers</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Privacy</a>
            </li>
            <li class="footer__item">
              <a href="#" class="footer__link">Terms</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="col-1-of-2">
        <p class="footer__copyright">
          Built by <a href="#" class="footer__link">Jon Doucette</a> Lorem ipsum
          dolor sit amet, consectetur adipisicing elit. Blanditiis in accusamus
          voluptates laborum enim alias. Hic aliquam culpa magni reiciendis
          mollitia ut vero voluptas ad illum, magnam totam obcaecati quidem.
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style></style>
