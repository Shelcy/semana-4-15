<template>
<v-content>
 <section id="Servicios">
          <div class="py-12"></div>

          <v-container>
            <h2 class="display-2 font-weight-bold mb-3 text-uppercase text-center">Servicios</h2>

            <v-responsive class="mx-auto mb-12" width="56">
              <v-divider class="mb-1"></v-divider>

              <v-divider></v-divider>
            </v-responsive>

            <v-row>
              <v-col  v-for="({ src, text, title }, i) in articles" :key="i" cols="12" md="4">
                <v-img outlined :src="src" class="mb-4" height="275" max-width="100%"></v-img>

                <h3 class="font-weight-black mb-4 text-uppercase" v-text="title"></h3>

                <div class="title font-weight-light mb-5 align-stretch " v-text="text"></div>

                <!-- <v-btn class="ml-n4 font-weight-black align-end" text>
                  Continue Reading
                </v-btn> -->
              </v-col>
            </v-row>
          </v-container>

         
        </section>
</v-content>
</template>

<script>
export default {
    name: 'Servicios',
     data() {
        return {
          articles: [{
              src: 'https://mejorconsalud.as.com/wp-content/uploads/2018/07/estantes-sala-e1544699110291.jpg',
              title: 'Diseño personalizado',
              text: 'Ofrecemos un diseño personalizado según las necesidades de su empresa y sus productos.',
            },
            {
              src: 'https://mcconsultorias.com.co/portal/images/servicios/asesorias.jpg',
              title: 'Asesorías',
              text: 'Ofrecemos asesorías totalmente gratuitas con un diseñador de interiores con el fin de dar a nuestros clientes la mejor opción para optimizar los espacios disponibles para almacenaje o en su negocio. ',
            },
            {
              src: 'https://i2.wp.com/www.pintoressigloxxi.com/wp-content/uploads/2018/08/pago.jpg?fit=800%2C445&ssl=1',
              title: 'Facilidades de pago ',
              text: 'Contamos con convenios crediticios que le permitirán tener facilidades de pago en el diseño, construcción e instalación de sus modulares. ',
            },
          ],
        }
    }
}
</script>

<style>

</style>