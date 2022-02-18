<template>


<v-container grid-list-md>
    <!-- Este Div es para la imagén en version celular -->
  <div class="d-lg-none d-xs-flex">
    <v-img src="@/assets/celularPortada.png">
      </v-img>
  </div>
  <!-- Este Div es para la imagén en version pantalla Normal -->
  <div  class="d-none d-lg-block">
 <v-parallax src="@/assets/proposito4.jpg"></v-parallax>
  </div>
 

    <h1 class="text-center"> Propósitos </h1>
    <v-slider disabled
        dense
        hint="im a hint"
        max="50"
        min="-50"
        ></v-slider>
       
  <!-- Tarjetas que contienen los propositos -->
  <v-layout row wrap>
    <!-- /////////////////////////////////////////////////////////////// -->
    <!-- primer proposito -->
    <!-- /////////////////////////////////////////////////////////////// -->
    <v-flex md6>
    <v-card
      class="mx-auto"
      color="grey lighten-3"
      max-width="800"
    >
    <v-card-title>
      <v-icon
        large
        left
      >
        mdi-school
        </v-icon>
        <!--<span class="text-h6 font-weight-light"></span> -->   
    </v-card-title>
  
    <v-card-text class="text-h5 font-weight-black ">
    Difundir el conocimiento generado en los estudios de los investigadores participantes.
    </v-card-text>
    </v-card>
    </v-flex>

    <!-- /////////////////////////////////////////////////////////////// -->
    <!-- Segundo proposito -->
    <!-- /////////////////////////////////////////////////////////////// -->
      <v-flex md6>
      <v-card
        class="mx-auto"
        color="grey lighten-3"
        max-width="800"
      >
      <v-card-title>
        <v-icon
          large
          left
        >
        mdi-school
        </v-icon>
        <!--<span class="text-h6 font-weight-light"></span> -->       
      </v-card-title>
  
      <v-card-text class="text-h5 font-weight-black ">
      Informar de temas de interés que contribuyan al bienestar personal y social de las personas.
      </v-card-text>
  
      </v-card> 
            
      </v-flex>
    <!-- /////////////////////////////////////////////////////////////// -->
    <!-- Tercer proposito -->
    <!-- /////////////////////////////////////////////////////////////// -->

      <v-flex md6>
      <v-card
        class="mx-auto"
        color="grey lighten-3"
        max-width="800"
      >
      <v-card-title>
        <v-icon
          large
          left
        >
        mdi-school
        </v-icon>
        <!--<span class="text-h6 font-weight-light"></span> -->       
      </v-card-title>
  
      <v-card-text class="text-h5 font-weight-black ">
      Formar en habilidades específicas para la salud, aprendizaje ….. y más.
      </v-card-text>
  
      </v-card> 
            
      </v-flex>
    <!-- /////////////////////////////////////////////////////////////// -->
    <!-- Cuarto proposito -->
    <!-- /////////////////////////////////////////////////////////////// -->

      <v-flex md6>
      <v-card
        class="mx-auto"
        color="grey lighten-3"
        max-width="800"
      >
      <v-card-title>
        <v-icon
          large
          left
        >
        mdi-school
        </v-icon>
        <!--<span class="text-h6 font-weight-light"></span> -->       
      </v-card-title>
      
      <v-card-text class="text-h5 font-weight-black ">
      Compartir los resultados de las investigaciones para interesados especializados en los temas de interés
      </v-card-text>
      </v-card> 
      </v-flex>

    <!-- /////////////////////////////////////////////////////////////// -->
    <!-- Quinto proposito -->
    <!-- /////////////////////////////////////////////////////////////// -->

      <v-flex >
      <v-card
        class="mx-auto"
        color="grey lighten-3"
        max-width="800"
      >
      <v-card-title>
        <v-icon
          large
          left
        >
        mdi-school
        </v-icon>
        <!--<span class="text-h6 font-weight-light"></span> -->       
      </v-card-title>
      
      <v-card-text class="text-h5 font-weight-black ">
      Intervenir para brindar apoyos específicos, guía y orientación a personas que lo soliciten a través de la plataforma, en periodos específicos del año.
      </v-card-text>
      </v-card> 
      </v-flex>

    </v-layout>
 
</v-container>
    

    
</template>