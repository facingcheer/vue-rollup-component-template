<template >
<div class="container">
   {{bundler}}
</div>
 
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      bundler: 'Parcel'
    }
  }
})
</script>

<style lang="scss" scoped>
.container {
  color: green;
}
</style>