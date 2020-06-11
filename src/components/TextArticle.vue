<template>
  <p class="text">{{ texts }}</p>
</template>

<script>
export default {
 props: {
    'texts':String,
  },
};
</script>

<style lang = "scss">
.text {
 opacity: 0.62;
 font-family: "Raleway", sans-serif;
 font-size: 18px;
 line-height: 1.56;
 letter-spacing: 2px;
 text-align: center;
 color: #0000009e;
 margin: 0 auto;
 margin-bottom: 120px;
 text-transform: uppercase;
}
</style>
