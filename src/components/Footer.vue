<template>
  <div id="footer">
    <div>
      <input type="checkbox">
    </div>
    <div>
      已完成<span>0</span>
      /全部<span>0</span>
    </div>
    <div>
      清除已完成的任务
    </div>
  </div>
</template>

<script lang='ts'>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Footer'

})
</script>
<style scoped>
  #footer {
    display: flex;
    justify-content: space-between;
    margin-top: 15px;
  }
  #footer > div:nth-child(2) {
    flex: 1;
  }
  #footer > div:nth-child(3) {
    background-color: unset;
    background-color: #f00;
    border-radius: 5px;
    padding: 5px;
    box-sizing: border-box;
    cursor: pointer;
    -webkit-user-select: none;
  }
  #footer > div:nth-child(3):active {
    background-color: #f2f2f2;
  }
</style>