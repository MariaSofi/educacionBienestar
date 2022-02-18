<template>
    
<container >
  
    <h1 class="text-center"> Quiénes Somos</h1>
     <v-slider disabled
dense
hint="im a hint"
max="50"
min="-50"
></v-slider>
<prueba-componente/>
<equipo/>
<Footer/>
</container>

</template>
<script>
 
 import Footer from '../components/Footer'
 import equipo from '../components/equipo.vue'
 import pruebaComponente from '../components/pruebaComponente.vue'
export default {
  components: {
     Footer,equipo,pruebaComponente
    },
data () {
  return {
        items: [
          {
            src: 'https://scontent.fcen1-1.fna.fbcdn.net/v/t1.6435-9/151205759_3663686247083296_3271210901438188425_n.jpg?_nc_cat=111&ccb=1-3&_nc_sid=e3f864&_nc_eui2=AeFi0Qh0Cgw51meMbyd6DgnW1j0xLyqoT4vWPTEvKqhPixC8eLZVRcG1W-75qsjiLqOUK3ZLxvAB1YUg0VjJZ9f3&_nc_ohc=i6PtJnYZYZgAX9dXgcH&_nc_ht=scontent.fcen1-1.fna&oh=6e0bb4ec01885ad02e5b1ea0fdc1e3d9&oe=60ECF06E',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    },
  }
</script>

<style scoped>

</style>