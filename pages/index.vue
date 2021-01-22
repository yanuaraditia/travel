<template>
  <div>
    <section class="front-banner">
      <div class="front-banner-bg coraid-lg mx-auto">
        <img src="~/assets/front-banner.jpg" alt="" v-bind:style="{'transform' : `translateY(-${random_axis}px)`}">
      </div>
      <b-container class="position-relative">
        <div class="px-lg-5">
          <h1 class="text-white focus is-1">The quickest & easiest online video editor for any team</h1>
          <b-button size="lg" variant="primary">Try for free</b-button>
          <b-button size="lg" variant="lighter" class="ml-lg-2">Watch video</b-button>
        </div>
      </b-container>
    </section>
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
    box-shadow: 0 4px 4px rgba(0,0,0,.25);
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
      random_axis: 0
    }
  },
  methods: {
    scrolled() {
      const offset_max = document.getElementsByClassName('coraid-lg')[0].getBoundingClientRect().bottom;
      const currentScrollPosition = window.pageYOffset || document.documentElement.scrollTop
      if (currentScrollPosition <= offset_max) {
        this.random_axis = currentScrollPosition + 10;
      } else {
        this.random_axis = offset_max
      }
    }
  },
  mounted () {
    this.onScroll
    window.addEventListener('scroll', this.scrolled)
  },
  beforeDestroy () {
    window.removeEventListener('scroll', this.scrolled)
  }

}
</script>
