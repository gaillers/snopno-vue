<template>
  <section class="works">
    <div class="works-us">
      <TitleArticle titles="featured works"/>
      <TextArticle texts="lorem ipsum dolor sit amet event landing template"/>
    </div>
    <div class="content-img">
      <img src="../assets/images/1 works.png" alt="1 works" />
      <img src="../assets/images/2 works.png" alt="2 works" />
      <img src="../assets/images/3 works.png" alt="3 works" />
      <img src="../assets/images/4 works.png" alt="4 works" />
      <img src="../assets/images/5 works.png" alt="5 works" />
      <img src="../assets/images/6 works.png" alt="6 works" />
    </div>
  </section>
</template>

<script>
import TitleArticle from '../components/TitleArticle';
import TextArticle from '../components/TextArticle';

export default {
 name: 'Works',
 components: {
   TitleArticle,
   TextArticle,
   
 }
};
</script>

<style lang="scss">
.works {
  max-width: 1920px;
  width: 100%;
  margin-bottom: 117px;
}
.works-us {
  width: 617px;
  margin: 0 auto;
}
.content-img {
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  align-content: stretch;
  height: 100%;
  justify-content: center;
}

.content-img img {
  margin-left: 15px;
  margin-bottom: 24px;
  margin-right: 15px;
}
</style>
