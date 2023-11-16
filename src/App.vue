<script>
  import MyCounter from './components/MyCounter.vue';
  import MagicBox from './components/MagicBox.vue';


  export default{
    components: {
      MyCounter,
      MagicBox,
    },
  };
</script>

<template>
  <main>
    <MyCounter/>
    <MagicBox/>
  </main>
</template>

<style scoped>

</style>
