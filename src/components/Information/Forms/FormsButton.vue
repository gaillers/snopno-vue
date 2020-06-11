<template>
  <div class="text-center">
    <button type="submit" class="btn btn-start-order">send message</button>
  </div>
</template>

<script>
export default {
   
};
</script>

<style lang="scss" scoped>
.text-center {
 margin-left: 30px;
 margin-top: 55px;
}
.btn-start-order {
 width: 244px;
 height: 53px;
 border-radius: 2px;
 background-color: #71f6eb;
 border: none;
 font-family: "Montserrat", sans-serif;
 font-size: 18px;
 text-transform: uppercase;
 transition: ease-out 0.5s;
  &:hover {
   background: #fff;
   color: #000;}
}
</style>
