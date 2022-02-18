<template>
<div>

<tarjetas/>

 <Footer/>

</div>
</template>

<script>
  import tarjetas from '../components/tarjetasSalud.vue'
  import Footer from '../components/Footer'
 
  export default {
    name: 'Salud',

    components: {
      tarjetas, Footer
    },
  }
</script>