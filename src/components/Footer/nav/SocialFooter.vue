<template>
  <div class="social__social-nav">
    <div class="icon-pinterest">
      <a href="#"></a>
    </div>
    <div class="icon-twitter">
      <a href="#"></a>
    </div>
    <div class="icon-facebook">
      <a href="#"></a>
    </div>
    <div class="icon-dribbble">
      <a href="#"></a>
    </div>
</div>

</template>
                                       //* До делать социальные svg 
<script>
export default {
   name: 'SocialFooter',
   
};
</script>

<style lang="scss" scoped>
.social__social-nav {
  display: flex;
  justify-content: space-between;
  width: 180px;
  margin: 0 auto;
  margin-bottom: 40px;
  margin-top: 20px;
}
.icon-pinterest {
  width: 40px;
  height: 40px;
  background-color: #8a8a8a;
  .pinterest {
    width: 22px;
    height: 22px;
    padding: 9px;
    transition: ease-out 0.5s;
    &:hover {
      background-color: #71f6eb;
    }
  }
}
.icon-twitter {
  width: 40px;
  height: 40px;
  background-color: #8a8a8a;
  .twitter {
    width: 22px;
    height: 22px;
    padding: 9px;
    transition: ease-out 0.5s;
    &:hover {
      background-color: #71f6eb;
    }
  }
}
.icon-facebook {
  width: 40px;
  height: 40px;
  background-color: #8a8a8a;
  .facebook {
    width: 22px;
    height: 22px;
    padding: 9px;
    transition: ease-out 0.5s;
    &:hover {
      background-color: #71f6eb;
    }
  }
}
.icon-dribbble {
  width: 40px;
  height: 40px;
  background-color: #8a8a8a;
  .dribbble {
    width: 22px;
    height: 22px;
    padding: 9px;
    transition: ease-out 0.5s;
    &:hover {
      background-color: #71f6eb;
    }
  }
}
</style>
