<template>
  <form>
    <div class="form__group">
      <label class="form-label" for="name">Name</label>
      <input
        class="form-control"
        type="text"
        id="name"
        name="name"
        tabindex="1"
        required
      />
    </div>
    <div class="form__group">
      <label class="form-label" for="subject">Subject</label>
      <input
        class="form-control"
        type="subject"
        id="subject"
        name="subject"
        tabindex="2"
        required
      />
    </div>
    <div class="form__group">
      <label class="form-label" for="subject">E-mail</label>
      <input
        class="form-control"
        type="e-mail"
        id="e-mail"
        name="e-mail"
        tabindex="3"
        required
      />
    </div>
    <div class="form__group">
      <label class="form-label" for="message">Message</label>
      <textarea
        class="form-control"
        rows="2"
        cols="50"
        name="message"
        id="message"
        tabindex="4"
        required
      ></textarea>
    </div>
  </form>
</template>

<script>
export default {
   
};
</script>

<style lang="scss" scoped>
.form__group {
  margin-left: 30px;
}
.form-label {
  width: 46px;
  height: 12px;
  opacity: 0.6;
  font-family: 'Raleway', sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 3.4;
  letter-spacing: normal;
  text-align: left;
  color: #ffffff99;
}
.form-control {
  display: flex;
  border-radius: 0;
  border-width: 0 0 2px 0;
  border-style: none none solid none;
  box-shadow: none;
  background: none;
  color: white;
  width: 550px;
  border-color: #7f7f7f;
}
</style>
