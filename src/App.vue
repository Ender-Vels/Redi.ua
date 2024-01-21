<script>
import HeaderSite from './components/Header/HeaderSite.vue'

export default{
  components:{
  HeaderSite
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
  </header>

  <RouterView />
</template>

<style>
*{
  margin: 0px;
  padding: 0px;
}
</style>
