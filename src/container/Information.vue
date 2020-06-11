<template>
  <section class="information">
    <div class="information-container">
      <div class="information__feedback">
        <div class="rows__contact-rows">
          <Forms />
          <FormsButton />
        </div>
      </div>
      <Location/>
    </div>
  </section>
</template>

<script>
import FormsButton from '../components/Information/forms/FormsButton';
import Forms from '../components/Information/forms/Forms';
import Location from '../components/Information/forms/Location'

export default {
  name: 'Information',
  components: {
    Forms,
    FormsButton,
    Location
    
  },
};
</script>

<style lang="scss">
.information {
  position: relative;
  max-width: 1920px;
  width: 100%;
  height: 704px;
  background: url('../assets/images/info.png') round;
}
.information-container {
  position: absolute;
  max-width: 1920px;
  width: 100%;
  display: flex;
  justify-content: space-evenly;
  top: 120px;
}
/* .Contact Me */
.information__feedback {
  width: 614px;
  height: 460px;
  opacity: 0.71;
  box-shadow: 0 0 30px 0 #1515151e;
  background-color: #021623;
}
.rows__contact-rows {
  margin-top: 12px;
}
</style>
