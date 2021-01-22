<template>
  <div>
    <section class="front-banner">
      <div class="front-banner-bg coraid-lg mx-auto">
        <img src="~/assets/front-banner.jpg" alt=""
             v-bind:style="{'transform' : `scale(1.3) rotate(${random_axis_x}deg)`}">
      </div>
      <b-container class="position-relative">
        <div class="px-lg-5">
          <h1 class="text-white focus is-1 font-weight-bold">The quickest & easiest online video editor for any
            team</h1>
          <b-button size="lg" variant="primary">Try for free</b-button>
          <b-button size="lg" variant="lighter" class="ml-lg-2"><i class="icon icon-play"></i>Watch video</b-button>
        </div>
      </b-container>
    </section>
    <div class="wb_home--features home-media-gallery">
      <div class="container">
        <div class="wb_criss-cross">
          <div class="wb_criss-cross--text">
            <h2 class="heading2">Access millions of<br>
              premium licensed videos, photos and gifs</h2>
            <p>Get stunning footage and assets right in our online video editor from top providers for professional
              quality production.</p>
            <hr class="dash">
            <ul class="wb_trusted--brands">
              <li>
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/logo-getty.svg"
                  alt="">
              </li>
              <li>
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/logo-fotosearch.svg"
                  alt="">
              </li>
              <li>
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/logo-unsplash.svg"
                  alt="">
              </li>
              <li>
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/logo-abaca.png"
                  alt="">
              </li>
              <li>
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/logo-tenor.svg"
                  alt="">
              </li>
              <li>
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/logo-afp.svg"
                  alt="">
              </li>
              <li>
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/logo-storyblocks.svg"
                  alt="">
              </li>
            </ul>
          </div>
          <div class="wb_criss-cross--grid">
            <ul class="grid-wrapper" style="position: relative; height: 655px;">
              <li class="grid-item" style="position: absolute; left: 0px; top: 0px;">
                <img src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/city.gif"
                     alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 200px; top: 0px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/img-lg1.jpg"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 400px; top: 0px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/race_track-1.gif"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 400px; top: 130.4px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/img-md4.jpg"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 0px; top: 137.6px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/img-md2.jpg"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 200px; top: 313px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/frog-1.gif"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 0px; top: 324.6px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/img-md3.jpg"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 400px; top: 330.4px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/img-lg2.jpg"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 200px; top: 443.4px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/img-md1.jpg"
                  alt="">
              </li>
              <li class="grid-item" style="position: absolute; left: 0px; top: 524.6px;">
                <img
                  src="https://48vo7843c3543dkn9cvt8sl1-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/clouds-1.gif"
                  alt="">
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.front-banner {
  position: relative;
  overflow: hidden;
  @media screen and (min-width: 1024px) {
    height: 600px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  @media screen and (max-width: 1023px) {
    height: 80vh;
  }

  &-bg {
    position: absolute;
    top: 2rem;
    bottom: 2rem;
    overflow: hidden;
    max-width: 1280px;

    img {
      position: relative;
      object-fit: cover;
      width: 100%;
      transition: all .3s ease-in-out;
      perspective: 40px;
    }

    @media screen and (min-width: 1024px) {
      &:hover {
        img {
          transform: scale(1.015);
        }
      }
    }
  }
}

.searcher {
  position: relative;

  .form-control {
    height: 3.5rem;
    border: none;
    border-radius: .5rem;
    box-shadow: 0 4px 4px rgba(0, 0, 0, .25);
    padding-left: 3.5rem;
  }

  label {
    position: absolute;
    left: .75rem;
    top: calc(50% - (1.75rem / 2));

    svg {
      height: 1.75rem;
      width: 1.75rem;
    }
  }
}

</style>
<script>
export default {
  data() {
    return {
      random_axis_x: 0,
      random_axis_y: 0,
    }
  },
  methods: {
    scrolled(e) {
      this.random_axis_x = e.pageX / 100
      this.random_axis_y = e.pageY / 100
    },
  },
  mounted() {
    this.onScroll
    document.getElementsByClassName('front-banner')[0].addEventListener('mousemove', this.scrolled, false)
  },
  beforeDestroy() {
    document.getElementsByClassName('front-banner')[0].addEventListener('mousemove', this.scrolled, false)
  }

}
</script>
