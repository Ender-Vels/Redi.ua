<script>
import HeaderSite from './components/Header/HeaderSite.vue'
import HomePage from './components/HomePage.vue';
export default{
  components:{
  HeaderSite,
  HomePage
},
  data(){
    return{

    }
  }
}
</script>

<template>
  <header>
    <HeaderSite/>
    <HomePage/>
  </header>

  <RouterView />
</template>

<style>
*{
  margin: 0px;
  padding: 0px;
}
</style>
