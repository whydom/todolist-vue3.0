<template>
  <li class="itme">
    <div>
      <input type="checkbox">
    </div>
    <div>
      <p>xxx</p>
    </div>
    
  </li>
</template>

<script lang='ts'>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'ListItme'

})
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
}
  .itme {
    width: 100%;
    height: 30px;
    display: flex;
    margin-top: 10px;
    border-bottom: 1px solid rgba(100,100,100,.3);
  }
  .itme > div {
    width: 100%;
    height: 100%;
    text-align: center;
    line-height: 30px;
  }
  .itme > div:nth-child(1) {
    flex: 1;
  }
  .itme > div:nth-child(1) > input {
    margin-left: 10px;
  }
  .itme > div:nth-child(2) > p {
    text-align: left;
    text-indent: 2rem;
  }
</style>