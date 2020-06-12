<template>
  <div class="social__social-nav">
    <SvgPinterest/>
    <SvgTwitter/>
    <SvgFacebook/>
    <SvgDribbble/>
</div>

</template>

<script>
import SvgPinterest from '../svg/SvgPinterest';
import SvgTwitter from '../svg/SvgTwitter';
import SvgFacebook from '../svg/SvgFacebook';
import SvgDribbble from '../svg/SvgDribbble';
export default {
   name: 'SocialFooter',
   components: {
    SvgPinterest,
    SvgTwitter,
    SvgFacebook,
    SvgDribbble,
   },
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

</style>
