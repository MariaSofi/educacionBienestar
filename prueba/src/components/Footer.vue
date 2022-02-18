<template>
  <v-footer
    color="grey lighten-3"
    padless
  >
    <v-row
      justify="center"
      no-gutters
    >
  
      <v-btn
        color="black"
        text
        rounded
        class="my-2"
        :to="{name:'Home'}"
      >Inicio</v-btn>

  
      <v-btn
        color="black"
        text
        rounded
        class="my-2"
        :to="{name:'Servicios'}"
      >Formación - Cursos
      </v-btn>

        <v-btn
        color="black"
        text
        rounded
        class="my-2"
        :to="{name:'Informativa'}"
      >Informativa
      </v-btn>

         <v-btn
        color="black"
        text
        rounded
        class="my-2"
        :to="{name:''}"
      >Propósito
      </v-btn>

       <v-btn
        color="black"
        text
        rounded
        class="my-2"
        :to="{name:'Info'}"
      >Quiénes Somos
      </v-btn>

      <v-col
      color=""
        class="grey lighten-4 py-4 text-center black--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Neo-Development</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      links: [
        'Inicio ' ,
        'Formación - Cursos',
        'Informativa',
        'Propósito',
        'Quiénes Somos',
      ],
    }),
  }
</script>