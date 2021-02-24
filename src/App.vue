<template>
  <div id="wrap">
    <Header></Header>
    <list></list>
    <Footer></Footer>
  </div>
</template>

<script lang='ts'>
import { defineComponent } from 'vue';
import Header from './components/Header.vue'
import list from './components/List.vue'
import Footer from './components/Footer.vue'
export default defineComponent({
  name: 'App',
  components: {
    Header,
    list,
    Footer

  }
})
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
}
  #wrap {
    width: 500px;
    border-radius: 5px;
    box-shadow: 0 0 5px rgba(100, 100, 100, .3);
    margin: 0 auto;
  }
</style>
