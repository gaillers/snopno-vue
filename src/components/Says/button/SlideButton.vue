<template>
  <div class="arrows">
    <div id="btn-prev" class="arrow-prev" tabindex="1" role="button"></div>
    <div id="btn-next" class="arrow-next" tabindex="2" role="button"></div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.arrows {
  display: flex;
  position: absolute;
  right: auto;
  margin-left: 575px;
  top: 6785px;
}
.arrow-prev,
.arrow-next {
  width: 40px;
  height: 40px;

  background-color: #71f6eb;
  margin: 0 4px;
  position: relative;
  cursor: pointer;
  transition: 0.3s ease;

  &:hover {
    box-shadow: 0 0 0 5px rgba(black, 0.5);
  }
  &:focus {
    box-shadow: 0 0 0 5px rgba(black, 0.5);
    outline: none;
  }
  &:active {
    box-shadow: 0 0 0 5px rgba(black, 1);
  }

  &::before,
  &::after {
    content: '';
    width: 40%;
    height: 4px;
    margin-top: -2px;
    background: #ffffff;
    position: absolute;
    top: 50%;
    border-radius: 4px;
  }
  &::before {
    transform: rotate(45deg);
  }
  &::after {
    transform: rotate(-45deg);
  }
}
.arrow-prev {
  &::before,
  &::after {
    left: 32%;
  }
  &::before {
    transform-origin: 0 0;
  }
  &::after {
    transform-origin: 0 100%;
  }
}
.arrow-next {
  &::before,
  &::after {
    right: 32%;
  }
  &::before {
    transform-origin: 100% 100%;
  }
  &::after {
    transform-origin: 100% 0;
  }
}
</style>
