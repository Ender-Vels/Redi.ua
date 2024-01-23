<template>
    <div class="Slider">
        <carousel 
        :items-to-show="1" 
        :autoplay="3000"
        :wrap-around="true"
        :transition="1000"
        >

    <slide v-for="slide in slides" :key="slide">
      <img :src="slide.img" alt="">
    </slide>

    <template #addons>
      <navigation />
      <pagination />
    </template>
  </carousel>
    </div>
    
</template>

<script>
import 'vue3-carousel/dist/carousel.css'
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel'
export default{
    components:{
        Carousel,
        Slide,
        Pagination,
        Navigation,

    },
    data(){
        return{
           slides:[
            {
                img:'https://redi.ua/wp-content/uploads/2021/02/23.png'
            },
            {
                img:'https://redi.ua/wp-content/uploads/2021/02/25.png'
            },

           ]
        }
    }
}
</script>

<style>
</style>