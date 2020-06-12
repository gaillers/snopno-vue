<template>
  <div class="dots-wrapper" >
    <span class="dot active"></span>
    <span class="dot"></span>
    <span class="dot"></span>
    <span class="dot"></span>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.dots-wrapper {
  position: relative;
  display: flex;
  justify-content: center;
  right: 20%;
  margin-top: 38.7%;
}
.dot {
  width: 10px;
  height: 10px;
  border-radius: 3px;
  background-color: #d0d0d0;
  margin-right: 2px;
  cursor: pointer;
}
.dot.active {
  width: 11px;
  height: 10px;
  border-radius: 3px;
  background-color: #71f6eb;
}
</style>
