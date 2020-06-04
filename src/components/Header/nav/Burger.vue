<template>
  <div class="burger">
    <div></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.burger {
  position: relative;
  width: 30px;
  height: 30px;
  border-radius: 1.5px;
  opacity: 0.6;
  cursor: pointer;
  div {
    position: absolute;
    width: 30px;
    height: 4px;
    background-color: #000;
    border-radius: 1.5px;
    top: 13px;
    &::before {
      content: '';
      width: 30px;
      height: 4px;
      position: absolute;
      border-radius: 1.5px;
      background: #000;
      top: -9px;
    }
    &::after {
      content: '';
      width: 30px;
      height: 4px;
      position: absolute;
      border-radius: 1.5px;
      background-color: #000;
      top: 9px;
    }
  }
}
</style>
