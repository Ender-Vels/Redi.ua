<template>
  <div> <Carusel/></div>
 
  <div class="category">
    <div class="category_nav">
      <div class="category_nav_element" >
        ddd
      </div>
    </div>
  </div>
</template>

<script>
import Carusel from './Carusel/CaruselSite.vue'
export default{
  components:{
    Carusel,
  },
  data(){
    return{
        images:[
          {
            title:'Iphones Б/У',
            img:'./assets/Category/1.png'
          },
        ]
    }
  }
}

</script>


<style>
.category_nav_element{
  background-color: brown;
}
</style>