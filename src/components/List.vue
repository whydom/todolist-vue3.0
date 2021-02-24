<template>
  <ul id="list">
    <listitme></listitme>
  </ul>
</template>

<script lang='ts'>
import { defineComponent } from 'vue';
import listitme from './ListItme.vue'
export default defineComponent({
  name: 'List',
  components: {
    listitme
  }

})
</script>
<style scoped>
  #list {
    width: 95%;
    border: 1px solid rgba(100, 100, 100,.3);
    margin: 0 auto;
    border-radius: 5px;
  }
</style>