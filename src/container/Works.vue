<template>
  <section class="works">
    <div class="works-us">
      <h2 class="works__title">featured works</h2>
      <p class="works__text">
        lorem ipsum dolor sit amet event landing template
      </p>
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
export default {};
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
.works__title {
  opacity: 0.9;
  font-family: 'Montserrat', sans-serif;
  font-size: 38px;
  line-height: 0.74;
  letter-spacing: 2.28px;
  text-align: center;
  color: #000000e6;
  margin: 0 auto;
  text-transform: uppercase;
  margin-bottom: 17px;
}
.works__text {
  opacity: 0.62;
  font-family: 'Raleway', sans-serif;
  font-size: 18px;
  line-height: 1.56;
  letter-spacing: 2px;
  text-align: center;
  color: #0000009e;
  margin: 0 auto;
  margin-bottom: 120px;
  text-transform: uppercase;
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
