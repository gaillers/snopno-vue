<template>
  <section class="services">
      <div class="services-us">
       <TitleArticle titles="our services"/>
       <TextArticle texts="lorem ipsum dolor sit amet event landing template"/>
      </div>
      <div class="services-info">
        <div class="services__info container-designing">
          <img src="../assets/images/services 1.png" alt="services 1">
          <div class="background-img1"></div>
          <div class="block-designing">
            <h3 class="designing-text">DESIGNING IS THE COOL LOVE FOR.</h3>
            <p class="designing-title">Our most popular service is our Virtual Receptionist. We know that sometimes it’s something and you middle most..</p>
            <button class="button-services">KNOW MORE
              <div class="button-next"></div>
            </button>
          </div>
        </div>
        <div class="services__info container-design">
          <img src="../assets/images/services 2.png" alt="services 2">
          <div class="background-img2"></div>
          <div class="block-design">
            <h3 class="design-text">COOL PSD DESIGN</h3>
            <p class="design-title">Our most popular service is our we know that sometimes it’s something and you middle most..</p>
            <button class="button-services">KNOW MORE
              <div class="button-next"></div>
            </button>
          </div>
        </div>
        <div class="services__info container-cool">
          <img src="../assets/images/services 3.png" alt="services 3">
          <div class="background-img3"></div>
          <div class="block-cool">
            <h3 class="cool-text">DESIGNING IS THE COOL</h3>
            <p class="cool-title">Our most popular service is our Virtual Receptionist. We know that ...</p>
            <button class="button-services">KNOW MORE
              <div class="button-nexttwo"></div>
            </button>
          </div>
        </div>
        <div class="services__info container-html">
          <img src="../assets/images/services 4.png" alt="services 4">
          <div class="background-img4"></div>
          <div class="block-html">
            <h3 class="html-text">PSD TO HTML KORI</h3>
            <p class="html-title">Our most popular service is our Virtual Receptionist. We know that ...</p>
            <button class="button-services">KNOW MORE
              <div class="button-nexttwo"></div>
            </button>
          </div>
        </div>
        <div class="services__info container-virtual">
          <img src="../assets/images/services 5.png" alt="services 5">
          <div class="background-img5"></div>
          <div class="block-virtual">
            <h3 class="virtual-text">COOL PSD DESIGN</h3>
            <p class="virtual-title">Our most popular service is our new virtual Receptionist you middle most..</p>
            <button class="button-services">KNOW MORE
              <div class="button-next"></div>
            </button>
          </div>
        </div>
        <div class="services__info container-recopt">
          <img src="../assets/images/services 6.png" alt="services 6">
          <div class="background-img6"></div>
          <div class="block-recopt">
            <h3 class="recopt-text">DESIGNING IS THE COOL FOR</h3>
            <p class="recopt-title">Our most popular service is our Virtual Receptionist. We know that sometimes it’s something and you middle most..</p>
            <button class="button-services">KNOW MORE
              <div class="button-next"></div>
            </button>
          </div>
        </div>
      </div>
    </section>
</template>

<script>
import TitleArticle from '../components/TitleArticle';
import TextArticle from '../components/TextArticle'
export default {
 name: 'Services',
 components: {
   TitleArticle,
   TextArticle,
 }
}
</script>

<style lang = "scss">
.services {
  max-width: 1920px;
  width: 100%;
  background-color: #f9fbfb;
  margin-bottom: 130px;
}
.services-us {
  width: 617px;
  margin: 0 auto;
  padding-top: 130px;
}
.services-info {
  max-width: 1170px;
  width: 100%;
  display: flex;
  margin: 0 auto;
  flex-wrap: wrap;
  justify-content: space-between;
}
/* 1 services */
.container-designing {
  width: 652px;
  height: 422px;
}

.block-designing {
  position: absolute;
  top: 3525px;
  left: auto;
  margin-left: 50px;
}
.designing-text {
  width: 425px;
  opacity: 0.95;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.45;
  letter-spacing: 1px;
  text-align: left;
  color: #fffffff3;
  padding-bottom: 20px;
}

.designing-title {
  width: 406px;
  opacity: 0.91;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: 0.32px;
  text-align: left;
  color: #ffffffe8;
}

.button-services {
  opacity: 0.9;
  font-family: "Raleway", sans-serif;
  font-size: 18px;
  font-weight: 500;
  font-stretch: normal;
  font-style: normal;
  letter-spacing: 0.72px;
  text-align: center;
  color: #f9fbfbe6;
  margin-top: 30px;
  background-color: transparent;
  border: none;
  margin-left: -1px;
  transition: ease-out 0.5s;

  &:hover {
    color: #000;
  }

  .button-next {
    position: absolute;
    width: 22px;
    height: 3px;
    opacity: 0.8;
    background-color: #ffffff;
    border-radius: 1.6px;
    left: 138px;
    top: 159px;
    transition: ease-out 0.5s;

    &::before {
      content: "";
      width: 11px;
      height: 3px;
      background-color: #fff;
      border-radius: 1.6px;
      position: absolute;
      left: 14px;
      transform: rotate(40deg);
      top: -3px;
    }
    &::after {
      content: "";
      width: 11px;
      height: 3px;
      background-color: #fff;
      border-radius: 1.6px;
      position: absolute;
      top: 3px;
      transform: rotate(-40deg);
      left: 14.1px;
    }
  }
}

.background-img1 {
  position: relative;
  background-color: #000;
  opacity: 0.6;
  width: 652px;
  height: 422px;
  top: -426px;
}
/* << 1 services >> */

/* 2 services */
.container-design {
  width: 474px;
  height: 422px;
}

.block-design {
  position: absolute;
  top: 3525px;
  left: auto;
  margin-left: 50px;
}

.design-text {
  opacity: 0.95;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.45;
  letter-spacing: 1px;
  text-align: left;
  color: #fffffff3;
  padding-bottom: 20px;
}
.design-title {
  width: 312px;
  opacity: 0.9;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: 0.32px;
  text-align: left;
  color: #ffffffe6;
}

.background-img2 {
  position: relative;
  background-color: #000;
  opacity: 0.6;
  width: 474px;
  height: 422px;
  top: -426px;
}
/* << 2 services >> */

/* 3 services */
.container-cool {
  width: 652px;
  height: 371px;
  margin-top: 15px;
}

.block-cool {
  position: absolute;
  top: 3935px;
  left: auto;
  margin-left: 50px;
}

.button-nexttwo {
  position: absolute;
  width: 22px;
  height: 3px;
  opacity: 0.8;
  background-color: #ffffff;
  border-radius: 1.6px;
  left: 138px;
  top: 136px;
  transition: ease-out 0.5s;

  &::before {
    content: "";
    width: 11px;
    height: 3px;
    background-color: #fff;
    border-radius: 1.6px;
    position: absolute;
    left: 14px;
    transform: rotate(40deg);
    top: -3px;
  }
  &::after {
    content: "";
    width: 11px;
    height: 3px;
    background-color: #fff;
    border-radius: 1.6px;
    position: absolute;
    top: 3px;
    transform: rotate(-40deg);
    left: 14.1px;
  }
}

.cool-text {
  opacity: 0.95;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.45;
  letter-spacing: 1px;
  text-align: left;
  color: #fffffff3;
  padding-bottom: 20px;
}

.cool-title {
  width: 396px;
  opacity: 0.9;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: 0.32px;
  text-align: left;
  color: #ffffffe6;
}

.background-img3 {
  position: relative;
  background-color: #000;
  opacity: 0.6;
  width: 652px;
  height: 371px;
  top: -375px;
}
/* << 3 services >> */

/* 4 services */
.container-html {
  width: 474px;
  height: 370px;
  margin-top: 15px;
}

.block-html {
  position: absolute;
  top: 3935px;
  left: auto;
  margin-left: 50px;
}

.html-text {
  opacity: 0.95;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.45;
  letter-spacing: 1px;
  text-align: left;
  color: #fffffff3;
  padding-bottom: 20px;
}

.html-title {
  width: 305px;
  opacity: 0.91;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: 0.32px;
  text-align: left;
  color: #ffffffe8;
}

.background-img4 {
  position: relative;
  background-color: #000;
  opacity: 0.6;
  width: 474px;
  height: 370px;
  top: -374px;
}
/* << 4 services >> */

/* 5 services */
.container-virtual {
  width: 472px;
  height: 370px;
  margin-top: 15px;
}

.block-virtual {
  position: absolute;
  top: 4295px;
  left: auto;
  margin-left: 50px;
}
.virtual-text {
  opacity: 0.95;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.45;
  letter-spacing: 1px;
  text-align: left;
  color: #fffffff3;
  padding-bottom: 20px;
}
.virtual-title {
  width: 287px;
  opacity: 0.91;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: 0.32px;
  text-align: left;
  color: #ffffffe8;
}

.background-img5 {
  position: relative;
  background-color: #000;
  opacity: 0.6;
  width: 472px;
  height: 370px;
  top: -375px;
}
/* << 5 services>> */

/* 6 services */
.container-recopt {
  height: 371px;
  margin-top: 15px;
}
.block-recopt {
  position: absolute;
  top: 4295px;
  left: auto;
  margin-left: 50px;
}

.recopt-text {
  opacity: 0.95;
  font-family: "Montserrat", sans-serif;
  font-size: 20px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.45;
  letter-spacing: 1px;
  text-align: left;
  color: #fffffff3;
  padding-bottom: 20px;
}

.recopt-title {
  width: 397px;
  opacity: 0.91;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.56;
  letter-spacing: 0.32px;
  text-align: left;
  color: #ffffffe8;
}

.background-img6 {
  position: relative;
  background-color: #000;
  opacity: 0.6;
  height: 371px;
  top: -375px;
}

/* << 6 services >> */
</style>