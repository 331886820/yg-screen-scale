// 全屏适配方案1: npm install autofit   文档-----https://larryzhu-dev.github.io/autoLarryPages/autofit.js/use.html
// 全屏适配方案2: npm install yg-screen-scale     文档-------https://www.npmjs.com/package/yg-screen-scale
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <!-- <AutoJs /> -->
  <YgScreenScale />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import AutoJs from './components/autojs.vue'
import YgScreenScale from './components/yg-screen-scale.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    // AutoJs,
    YgScreenScale
  },
  data() {
    return {

    }
  },
  mounted() {

  },
  methods: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
