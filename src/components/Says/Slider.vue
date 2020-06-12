<template>
  <div class="slider-wrapper">
    <div class="slide active">
      <img src="../../assets/images/saysteam1.png" alt="saysteam1" />
      <div class="background__says"></div>
    </div>
    <div class="slide">
      <img src="../../assets/images/saysteam2.png" alt="saysteam2" />
      <div class="background__says"></div>
    </div>
    <div class="slide">
      <img src="../../assets/images/saysteam3.png" alt="saysteam3" />
      <div class="background__says"></div>
    </div>
    <div class="slide">
      <img src="../../assets/images/saysteam4.png" alt="saysteam3" />
      <div class="background__says"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.slider-wrapper {
  position: relative;
}
.slide {
  position: absolute;
  z-index: 1;
  display: none;
  top: 0px;
}
.slide.active {
  position: relative;
  z-index: 1;
  display: block;
}
</style>
