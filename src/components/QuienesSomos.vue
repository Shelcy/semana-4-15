<template>

  <section id="quienSomos" >
          

          <v-container class="text-center" >
            <h2 class="display-2 font-weight-bold ">¿Quienes somos?</h2>

            <v-responsive class="mx-auto mb-8" width="56">
              <v-divider class="mb-1"></v-divider>

              <v-divider></v-divider>
            </v-responsive>

            <v-responsive class="mx-auto title font-weight-light mb-8" max-width="720">
             Modularte es una empresa del sector de amoblado para oficinas y establecimientos de comercio que requieran mayor capacidad y ordenamiento en su inventario y/o espacios de almacenamiento. 
Garantizamos productos personalizados a las necesidades del cliente con materiales de calidad y acabados estéticos. Como empresa buscamos que nuestros clientes puedan aprovechar los espacios disponibles de forma óptima y elegante. 

            </v-responsive>
<br>
            <v-avatar class="elevation-12 mb-12" size="128">
              <v-img src="https://picsum.photos/seed/picsum/200/300"></v-img>
            </v-avatar>

            <div></div>

            <!-- <v-btn color="grey" href="https://vuetifyjs.com" outlined large>
              <span class="grey--text text--darken-1 font-weight-bold">
                Vuetify Documentation
              </span>
            </v-btn> -->
          </v-container>

          <div class="py-12"></div>
        </section>


</template>

<script>
export default {
    name: 'QuienesSomos'
}
</script>

<style scoped>
.contenedor{
    padding-top:-90px;
}

</style>