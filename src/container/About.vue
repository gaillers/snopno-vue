<template>
  <section class="about">
    <div class="about-us">
      <TitleArticle titles="about us"/>
      <TextArticle texts="lorem ipsum dolor sit amet event landing template"/>
    </div>
    <div class="container-info">
      <div class="block__photo">
        <img src="../assets/images/About photo.png" alt="about png" />
        <div class="background__photo"></div>
      </div>
      <div class="block-info">
        <h2 class="block__title">we actually do amazing works</h2>
        <p class="block__text">
          A visual approach is an approach to a runway at an airoport conducted
          inder instrument flight rules. The pilot must at all times have either
          the airport or the preceding aircraft in approach correct sight.
          Conducter under instrument flight rules. The pilot must at all
          times.<br />Preceding aircraft in approach correct sight. Conducted
          under instrument flight rules.
        </p>
        <h3 class="block__title title-two">why we are the great?</h3>
        <p class="block__text text-two">
          A visual approach is an approach to a runway at an airport conducted
          under instrument flight rules. <br />The preceding aircraft oi
          approach correct sight.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
import TitleArticle from '../components/TitleArticle';
import TextArticle from '../components/TextArticle'
export default {
 name: 'About',
 components: {
   TitleArticle,
   TextArticle,
   
 }
};
</script>

<style lang="scss">
.about {
  max-width: 1920px;
  width: 100%;
  background-color: #f9fbfb;
  margin-bottom: 130px;
}
.about-us {
  width: 617px;
  margin: 0 auto;
  padding-top: 130px;
}
.container-info {
  display: flex;
  justify-content: space-evenly;
  max-width: 1600px;
  width: 100%;
  margin: 0 auto;
  align-items: center;
  padding-bottom: 130px;
}
.block__photo {
  position: relative;
  z-index: 1;
}

.background__photo {
  position: absolute;
  z-index: -1;
  width: 479px;
  height: 412px;
  background-color: #eff0f2;
  top: 62px;
  left: -18px;
}
.block__title {
  font-family: "Montserrat", sans-serif;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.4;
  letter-spacing: 1.2px;
  text-align: left;
  color: #000000c0;
  font-size: 21px;
  text-transform: uppercase;
  padding: 17px 0 17px 0;
}

.block__text {
  width: 480px;
  height: 212px;
  opacity: 0.74;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.75;
  letter-spacing: 0.8px;
  text-align: left;
  color: #000000bd;
  padding-bottom: 16px;
  
}

.title-two {
  font-family: "Montserrat", sans-serif;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.4;
  letter-spacing: 1.2px;
  text-align: left;
  color: #000000c0;
  font-size: 18px;
}
.text-two {
  height: 85px;
  opacity: 0.74;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.75;
  letter-spacing: 0.8px;
  text-align: left;
  color: #000000bd;
}

</style>
