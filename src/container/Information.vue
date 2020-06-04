<template>
  <section class="information">
      <div class="information-container">
        <div class="information__feedback">
         <div class="rows__contact-rows">
           <div class="form__group">
            <label class="form-label" for="name">Name</label>
            <input class="form-control" type="text" id="name" name="name" tabindex="1" required>
          </div>
          <div class="form__group">
            <label class="form-label" for="subject">Subject</label>
            <input class="form-control" type="subject" id="subject" name="subject" tabindex="2" required>
          </div>
          <div class="form__group">
            <label class="form-label" for="subject">E-mail</label>
            <input class="form-control" type="e-mail" id="e-mail" name="e-mail" tabindex="3" required>
          </div>
          <div class="form__group">
            <label class="form-label" for="message">Message</label>
            <textarea class="form-control" rows="2" cols="50" name="message" id="message" tabindex="4" required></textarea>
          </div>
          <div class="text-center">
            <button type="submit" class="btn btn-start-order">send message</button>
          </div>
        </div>
        </div>
        <div class="information__nav-map">
            <p class="adress">
              Adress line 1 <br>
              Adress line 2 <br>
              Phone: +548 945645 <br>
              Fax: +456456 54546 <br>
             <br>
              Web: www.designagency.net <br>
              E-mail: info@designagency.net</p>
            <img class="map" src="../assets/images/map.png" alt="map">
          </div>
      </div>
    </section> 
</template>

<script>
export default {

}
</script>

<style lang = "scss">
 
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

.rows__contact-rows{
 margin-top: 12px;
}

.form__group {
 margin-left: 30px;
} 

.form-label {
 width: 46px;
 height: 12px;
 opacity: 0.6;
 font-family: "Raleway", sans-serif;
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
 border-color:#7f7f7f;
}

.text-center {
 margin-left: 30px;
 margin-top: 55px;
}

.btn-start-order {
 width: 244px;
 height: 53px;
 border-radius: 2px;
 background-color: #71f6eb;
 border: none;
 font-family: "Montserrat", sans-serif;
 font-size: 18px;
 text-transform: uppercase;
 transition: ease-out 0.5s;
  &:hover {
   background: #fff;
   color: #000;}
}
/* </Contact Me */

/* Map-adress */
.information__nav-map {
 width: 500px;
 height: 461px;
 opacity: 0.71;
 box-shadow: 0 0 3px 0 #15151528;
 background-color: #021623;

}
.adress {
 width: 213px;
 opacity: 0.7;
 font-family: "Raleway", sans-serif;
 font-size: 15px;
 line-height: 1.6;
 letter-spacing: normal;
 text-align: left;
 color: #ffffffb3; 
 margin-left: 22px;  
 padding-top: 10px;

}
.map {
 margin-left: 22px;
}

/* <Map-adress */
</style>