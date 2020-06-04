<template>
  <button class="button">contact us</button>
</template>

<script>
export default {};
</script>

<style lang="scss">
.button {
  display: flex;
  margin: 0 auto;
  font-family: 'Montserrat', sans-serif;
  font-size: 18px;
  font-weight: 700;
  font-stretch: normal;
  font-style: normal;
  letter-spacing: 2.16px;
  text-align: left;
  height: 53px;
  border: 2px solid #000;
  padding: 16px 48px;
  text-transform: uppercase;
  transition: ease-out 0.5s;
  &:hover {
    background: #000;
    color: white;
  }
}
</style>
