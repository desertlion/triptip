<template>
  <div class="triptip-container">
    <div class="trip-app">
      <Header />
      <!--<Sidebar />-->
      <nuxt/>
    </div>
    <!--<my-footer/>-->
  </div>
</template>

<script>
import MyFooter from '~components/Footer.vue'
import Sidebar from '~components/Sidebar.vue'
import Header from '~components/Header.vue'

export default {
  components: {
    MyFooter, Sidebar, Header
  }
}
</script>

<style lang="scss">
body {
  background: #b6b8c1;
  /*background: -moz-linear-gradient(top, #daffd5 0%, rgba(46,204,113,1) 100%);
  background: -webkit-gradient(left top, left bottom, color-stop(0%, #daffd5), color-stop(100%, rgba(46,204,113,1)));
  background: -webkit-linear-gradient(top, #daffd5 0%, rgba(46,204,113,1) 100%);
  background: -o-linear-gradient(top, #daffd5 0%, rgba(46,204,113,1) 100%);
  background: -ms-linear-gradient(top, #daffd5 0%, rgba(46,204,113,1) 100%);
  background: linear-gradient(to bottom, #daffd5 0%, rgba(46,204,113,1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#34495e', endColorstr='#2ecc71', GradientType=0 );*/
}
.trip-app {
  background: #FFF;
  position: absolute;
  z-index: 100;
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  border-radius: 10px;
  padding: 20px;
  width: 700px;
  box-shadow: 3px 15px 20px rgba(0,0,0,.25);
}
footer a {
  color: #FFF !important;
}
.container
{
  margin: 0;
  width: 100%;
  padding: 100px 0;
  text-align: center;
}

.button, .button:visited
{
  display: inline-block;
  color: #744d82;
  letter-spacing: 1px;
  background-color: #fff;
  border: 2px solid #744d82;
  text-decoration: none;
  text-transform: uppercase;
  padding: 15px 45px;
}

.button:hover, .button:focus
{
  color: #fff;
  background-color: #744d82;
}

.title
{
  color: #505153;
  font-weight: 300;
  font-size: 2.5em;
  margin: 0;
}
</style>
