<template>
    <!-- Banner -->
  <section ref="banner" class="banner bg-cover vh-100">
    <div class="banner-mask d-flex justify-content-center align-items-center">
      <h2 class="text-white text-center mt-20 d-flex flex-column">
        <span class="mb-8 font-weight-bold">Welcome to Nefer Digital</span>
        <span class="mb-8 font-weight-bold">完美數位科技</span>
        <span><i>最新的技術，穩定的基石開拓新市場</i></span>
      </h2>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import '../../assets/all.scss';
    // Banner
.banner {
    background-image: url('../../assets/images/u0.jpg');
    position: relative;

    .banner-mask {
      position: absolute;
      top: 0;
      bottom: 0;
      right: 0;
      left: 0;
      background-color: rgba(0, 0, 0, .75);

      h2 {
          @include mobile {
              font-size: 24px;
          }
      }
    }
}
</style>
