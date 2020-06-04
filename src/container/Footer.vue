<template>
  <footer class="footer">
    <div class="follows">
      <h4 class="follow-text">follow us</h4>
      <div class="icon">
        <div class="icon-pinterest">
          <img
            class="pinterest"
            src="../assets/svgs/pinterest.svg"
            alt="pinterest"
          />
        </div>
        <div class="icon-twitter">
          <img class="twitter" src="../assets/svgs/twitter.svg" alt="twitter" />
        </div>
        <div class="icon-facebook">
          <img
            class="facebook"
            src="../assets/svgs/facebook.svg"
            alt="facebook"
          />
        </div>
        <div class="icon-dribbble">
          <img
            class="dribbble"
            src="../assets/svgs/dribbble.svg"
            alt="dribbble"
          />
        </div>
      </div>
      <p class="follow-title">Copyright Masum Parvej, All Rights Reserved</p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
.footer {
  max-width: 1920px;
  width: 100%;
  height: 316px;
  background-color: #262b2e;
  margin-top: -20px;
}
.follows {
  margin-top: 10px;
}
.follow-text {
  opacity: 0.8;
  font-family: 'Raleway', sans-serif;
  font-weight: 400;
  letter-spacing: 0.16px;
  text-align: center;
  color: #ffffffcc;
  padding-top: 90px;
  text-transform: uppercase;
}
.follow-title {
  opacity: 0.4;
  font-family: 'Raleway', sans-serif;
  line-height: 1.56;
  letter-spacing: 0.16px;
  text-align: center;
  color: #ffffff66;
}
/* ICON */
.icon {
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
/* <ICON */
</style>
