<template>
<div>
<Carousel/>
<tarjetas/>
<parrallax/>
<pasos/>
 <contacto/>

 <Footer/>

</div>
</template>

<script>
  
  import tarjetas from '../components/tarjetas.vue'
  import parrallax from '../components/parrallax.vue'
  import Carousel from '../components/Carousel'
  import pasos from '../components/pasos.vue'
  import Footer from '../components/Footer'
  import contacto from '../components/contacto.vue'
  

  export default {
    name: 'Home',

    components: {
      Carousel,tarjetas, parrallax,pasos,Footer, contacto
    },
  }
</script>
