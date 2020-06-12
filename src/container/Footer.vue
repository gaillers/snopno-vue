<template>
  <footer class="footer">
    <div class="follows">
      <h4 class="follow-text">follow us</h4>
      <SocialFooter/>
      <p class="follow-title">Copyright Masum Parvej, All Rights Reserved</p>
    </div>
  </footer>
</template>

<script>
import SocialFooter from '../components/Footer/nav/SocialFooter'

export default {
  name: 'Footer',
  components: {
    SocialFooter,
    
  }
};
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
</style>
