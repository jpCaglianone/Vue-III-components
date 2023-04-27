<template>


  <botao msg="teste"></botao>

  
</template>

<script>


import myButton from "./components/myComp.vue";


export default {
  name: "App",
  components: {
    botao: myButton
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
