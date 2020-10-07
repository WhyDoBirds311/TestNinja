<template>
  <div>
    <appHeader></appHeader>
      <Ninjas></Ninjas>
    <appFooter></appFooter>
  </div>
</template>

<script>

import appHeader from "./components/header.vue";
import appFooter from "./components/footer.vue";
import Ninjas from "./components/ninjas.vue";

export default {
  components: {
    appHeader, appFooter, Ninjas
  },
  data () {
    return {
    }
  }
}
</script>

<style>

    
</style>
