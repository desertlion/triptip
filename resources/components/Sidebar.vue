<template>
  <ul class="triptip-sidebar">
    <li>
      <nuxt-link to="/"><i class="fa fa-home fa-2x"></i></nuxt-link>
    </li>
    <li>
      <nuxt-link to="/about"><i class="fa fa-info-circle fa-2x"></i></nuxt-link>
    </li>
  </ul>
</template>
<style lang="scss">
  .triptip-sidebar {
    background: rgb(52,73,94);
    list-style: none;
    margin: 0; padding: 10px;
    position: absolute;
    border-radius: 5px 0 0 5px;
    top: 150px;
    right: 100%;
    box-shadow: 0 3px 15px rgba(0,0,0,.3);
    z-index: 1;
    a {
      color: #DDD;
      display: block;
      line-height: 3em;
      cursor: pointer;
    }
  }
</style>