<template>
  <div class="micro">
    <div id="sub-view" />
  </div>
</template>
<script>
import { registerMicroApps, start } from 'qiankun'

export default {
  name: 'Micro',
  data() {
    return {}
  },
  mounted() {
    registerMicroApps([
      {
        name: 'vueApp',
        entry: '//localhost:9520',
        container: '#sub-view',
        activeRule: 'micro/vue'
      }
    ]);
    start();
  },
  methods: {
  }
};
</script>
<style lang='scss' scoped>
</style>
