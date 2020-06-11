<template>
  <section class="team">
      <div class="team-us">
        <TitleArticle titles="small team"/>
        <TextArticle texts="lorem ipsum dolor sit amet event landing template"/>
      </div>
      <div class="content-item">
        <ul ><!--Margeret-->
          <li class="content-item__list">
            <img src="../assets/images/team 1.png" alt="team 1">
            <div class="content-info">
              <div class="block-al"></div>
              <h3 class="content-text"><b>margaret</b> <br> IT recruiter  HR manager</h3>
              <p class="content-title">Lorem Ipsum is not simply is  an action designer random text
                It has roots in a piece. </p>
              <div class="social">
                <img class="social-png" src="../assets/images/facebook.png" alt="facebook">
                <img class="social-png" src="../assets/images/twitter.png" alt="twitter">
                <img class="social-png" src="../assets/images/message.png" alt="message">
              </div>
            </div>
          </li><!--Al Rayhan-->
          <li class="content-item__list">
            <img src="../assets/images/team 2.png" alt="team 2">
            <div class="content-info">
              <div class="block-al"></div>
              <h3 class="content-text"><b>al rayhan</b> / ui designer</h3>
              <p class="content-title">Lorem Ipsum is not simply is  an action designer random text
                It has roots in a piece. </p>
              <div class="social">
                <img class="social-png" src="../assets/images/facebook.png" alt="facebook">
                <img class="social-png" src="../assets/images/twitter.png" alt="twitter">
                <img class="social-png" src="../assets/images/dribbble.png" alt="dribbble">
                <img class="social-png" src="../assets/images/message.png" alt="message">
              </div>
            </div>
          </li><!--Richard-->
          <li class="content-item__list">
            <img src="../assets/images/team 3.png" alt="team 3">
            <div class="content-info">
              <div class="block-al"></div>
              <h3 class="content-text"><b>richard</b> / Ui/Ux designer</h3>
              <p class="content-title">Lorem Ipsum is not simply is  an action designer random text
                It has roots in a piece. </p>
              <div class="social">
                <img class="social-png" src="../assets/images/facebook.png" alt="facebook">
                <img class="social-png" src="../assets/images/twitter.png" alt="twitter">
                <img class="social-png" src="../assets/images/dribbble.png" alt="dribbble">
                <img class="social-png" src="../assets/images/message.png" alt="message">
              </div>
            </div>
          </li><!--Jayson-->
          <li class="content-item__list"> 
            <img src="../assets/images/team 4.png" alt="team 4">
            <div class="content-info">
              <div class="block-al"></div>
              <h3 class="content-text"><b>jayson</b> <br> management director </h3>
              <p class="content-title">Lorem Ipsum is not simply is  an action designer random text
                It has roots in a piece. </p>
              <div class="social">
                <img class="social-png" src="../assets/images/facebook.png" alt="facebook">
                <img class="social-png" src="../assets/images/twitter.png" alt="twitter">
                <img class="social-png" src="../assets/images/message.png" alt="message">
              </div>
            </div>
          </li><!--Elizabeth-->
          <li class="content-item__list">
            <img src="../assets/images/team 5.png" alt="team 5">
            <div class="content-info">
              <div class="block-al"></div>
              <h3 class="content-text"><b>elizabeth</b> <br> project menager </h3>
              <p class="content-title">Lorem Ipsum is not simply is  an action designer random text
                It has roots in a piece. </p>
              <div class="social">
                <img class="social-png" src="../assets/images/facebook.png" alt="facebook">
                <img class="social-png" src="../assets/images/twitter.png" alt="twitter">
                <img class="social-png" src="../assets/images/message.png" alt="message">
              </div>
            </div>
          </li><!--Steven-->
          <li class="content-item__list"> 
            <img src="../assets/images/team 6.png" alt="team 6">
            <div class="content-info">
              <div class="block-al"></div>
              <h3 class="content-text"><b>steven</b> <br> development team leader </h3>
              <p class="content-title">Lorem Ipsum is not simply is  an action designer random text
                It has roots in a piece. </p>
              <div class="social">
                <img class="social-png" src="../assets/images/facebook.png" alt="facebook">
                <img class="social-png" src="../assets/images/twitter.png" alt="twitter">
                <img class="social-png" src="../assets/images/message.png" alt="message">
              </div>
            </div>
          </li>
        </ul>
      </div>
    </section>
</template>

<script>
import TitleArticle from '../components/TitleArticle';
import TextArticle from '../components/TextArticle';

export default {
 name: 'Team',
 components: {
   TitleArticle,
   TextArticle,
   
 }
}
</script>

<style lang = "scss">
.team {
 max-width: 1920px;
 width: 100%;
 height: 1400px;
 background-color: #f9fbfb;
}
.team-us {
 width: 617px;
 margin: 0 auto;
 padding-top: 130px;
}
.content-item {
 width: 1200px;
 max-width: 100%;
 margin: 0 auto;

 & img {
  margin-bottom: 20px;
 }
 & ul{
  display: flex;
  margin: 0 auto;
  flex-wrap: wrap;
  justify-content: space-evenly;
  padding: 0;
 }
 & li {
  position: relative;  
  list-style-type: none;
 }
}

.content-info {
 opacity: 0;
 visibility: hidden;
 position: absolute;
 width: 335px;
 height: 241px;
 box-shadow: 2.7px 6.4px 16px 0 #1414152e;
 background-color: #6df6eb;
 top: 183px;
 left: 17px;
 transition: opacity 0.5s ease-in-out, visibility 0.5s ease-in-out;

 .block-al {
  position: relative;
  color: #fff;

  &::after {
    content: '';
    position: absolute;
    left: 25px;
    bottom: 0px;
    border: 13px solid transparent;
    border-bottom: 20px solid #6df6eb;
  }
 }
}

.content-item__list{
  position: relative;
 &:hover .content-info {
   opacity: 1;
   visibility: visible;
  }
 }

.content-text {
  width: 243px;
  opacity: 0.95;
  font-family: "Montserrat", sans-serif;
  font-size: 15px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.6;
  letter-spacing: 0.45px;
  text-align: center;
  color: #767070f3;
  text-transform: capitalize;
  margin-right: auto;
  margin-left: auto;
  margin-top: 35px;
   & b {
    font-size: 20px;
    font-weight: bold;
    letter-spacing: 1px;
    color: #000000f3;
    text-transform: uppercase;
  }
}
.content-title {
  width: 239px;
  opacity: 0.8;
  font-family: "Raleway", sans-serif;
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.5;
  letter-spacing: 0.16px;
  text-align: left;
  color: #000000cc;
  margin-left: auto;
  margin-right: auto;
  padding: 15px;
}


.social {
  height: 15px;
  padding: 10px 50px;
  .social-png {
    margin-right: 10px;
  }
}
</style>