<template>
<v-content>
   <section id="stats">
          <v-parallax :height="$vuetify.breakpoint.smAndDown ? 700 : 500"
            src="https://img.freepik.com/foto-gratis/pared-oscura-o-negra-vacia-estantes-hexagonales-pared-representacion-3d_92790-234.jpg?size=2000&ext=jpg">
            <v-container fill-height>
                 <h2 class="display-2 font-weight-bold mb-3 text-uppercase text-center">Nuestras Cifras</h2>

              <v-row class="mx-auto">
                 
                <v-col v-for="[value, title] of stats" :key="title" cols="12" md="3">
                  <div class="text-center">
                    <div class="display-3 font-weight-black mb-4" v-text="value"></div>

                    <div class="title font-weight-regular text-uppercase" v-text="title"></div>
                  </div>
                </v-col>
              </v-row>
            </v-container>
          </v-parallax>
        </section>
</v-content>
</template>

<script>
export default {
    name: 'Resultados',
    data() {
        return {
    stats: [
            ['24k', 'Empleados'],
            ['330k', 'Trabajos finalizados'],
            ['1m', 'Diseños'],
            ['5m', 'Clientes'],
          ],
    }
    }
}
</script>

<style>

</style>