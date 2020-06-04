<template>
  <div class="main">
    <Header />
    <About />
    <Works />
    <Services />
    <Team />
    <Says />
    <Sponsor />
    <Information />
    <Footer />
  </div>
</template>

<script>
import Header from '../src/container/Header';
import About from '../src/container/About';
import Works from '../src/container/Works';
import Services from '../src/container/Services';
import Team from '../src/container/Team';
import Says from '../src/container/Says';
import Sponsor from '../src/container/Sponsor';
import Information from '../src/container/Information';
import Footer from '../src/container/Footer';

export default {
  name: 'App',
  components: {
    Header,
    About,
    Works,
    Services,
    Team,
    Says,
    Sponsor,
    Information,
    Footer,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
</style>
