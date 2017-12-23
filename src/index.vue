<template>
  <div>
    <h1>{{msg}}</h1>
    <Hello/>
  </div>
</template>

<script>
import Hello from './components/hello';
export default {
  data() {
    return {
      msg: 'Parcels'
    };
  },
  components: {
    Hello
  }
};
</script>

<style>
  div {
    background: red;
  }
</style>
