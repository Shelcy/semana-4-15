<template>
  <!-- <v-app-bar app color="white" height="80"> -->
<div>


  <v-app id="inspire">
    <v-app-bar app color="white" flat height="90">
      <!-- <v-avatar :color="$vuetify.breakpoint.smAndDown ? 'grey darken-1' : 'transparent'" size="32"></v-avatar> -->

      <v-tabs centered class="ml-n9" color="grey darken-1">
        <!-- <v-tab v-for="link in links" :key="link" :to="{name: link.ruta}" exact @click="$vuetify.goTo('#' + {name: link.ruta})">
                    {{ link.text }}
                </v-tab> -->
        <v-tab @click="$vuetify.goTo('#')"> Inicio </v-tab>
        <v-tab @click="$vuetify.goTo('#Servicios')"> Servicios </v-tab>
        <v-tab @click="$vuetify.goTo('#Testimonios')"> Testimonios </v-tab>
        <v-tab @click="$vuetify.goTo('#quienSomos')"> ¿Quienes somos? </v-tab>
        <v-tab @click="$vuetify.goTo('#Contactanos')"> Contactanos </v-tab>
        <v-tab @click="salir()" icon v-if="logueado">
          <v-icon>logout</v-icon> Salir
        </v-tab>
        <v-tab :to="{ name: 'login' }" icon v-else>
          <v-icon> mdi-account-arrow-right </v-icon> Login

          
        </v-tab>
        
        <!-- </v-app-bar> -->

        
      <!-- <v-avatar
        class="hidden-sm-and-down"
        color="grey darken-1 shrink"
        size="32"
      ></v-avatar> -->
      </v-tabs>
    </v-app-bar>
<!-- <div ><v-content>
          <v-container fluid fill-height>
            <v-slide-y-transition mode="out-in">
              <router-view />
            </v-slide-y-transition>
          </v-container>
        </v-content>> -->


   
      
  </v-app>

  <v-content>
          <v-container fluid fill-height>
            <v-slide-y-transition mode="out-in">
              <router-view />
            </v-slide-y-transition>
          </v-container>
        </v-content>> 

  </div>

  <!-- <router-view />  -->

  <!-- </v-app-bar> -->
</template>

<script>
export default {
  name: "Menu",
  data() {
    return {

         
    //     drawer: false,
    //     estado: 1,
      links: [
        {
          text: "Inicio",
          ruta: "/",
        },
        {
          text: "Servicios",
          ruta: "Servicios",
        },
        {
          text: "¿Quienes somos?",
          ruta: "quienSomos",
        },
        {
          text: "Contactanos",
          ruta: "contacto",
        },
      ],
    };
  },

  computed: {
    logueado() {
      return this.$store.state.usuario;
    },
  },
  created() {
    this.$store.dispatch("autoLogin");
  },
  methods: {
    salir() {
      this.$store.dispatch("salir");
      this.estado = 1;
    },

    ingresar() {
      this.estado = 0;
    },

    home() {
      this.estado = 1;
    },
  },
};
</script>

<style scoped>
#inspire {
  height: 93px;
}
</style>