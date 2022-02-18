<template>
<v-container grid-list-md>
    <h1 class="text-center"> Acerca de </h1>
    <v-layout row wrap >
        <v-flex xs12 sm6 md4 lg3  >
            <v-card
            class="mx-2"
            max-width="600"
            
            >
                <v-img 
                src="@/assets/salud1.png">
                </v-img>

                     <v-card-title class="orange lighten-5">
                      <h2>Salud</h2>
                     </v-card-title>
                    <v-card-text>
                      
                En este sitio podrás encontrar  información importante para el cuidado de la salud física y Emocional de niños, adolescentes y adultos.
                    </v-card-text>
                      <v-card-actions>
                        <v-btn
                          text
                          color="teal accent-4"
                          @click="mostrar = true">
                          Mostrar Más
                           </v-btn>
                           </v-card-actions>

    <v-expand-transition>
        <v-card
        v-if="mostrar"
        class="transition-fast-in-fast-out v-card--reveal"
        style="height: 100%;"
        >
        <v-card-text class="pb-0">
          <p class="text-h4 text--primary">
            Informacion Adicional
          </p>
          <p>late 16th century (as a noun denoting a place where alms were distributed): from medieval Latin eleemosynarius, from late Latin eleemosyna ‘alms’, from Greek eleēmosunē ‘compassion’ </p>
        </v-card-text>
        <v-card-actions class="pt-0">
          <v-btn
            text
            color="teal accent-4"
            @click="mostrar=false"
          >
            Cerrar
          </v-btn>
          <v-btn color="primary" :to="{name:'Informativa'}">Conocer más </v-btn>
        </v-card-actions>
      </v-card>
   </v-expand-transition>
      </v-card>
        </v-flex>


 <v-flex xs12 sm6 md4 lg3  >
            <v-card
           class="mx-2"
            max-width="600"
            >
                <v-img 
                src="@/assets/edultosmayores1.png">
                </v-img>
                     <v-card-title class="deep-orange lighten-5">
                      <h2>Adultos Mayores</h2>
                    </v-card-title>
                <v-card-text>
               Envejecer activo y exitoso, encontrando y generando opciones para un envejecimiento exitoso, con diversas opciones de ejercios mentales
                    </v-card-text>
                      <v-card-actions>
                        <v-btn
                          text
                          color="teal accent-4"
                          @click="enseñar = true">
                          Mostrar Más
                           </v-btn>
                           </v-card-actions>

    <v-expand-transition>
        <v-card
        v-if="enseñar"
        class="transition-fast-in-fast-out v-card--reveal"
        style="height: 100%;"
        >
        <v-card-text class="pb-0">
          <p class="text-h4 text--primary">
            Informacion Adicional
          </p>
          <p>late 16th century (as a noun denoting a place where alms were distributed): from medieval Latin eleemosynarius, from late Latin eleemosyna ‘alms’, from Greek eleēmosunē ‘compassion’ </p>
        </v-card-text>
        <v-card-actions class="pt-0">
          <v-btn
            text
            color="teal accent-4"
            @click="enseñar=false"
          >
            Cerrar
          </v-btn>
          <v-btn color="primary" :to="{name:'Informativa'}">Conocer más </v-btn>
        </v-card-actions>
      </v-card>
   </v-expand-transition>
      </v-card>
        </v-flex>

        
        <v-flex xs12 sm6 md4 lg3>
            <v-card class="mx-2"
                    max-width="600"
             >
                <v-img 
                src="@/assets/sustentabilidad1.png">
                </v-img>
                     <v-card-title class= "green lighten-5">
                      <h2>Sustentabilidad</h2>
                    </v-card-title>
                    <v-card-text>
             Cómo lograr  atender  las necesidades presente  de los seres humanos sin descuidar lo que se hereda a las futuras generaciones, mediante actos responsables
                    </v-card-text>
                    <v-card-actions>
                    <v-btn
                      text
                      color="teal accent-4"
                      @click="show = true"
                    >
                  Mostrar más
                  </v-btn>
                  </v-card-actions>

    <v-expand-transition>
      <v-card
        v-if="show"
        class="transition-fast-in-fast-out v-card--reveal"
        style="height: 100%;"
      >
        <v-card-text class="pb-0">
          <p class="text-h4 text--primary">
            Informacion Adicional
          </p>
          <p>late 16th century (as a noun denoting a place where alms were distributed): from medieval Latin eleemosynarius, from late Latin eleemosyna ‘alms’, from Greek eleēmosunē ‘compassion’ </p>
        </v-card-text>
        <v-card-actions class="pt-0">
          <v-btn
            text
            color="teal accent-4"
            @click="show = false"
          >
            Cerrar
          </v-btn>
          <v-btn color="primary" :to="{name:'Informativa'}">Conocer más </v-btn>
        </v-card-actions>
      </v-card>
    </v-expand-transition>
            </v-card>
        </v-flex>
    
        <v-flex xs12 sm6 md4 lg3 >
            <v-card
            class="mx-2"
            max-width="600"
            >
                <v-img 
                src="@/assets/educacion2.png">
                </v-img>
                     <v-card-title class="deep-orange lighten-5" >
                      <h2 >Educación</h2>
                    </v-card-title>
                    <v-card-text>
                Aquí encontraras informacion correspondiente a la educacion, con diverso material de investigacion, en el ambito educativo.                  </v-card-text>
                   <v-card-actions>
      <v-btn
        text
        color="teal accent-4"
        @click="reveal = true"
      >
        Mostrar Más
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <v-card
        v-if="reveal"
        class="transition-fast-in-fast-out v-card--reveal"
        style="height: 100%;"
      >
        <v-card-text class="pb-0">
          <p class="text-h4 text--primary">
            Informacion Adicional
          </p>
          <p>late 16th century (as a noun denoting a place where alms were distributed): from medieval Latin eleemosynarius, from late Latin eleemosyna ‘alms’, from Greek eleēmosunē ‘compassion’ </p>
        </v-card-text>
        <v-card-actions class="pt-0">
          <v-btn
            text
            color="teal accent-4"
            @click="reveal = false"
          >
            Cerrar
          </v-btn>
          <v-btn color="primary" :to="{name:'Informativa'}">Conocer más </v-btn>
        </v-card-actions>
      </v-card>
    </v-expand-transition>
  </v-card>
  
</v-flex>
    </v-layout>
</v-container>
</template>

<script>
  export default {
    data: () => ({
      mostrar: false,
      show: false,
      reveal: false,
      enseñar: false,
     
    }),
  }
</script>


<style >

.v-card--reveal {
  bottom: 0;
  opacity: 1 !important;
  position: absolute;
  width: 100%;
}
main{
    background-image: url ('@/assets/diabetes.jpg');
    background-size:cover;
}
</style>