<template>
  <div class="home">
    <nav-bar class="header"/><!--顶部导航部分-->
    <nav-top class="nav"/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import navBar from '@/components/navBar/navBar.vue'
import navTop from '@/components/nav/nav.vue'
export default {
  name: 'Home',
  components: {
    // HelloWorld
    navBar,
    navTop
  }
}
</script>

<style scoped>
@import '../assets/css/navBar/navBar.css';
@import '../assets/css/nav/nav.css';
.header{
  top: 0;
}
.nav{
  width: 999px;
  margin: 0 auto;
}
</style>