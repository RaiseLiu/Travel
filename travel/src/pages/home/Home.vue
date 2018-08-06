<template>
  <home-header></home-header>
</template>

<script>
import HomeHeader from './components/Header'
export default {
  name: 'Home',
  // 局部组件声明
  components: {
    HomeHeader
  }
}
</script>

<style>
  .home {
    font-size: 50px;
  }
</style>
