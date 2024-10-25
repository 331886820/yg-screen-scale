<template>
  <div></div>
</template>

<script>
import BigScreenScale from 'yg-screen-scale'

export default {
  name: 'App',
  data() {
    return {}
  },
  mounted() {
    // 方案2：https://www.npmjs.com/package/yg-screen-scale
    this.BigScreenScale = new BigScreenScale({container: 'app'}, (scale) => {
      console.log('scale====>',scale);
    })
  },
  beforeUnmount() {
    // 移除监听
    this.BigScreenScale.clearListener()
  },
  methods: {
    
  }
}
</script>

<style>

</style>
