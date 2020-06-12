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
        v-model="name"
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
        v-model="subject"
      />
    </div>
    <div class="form__group">
      <label class="form-label" for="subject">Email</label>
      <input
        class="form-control"
        type="email"
        id="email"
        name="email"
        tabindex="3"
        required
        v-model="email"  
      />
    </div>
    <div class="form__group">
      <label class="form-label" for="message">Message</label>
      <textarea
        class="form-control"
        rows="4"
        cols="50"
        name="message"
        id="message"
        tabindex="4"
        required
        v-model="message"
      ></textarea>
    </div>
  </form>
</template>

<script>
export default {
  data() {
    return {
      name: null,
      subject: null,
      email: null,
      message: null,
    };
  },
  methods: {

  },
}
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
  max-width: 550px;
  width: 100%;
  max-height: 60px;
  display: flex;
  border-radius: 0;
  border-width: 0 0 2px 0;
  border-style: none none solid none;
  box-shadow: none;
  background: none;
  color: white;
  border-color: #7f7f7f;
  font-family: 'Raleway', sans-serif;
  font-size: 13px;
  outline: none;
  
}
</style>
