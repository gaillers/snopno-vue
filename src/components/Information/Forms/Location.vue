<template>
  <div class="location">
    <p class="adress">
      Adress line 1 <br />
      Adress line 2 <br />
      Phone: +548 945645 <br />
      Fax: +456456 54546 <br />
      <br />
      Web: www.designagency.net <br />
      E-mail: info@designagency.net
    </p>
    <GoogleMapLoader/>
  </div>
</template>

<script>
import GoogleMapLoader from '../forms/map/GoogleMapLoader'
export default {
  name: 'Location',
  components: {
    GoogleMapLoader
  }
};

</script>

<style lang="scss">
.location {
  width: 500px;
  height: 461px;
  opacity: 0.71;
  box-shadow: 0 0 3px 0 #15151528;
  background-color: #021623;
}
.adress {
  width: 213px;
  opacity: 0.7;
  font-family: 'Raleway', sans-serif;
  font-size: 15px;
  line-height: 1.6;
  letter-spacing: normal;
  text-align: left;
  color: #ffffffb3;
  padding: 23px 20px;
}

</style>
