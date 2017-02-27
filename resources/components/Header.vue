<template>
  <div class="triptip-header">
    <h1>Trip<strong>Tip</strong></h1>
    <div id="logo">tt</div>
  </div>
</template>
<style lang="scss">
.triptip-header {
  border-bottom: 1px solid #ccc;
  padding: 15px 20px;
  /*border-radius: 10px 10px 0 0;*/
  margin: -20px -20px 15px -20px;
  background: #34495e;
  /*background: #ff4b1f;*/
  box-shadow: 0 5px 17px rgba(0,0,0,.15); 
  color: #DDD;
}
h1 {
  text-transform: uppercase;
  font-size: 2em;
  margin: 0; padding: 0;
  color: #2ecc71;
  font-weight: 100;
  strong {
    color: #FFF;
  }
}
#logo {
  font-weight: bold;
  font-style: oblique;
  font-size: 32px;
  letter-spacing: -2px;
  background: #FFF;
  border-radius: 50%;
  color: #2ecc71;
  position: absolute;
  padding: 5px 17px 7px 15px;
  top: 9px; right: 15px;
}
</style>