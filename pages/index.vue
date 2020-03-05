<template>
  <main>
    <div data-scroll class="page page--layout-2">
      <h1 class="page__title">Smooth Scrolling Image Effects</h1>
      <div class="meta">
        <div class="meta__links">
          <a href="https://tympanus.net/codrops/?p=42459">Article</a>
          <a href="https://tympanus.net/Tutorials/SmoothScrollAnimations/">Previous Demo</a>
          <a href="https://github.com/codrops/SmoothScrollingImageEffects/">GitHub</a>
        </div>
        <div class="meta__demos">
          <a href="index.html" class="meta__demo meta__demo--current">01</a>
        </div>
      </div>
      <div class="content content--full content--alternate">
        <div class="content__item content__item--wide">
          <span class="content__item-number">01</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/17.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Oh</h2>
          <p class="content__item-description">Little trees and bushes grow however makes them happy.</p>
        </div>
        <div class="content__item content__item--wide">
          <span class="content__item-number">02</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/21.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Ri</h2>
          <p class="content__item-description">We don't have to be committed. We are just playing here.</p>
        </div>
        <div class="content__item content__item--wide">
          <span class="content__item-number">03</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/19.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Nj</h2>
          <p class="content__item-description">I thought today we would do a happy little picture.</p>
        </div>
        <div class="content__item content__item--wide">
          <span class="content__item-number">04</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/20.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Mo</h2>
          <p class="content__item-description">Nature is so fantastic, enjoy it. Let it make you happy.</p>
        </div>
        <div class="content__item content__item--wide">
          <span class="content__item-number">05</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/18.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Ne</h2>
          <p class="content__item-description">We need a shadow side and a highlight side.</p>
        </div>
        <div class="content__item content__item--wide">
          <span class="content__item-number">06</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/16.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Wy</h2>
          <p class="content__item-description">We'll put some happy little leaves here and there.</p>
        </div>
        <div class="content__item content__item--wide">
          <span class="content__item-number">07</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/11.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Tx</h2>
          <p class="content__item-description">With something so strong, a little bit can go a long way.</p>
        </div>
        <div class="content__item content__item--wide">
          <span class="content__item-number">08</span>
          <div class="content__item-imgwrap"><div class="content__item-img" style="background-image: url(images/4.jpg);"></div></div>
          <div class="content__item-deco"></div>
          <h2 class="content__item-title">Sd</h2>
          <p class="content__item-description">There are no limits in this world.</p>
        </div>
        <p class="credits">Photography by <a href="https://www.instagram.com/byfoul/">Frankie Cordoba</a></p>
      </div>
    </div>
  </main>
</template>

<script>
// import Logo from '~/components/Logo.vue'

// if (process.client) {
//   require('/js/demo.js')
// }

export default {
  components: {
    // Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
