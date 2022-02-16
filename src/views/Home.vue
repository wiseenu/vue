<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/emblem.jpg" style="width:500px;height:500px">
    <HelloWorld msg="Welcome to Wisnu's Portofolio"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>
