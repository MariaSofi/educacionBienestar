<template>
<v-container grid-list-md-lg>
  <div class="d-lg-none">
<h3 class="text-center">Consejos para mejorar tú salud</h3>
  <v-stepper
    v-model="e6"
    vertical
  >
   
    <v-stepper-step
      :complete="e6 > 1"
      step="1"
        max-width="300" 
    >
   
      Cuida tú alimentación
      <small> Come bien</small>
    </v-stepper-step>

    <v-stepper-content step="1">
      <v-card
        
       class="mb-1"
        height="280px"
      >
        <v-img 
                src="@/assets/plato.jpg">
                </v-img>
                <v-spacer></v-spacer>
               <v-card-text>
                 
                  Haz de la variedad de frutas, vegetales y granos integrales, la base de tu alimentación. Recuerda que es recomendable consumir 5 porciones de frutas y verduras al día
                  
               </v-card-text>
        </v-card>

      <v-btn
        
        color="primary"
        @click="e6 = 2"
      >
        Paso 2
      </v-btn>
    
    </v-stepper-content>

    <v-stepper-step
      :complete="e6 > 2"
      step="2"
    >
      Haz deporte, ¡Muevete!
    </v-stepper-step>

    <v-stepper-content step="2">
      <v-card
          class="mb-1"
        height="280px"
      >
           <v-img 
           height="150"
                src="@/assets/ejercicio.jpg">
                </v-img>
                <v-spacer></v-spacer>
               <v-card-text>
                 Practicar diariamente una actividad física moderada y a largo plazo, como puede ser caminar a buen ritmo durante 30 minutos, tiene numerosos beneficios para la salud
               </v-card-text>
      </v-card>
      <v-btn
        color="primary"
        @click="e6 = 3"
      >
        Paso 3
      </v-btn>
         <v-btn text
      @click="e6 = 1">
        Retroceder
      </v-btn>
    </v-stepper-content>

    <v-stepper-step
      :complete="e6 > 3"
      step="3"
    >
     Duerme bien
    </v-stepper-step>

    <v-stepper-content step="3">
      <v-card
         class="mb-1"
        height="280px"
      >
       <v-img 
       height="150"
                src="@/assets/sueño.jpg">
                </v-img>
                <v-spacer></v-spacer>
               <v-card-text>
               Y bien ¿qué horas de sueño son las adecuadas? Las recomendaciones generales dependen de la edad, como se muestra en la imagen
               </v-card-text>
      </v-card>
      <v-btn
        color="primary"
        @click="e6 = 4"
      >
        Paso 4
      </v-btn>
      <v-btn text
      @click="e6 = 2">
        Retroceder
      </v-btn>
    </v-stepper-content>

    <v-stepper-step step="4">
     ¡No te olvides de tu salud mental!
    </v-stepper-step>
    <v-stepper-content step="4">
      <v-card
        
        class="mb-1"
        height="280px"
        
      >
      La salud mental y la física están estrechamente vinculadas, pues si una no es buena repercutirá negativamente en la otra y viceversa. 

Hoy en día sabemos que el estrés está asociado a un estilo de vida menos saludable, propiciando adicciones al tabaco y al alcohol, y una peor alimentación. 
      </v-card>
      <v-btn
        color="primary"
        @click="e6 = 1"
      >
        Repetir
      </v-btn>
      <v-btn
     text
      @click="e6 = false"
      >
        Cerrar
      </v-btn>
    </v-stepper-content>
  </v-stepper>
  </div>
</v-container>
</template>

<script>
  export default {
    data () {
      return {
        e6: 1,
      }
    },
  }
</script>