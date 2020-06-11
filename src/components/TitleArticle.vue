<template>
  <h2 class="title">{{ titles }}</h2>
</template>

<script>
export default {
   props: {
    'titles':String,
    },
};
</script>

<style lang="scss">
.title {
  opacity: 0.9;
  font-family: 'Montserrat', sans-serif;
  font-size: 38px;
  line-height: 0.74;
  letter-spacing: 2.28px;
  text-align: center;
  color: #000000e6;
  margin: 0 auto;
  text-transform: uppercase;
  margin-bottom: 17px;
}
</style>
