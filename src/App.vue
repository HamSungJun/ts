<template>
    <div class="row">Hello TS Vue</div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'App',
  mounted() {
    this.greet('Heelo wwerwr');
  },
  methods: {
    greet(message: string):void {
      console.log(message);
    },
  },
});
</script>

<style lang="scss">
    .row{
        width: 100vw;
        height: 100vh;
        color: red;
    }
</style>
