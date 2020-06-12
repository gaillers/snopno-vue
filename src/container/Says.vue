<template>
  <section class="says">
    <div class="says-us">
      <TitleArticle titles="what they says"/>
      <TextArticle texts="lorem ipsum dolor sit amet event landing template"/>
    </div>
    <div class="container-says">
      <Slider/>
      <SliderDots/>
      <div class="block__information">
        <h3 class="block__information-text"><b>richard</b> / ui/ux designer</h3>
        <p class="block__information-title">
          Lorem Ipsum is simply dummy text of the printing and you standard
          dummy know that text ever since the 1500s, when an unknown printer
          took a galley of type and scrambled it to make a type specimen book.
        </p>
        <div class="rating-mini">
          <span class="active"></span>
          <span class="active"></span>
          <span class="active"></span>
          <span class="active"></span>
          <span class="active"></span>
        </div>
        <SliderButton/>
      </div>
    </div>
  </section>
</template>

<script>
import Slider from '../components/Says/Slider';
import SliderDots from '../components/Says/SliderDots';
import SliderButton from '../components/Says/SliderButton';
import TitleArticle from '../components/TitleArticle';
import TextArticle from '../components/TextArticle';


export default {
  name: 'Says',
  components: {
    Slider,
    SliderDots,
    SliderButton,
    TitleArticle,
    TextArticle
  },
};
</script>

<style lang="scss">
.says {
  max-width: 1920px;
  width: 100%;
  height: 920px;
  background-color: #f9fbfb;
}
.says-us {
  width: 617px;
  margin: 0 auto;
  padding-top: 120px;
}
.container-says {
  display: flex;
  justify-content: space-around;
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
}
.background__says {
  position: absolute;
  z-index: -1;
  width: 393px;
  height: 362px;
  border-radius: 3px;
  background-color: #ecedef;
  top: 40px;
  right: -16px;
}
.block__information {
  margin-top: 40px;
  width: 666px;
  height: 362px;
  border-radius: 3px;
  background-color: #eaebed;
}
.block__information-text {
  margin-top: 80px;
  opacity: 0.95;
  font-family: 'Montserrat', sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.87;
  letter-spacing: 0.9px;
  text-align: center;
  color: #787878f3;
  margin-left: auto;
  text-transform: uppercase;
  & b {
    font-size: 20px;
    font-weight: bold;
    letter-spacing: 1.2px;
    color: #000000f3;
    text-transform: uppercase;
  }
}
.block__information-title {
  width: 515px;
  height: 105px;
  opacity: 0.7;
  font-family: 'Raleway', sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.69;
  letter-spacing: 0.96px;
  text-align: center;
  color: #000000b3;
  margin-left: 75px;
}
.rating-mini {
  display: inline-block;
  font-size: 0;
  margin-left: 285px;
  margin-top: 20px;
}
.rating-mini span {
  padding: 0;
  font-size: 20px;
  line-height: 1;
  color: lightgrey;
}
.rating-mini > span:before {
  content: '★';
}
.rating-mini > span.active {
  color: gold;
}

.arrows {
  display: flex;
  position: absolute;
  right: auto;
  margin-left: 535px;
  top: 6800px;
}
.arrow-prev,
.arrow-next {
  width: 40px;
  height: 40px;

  background-color: #71f6eb;
  margin: 0 4px;
  position: relative;
  cursor: pointer;
  transition: 0.3s ease;

  &:hover {
    box-shadow: 0 0 0 5px rgba(black, 0.5);
  }
  &:focus {
    box-shadow: 0 0 0 5px rgba(black, 0.5);
    outline: none;
  }
  &:active {
    box-shadow: 0 0 0 5px rgba(black, 1);
  }

  &::before,
  &::after {
    content: '';
    width: 40%;
    height: 4px;
    margin-top: -2px;
    background: #ffffff;
    position: absolute;
    top: 50%;
    border-radius: 4px;
  }
  &::before {
    transform: rotate(45deg);
  }
  &::after {
    transform: rotate(-45deg);
  }
}
.arrow-prev {
  &::before,
  &::after {
    left: 32%;
  }
  &::before {
    transform-origin: 0 0;
  }
  &::after {
    transform-origin: 0 100%;
  }
}
.arrow-next {
  &::before,
  &::after {
    right: 32%;
  }
  &::before {
    transform-origin: 100% 100%;
  }
  &::after {
    transform-origin: 100% 0;
  }
}
</style>
