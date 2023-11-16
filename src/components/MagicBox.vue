<script>
  export default{
    data() {
      return {
        visible: true,
        color: 'black'
      };
    },
    methods: {
	    method1() { this.visible = !this.visible },
      method2() { this.color = 'red' },
    }
  };
</script>

<template>
  <div class="box" v-if="visible" @dblclick="method1()" @click="method2()"
  :style="{ backgroundColor: color }" ></div>
</template>

<style scoped>
  .box {
    width:200px;
    height:200px;
  }
</style>
