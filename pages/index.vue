<template>
  <section class="front-banner">
    <div class="front-banner-bg coraid mx-auto">
      <img src="~/assets/front-banner.jpg" alt="">
    </div>
    <b-container class="position-relative">
      <div class="px-lg-4">
        <h1 class="text-white grotesk focus is-1">Find the good out there.</h1>
        <div class="form-group searcher">
          <label for="">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-search"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
          </label>
          <input type="text" placeholder="Which one?" class="form-control">
        </div>
      </div>
    </b-container>
  </section>
</template>

<style lang="scss">
.front-banner {
  position: relative;
  overflow: hidden;
  @media screen and (min-width: 1024px) {
    height: 80vh;
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