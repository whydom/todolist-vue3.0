<template>
  <div id="header">
    <input type="text" placeholder="请输入要添加的任务，按回车键确定">
  </div>
</template>

<script lang='ts'>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Header'

})
</script>
<style scoped>
  #header {
    width: 100%;
    padding-top: 10px;
    box-sizing: border-box;
  }
  #header > input {
    display: block;
    width: 95%;
    height: 30px;
    margin: 0 auto;
    border: 1px solid rgba(100, 100, 100,.3);
    border-radius: 5px;
    text-indent: 2rem;
    outline: none;
  }
  #header > input::placeholder {
    color: rgba(100,100,100,.3);
    text-indent: 2rem;
    
  }
</style>