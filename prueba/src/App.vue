<template>
  <v-app>
    <nav>
        <v-toolbar flat app class="white" >
            <v-app-bar-nav-icon class="grey--text" @click="drawer = !drawer"></v-app-bar-nav-icon>

            <v-toolbar-title class="text-uppercase grey--text">
                <span class="font-weight-light">Educacion Para El</span>
                <span> Bienestar</span>
            </v-toolbar-title>
            <v-spacer></v-spacer>
        <v-toolbar-items> 
            <div class="d-none d-lg-block">
            <v-btn class="ma-2" rounded large outlined color="primary" :to="{name:'Home'}">Principal </v-btn>
            <v-btn class="ma-2" rounded large outlined color="pink" :to="{name: 'Servicios'}">Formación - Cursos</v-btn>
            <v-btn class="ma-2" rounded large outlined color="secondary" :to="{name:'Informativa'}">Informativa</v-btn>
            <v-btn class="ma-2" rounded large outlined color="primary" :to="{name: 'propo'}">Propósito</v-btn>
            <v-btn class="ma-2" rounded large outlined color="blue" :to="{name: 'Info'}">Quiénes Somos</v-btn>
            <v-btn class="ma-2" rounded large outlined color="blue" :to="{name: 'Salud'}">Salud</v-btn>

            </div>
         </v-toolbar-items> 
        </v-toolbar>

   <v-navigation-drawer
      v-model="drawer"
      absolute
      temporary
    >
      <v-list
        nav
        dense
      >
        <v-list-item-group
          v-model="group"
          active-class="text-uppercase grey--text"
        >
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-home</v-icon>
            </v-list-item-icon>
            <v-btn  text color="text-uppercase grey--text" x small  :to="{name:'Home'}">Principal </v-btn>
          </v-list-item>

            <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-account</v-icon>
            </v-list-item-icon>
            <v-btn  text color="text-uppercase grey--text" x small  :to="{name:'Servicios'}">Formacion-Cursos</v-btn>
          </v-list-item>
          
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-alert-circle</v-icon>
            </v-list-item-icon>
            <v-btn  text color="text-uppercase grey--text" x small  :to="{name:'Informativa'}">Informativa</v-btn>
          </v-list-item>

          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-clipboard-arrow-down-outline</v-icon>
            </v-list-item-icon>
            <v-btn  text color="text-uppercase grey--text" x small  :to="{name:'propo'}">Propósito</v-btn>
          </v-list-item>
      
            <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-help-circle-outline</v-icon>
            </v-list-item-icon>
            <v-btn  text color="text-uppercase grey--text" x small  :to="{name:'Info'}">Quienes Somos</v-btn>
          </v-list-item>
          
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
    </nav>
    
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => {
    //
    
    return{
      drawer : false,
      
    }
  },
};
</script>