<template>
  <div></div>
</template>

<script>
import autofit from 'autofit.js'

export default {
  name: 'AUTOJS',
  data() {
    return {}
  },
  mounted() {
    // 方案1：https://larryzhu-dev.github.io/autoLarryPages/autofit.js/use.html
   // 用了默认参数，等价于 autofit.init()
    autofit.init({
      dh: 1080,
      dw: 1920,
      el: "body",
      resize: true,
    });
  },
  methods: {
    
  }
}
</script>

<style>

</style>
