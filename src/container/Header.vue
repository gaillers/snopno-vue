<template>
  <header class="header">
    <div class="menu">
      <img
        class="logo"
        href="#"
        src="../assets/images/Logo.png"
        alt="Logo.png"
      />
      <Burger/>
    </div>
    <div class="container">
      <TitleMain/>
      <MainButton/> 
      <img
        class="banka"
        src="../assets/svgs/banka.svg"
        alt="banka"
        height="100"
        width="100"
      />
    </div>
  </header>
</template>

<script>
import MainButton from '../components/Header/button/MainButton'
import Burger from '../components/Header/nav/Burger'
import TitleMain from '../components/Header/title/TitleMain'

export default {
  name: 'Header',
  components: {
    MainButton,
    Burger,
    TitleMain,
  },
};
</script>

<style lang="scss">
.header {
  max-width: 1920px;
  width: 100%;
  height: 806px;
  opacity: 0.99;
  background-color: #eff0f2;
}
.container {
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
}
.menu {
  max-width: 1600px;
  width: 100%;
  height: 25%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 30px;
}
.banka {
  display: flex;
  margin: 0 auto;
  margin-right: 138px;
}

.svg-banka {
  display: none;
}
</style>
