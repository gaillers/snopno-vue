<template>
  <GmapMap class="map" v-bind:center="{lat: 46.45, lng: 30.70}" v-bind:zoom="5"
  map-type-id="terrain"
  style="width: 455px; height: 224px">
  <GmapMarker v-bind:key="index" v-for="(m, index) in markers"
   v-bind:position="m.position" v-bind:clickable="true"/>
 </GmapMap>
</template>

<script>


export default {
 data () {
    return {
      centre: { lat: 46.45, lng: 30.70 },
      markers: [
       {
         position: { lat: 46.45, lng: 30.70 },
       },
      ]
    };
 }
};

</script>

<style lang = "scss" scoped>
 .map {
    margin-left: 22px;
 }
</style>