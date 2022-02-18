<template>
<v-container grid-list-md>
    <h1 class="text-center"> Salud </h1>

    <h2 class="text-center">Bienvenido a este espacio en el cual podrás encontrar información valiosa para cuidar de tu salud física y emocional</h2>
    
    <v-layout row wrap >
        
        <!-- Primera tarjeta -->
        <v-flex xs12 sm6 md4 lg3  >
            <v-card
            class="mx-2"
            max-width="600" 
            >
                <!-- Imagen de la tarjeta 1 -->
                <v-img 
                src="@/assets/diab1.jpg">
                </v-img>
                    <!-- Titulo 1 -->
                    <v-card-title class="blue lighten-2">
                        <h2>Bienestar y autocuidado en diabetes</h2>
                    </v-card-title>
                   
                    <v-card-actions class="blue lighten-2">
                    <!-- Boton 1 -->
                    <v-btn
                        
                        rounded
                        outlined
                        color="grey lighten-5"
                        @click="mostrar = true">
                        Mostrar Más
                    </v-btn>
                    </v-card-actions>
            <!-- Tarjeta expandible de Mostrar mas -->
            <v-expand-transition>
            <!-- tarjeta con información -->
            <v-card
            v-if="mostrar"
            class="transition-fast-in-fast-out v-card--reveal "
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

      <!-- Segunda tarjeta -->
        <v-flex xs12 sm6 md4 lg3  >
            <v-card
            class="mx-2"
            max-width="600" 
            >
                <!-- Imagen de la tarjeta 1 -->
                <v-img 
                src="@/assets/diab1.jpg">
                </v-img>
                    <!-- Titulo 2 -->
                    <v-card-title class="blue lighten-2">
                        <h2>Bienestar y autocuidado en diabetes</h2>
                    </v-card-title>
                   
                    <v-card-actions class="blue lighten-2">
                    <!-- Boton 2 -->
                    <v-btn
                        
                        rounded
                        outlined
                        color="grey lighten-5"
                        @click="enseñar = true">
                        Mostrar Más
                    </v-btn>
                    </v-card-actions>
            <!-- Tarjeta expandible de Mostrar mas -->
            <v-expand-transition>
            <!-- tarjeta con información -->
            <v-card
            v-if="enseñar"
            class="transition-fast-in-fast-out v-card--reveal "
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

      <!-- Tercera tarjeta -->
        <v-flex xs12 sm6 md4 lg3  >
            <v-card
            class="mx-2"
            max-width="600" 
            >
                <!-- Imagen de la tarjeta 3 -->
                <v-img 
                src="@/assets/diab1.jpg">
                </v-img>
                    <!-- Titulo 3 -->
                    <v-card-title class="blue lighten-2">
                        <h2>Bienestar y autocuidado en diabetes</h2>
                    </v-card-title>
                   
                    <v-card-actions class="blue lighten-2">
                    <!-- Boton 3 -->
                    <v-btn
                        
                        rounded
                        outlined
                        color="grey lighten-5"
                        @click="show = true">
                        Mostrar Más
                    </v-btn>
                    </v-card-actions>
            <!-- Tarjeta expandible de Mostrar mas -->
            <v-expand-transition>
            <!-- tarjeta con información -->
            <v-card
            v-if="show"
            class="transition-fast-in-fast-out v-card--reveal "
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
                    @click="show=false"
                >
                Cerrar
                </v-btn>
                <v-btn color="primary" :to="{name:'Informativa'}">Conocer más </v-btn>
            </v-card-actions>
            </v-card>
            </v-expand-transition>
            </v-card>
        </v-flex>
        
     <!-- Cuarta tarjeta -->
        <v-flex xs12 sm6 md4 lg3  >
            <v-card
            class="mx-2"
            max-width="600" 
            >
                <!-- Imagen de la tarjeta 4 -->
                <v-img 
                src="@/assets/diab1.jpg">
                </v-img>
                    <!-- Titulo 4 -->
                    <v-card-title class="blue lighten-2">
                        <h2>Bienestar y autocuidado en diabetes</h2>
                    </v-card-title>
                   
                    <v-card-actions class="blue lighten-2">
                    <!-- Boton 4 -->
                    <v-btn
                        
                        rounded
                        outlined
                        color="grey lighten-5"
                        @click="reveal = true">
                        Mostrar Más
                    </v-btn>
                    </v-card-actions>
            <!-- Tarjeta expandible de Mostrar mas -->
            <v-expand-transition>
            <!-- tarjeta con información -->
            <v-card
            v-if="reveal"
            class="transition-fast-in-fast-out v-card--reveal "
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
                    @click="reveal=false"
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