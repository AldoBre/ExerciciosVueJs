<template>
 
  <div>
    <Header/>
    <primeiroComponente></primeiroComponente>
    <LifeCycle/>
    <Pessoa/>
  </div>
  
</template>

<script>
  import primeiroComponente from './components/primeiroComponente.vue';
  import LifeCycle from './components/LifeCycle.vue';
  import Pessoa from './components/Pessoa.vue';
  import Header from './components/Header.vue'

  export default{
    name:'App',
    components:{
      primeiroComponente,
      LifeCycle,
      Pessoa,
      Header
    }
  }
</script>

<style>
  body{
    background-color: #333;
    color:white;
  }

  a{
    color: red;
  }
</style>