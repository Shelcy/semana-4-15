<template>
  <v-content>
    <section id="Testimonios">
      <h2 class="display-2 font-weight-bold mb-3 text-uppercase text-center">
        Testimonios
      </h2>
      <br />

      <v-carousel :show-arrows="false" height="400">
        <v-carousel-item
          reverse-transition="fade-transition"
          transition="fade-transition"
        >
          <!-- <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src" reverse-transition="fade-transition"
                transition="fade-transition"> -->
          <v-row class="red--text d-flex justify-space-around">
            <v-card class="mx-auto" color="#CE93D8" max-width="350">
              <v-card-title>
                <v-icon large left> mdi-instagram </v-icon>
                <span class="title">Librería El club de los 27.</span>
              </v-card-title>

              <v-card-text class="headline font-weight-bold">
                “Estamos muy contentos porque la librería se ve más ordenada y
                tenemos fácil acceso a los libros que están almacenados” 
              </v-card-text>

              <v-card-actions>
                <v-list-item class="grow">
                  <v-list-item-avatar color="grey darken-3">
                    <v-img
                      class="elevation-6"
                      alt=""
                      src="https://www.emprendedores.es/wp-content/uploads/2016/02/ideas-para-montar-una-libreria-rentable.jpg"
                    >
                    </v-img>
                  </v-list-item-avatar>

                  <v-list-item-content>
                    <v-list-item-title
                      >Damian
                Leroux
                    </v-list-item-title>
                  </v-list-item-content>

                  <v-row align="center" justify="end" class="margenIcono">
                    <v-icon color="#D32F2F"> mdi-heart </v-icon>
                    <span class="subheading mr-2">26</span>
                  </v-row>
                </v-list-item>
              </v-card-actions>
            </v-card>

            <v-card class="mx-auto" color="#E57373" dark max-width="350">
              <v-card-title>
                <v-icon large left> mdi-pinterest </v-icon>
                <span class="title font-weight-light"
                  >Lenguas y Lingüísticas</span
                >
              </v-card-title>

              <v-card-text class="headline font-weight-bold">
                “Debido al nulo conocimiento que poseía sobre el tema, mis
                empleados se encontraban inconformes con las condiciones en las
                que debían trabajar, por el poco espacio que debían compartir.
                La asesoría prestada por Modularte fue invaluable para mejorar
                el rendimiento de mi empresa al permitirme usar el espacio más
                eficientemente.”
              </v-card-text>

              <v-card-actions>
                <v-list-item class="grow">
                  <v-list-item-avatar color="grey darken-3">
                    <v-img
                      class="elevation-6"
                      alt=""
                      src="https://mobiliario.mueblesparaoficinas.com.co/wp-content/uploads/2019/04/4-731x495.jpg"
                    >
                    </v-img>
                  </v-list-item-avatar>

                  <v-list-item-content>
                    <v-list-item-title>Miura Kaydo</v-list-item-title>
                  </v-list-item-content>

                  <v-row align="center" justify="end" class="margenIcono">
                    <v-icon class="mr-1"> mdi-heart </v-icon>
                    <span class="subheading mr-2">34</span>
                  </v-row>
                </v-list-item>
              </v-card-actions>
            </v-card>

            <v-card class="mx-auto" color="#42A5F5" dark max-width="350">
              <v-card-title>
                <v-icon large left> mdi-twitter </v-icon>
                <span class="title font-weight-light"
                  >La Cava de la guarda</span
                >
              </v-card-title>

              <v-card-text class="headline font-weight-bold">
                “Necesitaba que los vinos fueran almacenados en poco espacio,
                pero con los ángulos y condiciones de ventilación necesarias.
                Modularte fue capaz de diseñar repisas adecuadas y que además
                permitían cerrar las estanterías según fuera requerido. Fue un
                servicio excelente.”
              </v-card-text>

              <v-card-actions>
                <v-list-item class="grow">
                  <v-list-item-avatar color="grey darken-3">
                    <v-img
                      class="elevation-6"
                      alt=""
                      src="https://i.pinimg.com/originals/5f/52/37/5f523757b3d78ac3bb3e64d3933002af.jpg"
                    >
                    </v-img>
                  </v-list-item-avatar>

                  <v-list-item-content>
                    <v-list-item-title> Roxxane Peña.</v-list-item-title>
                  </v-list-item-content>

                  <v-row align="center" justify="end" class="margenIcono">
                    <v-icon class="mr-1" color="#D32F2F"> mdi-heart </v-icon>
                    <span class="subheading mr-2">256</span>
                  </v-row>
                </v-list-item>
              </v-card-actions>
            </v-card>
          </v-row>
        </v-carousel-item>
        <!--Inicio Segundo carusel -->
        <v-carousel-item
          reverse-transition="fade-transition"
          transition="fade-transition"
        >
          <!-- <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src" reverse-transition="fade-transition"
                transition="fade-transition"> -->
          <v-row class="red--text d-flex justify-space-around">
            <v-card class="mx-auto" color="#CE93D8" max-width="350">
              <v-card-title>
                <v-icon large left> mdi-instagram </v-icon>
                <span class="title">Instagram</span>
              </v-card-title>

              <v-card-text class="headline font-weight-bold">
                "Modularte fue capaz de diseñar repisas adecuadas y que además
                permitían cerrar las estanterías según fuera requerido. Fue un
                servicio excelente”.
              </v-card-text>

              <v-card-actions>
                <v-list-item class="grow">
                  <v-list-item-avatar color="grey darken-3">
                    <v-img
                      class="elevation-6"
                      alt=""
                      src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
                    >
                    </v-img>
                  </v-list-item-avatar>

                  <v-list-item-content>
                    <v-list-item-title>Evan You</v-list-item-title>
                  </v-list-item-content>

                  <v-row align="center" justify="end" class="margenIcono">
                    <v-icon class="mr-1" color="#D32F2F"> mdi-heart </v-icon>
                    <span class="subheading mr-2">256</span>
                  </v-row>
                </v-list-item>
              </v-card-actions>
            </v-card>

            <v-card class="mx-auto" color="#42A5F5" dark max-width="350">
              <v-card-title>
                <v-icon large left> mdi-twitter </v-icon>
                <span class="title font-weight-light">Twitter</span>
              </v-card-title>

              <v-card-text class="headline font-weight-bold">
                "La asesoría prestada por Modularte fue invaluable para mejorar
                el rendimiento de mi empresa al permitirme usar el espacio más
                eficientemente.”
              </v-card-text>

              <v-card-actions>
                <v-list-item class="grow">
                  <v-list-item-avatar color="grey darken-3">
                    <v-img
                      class="elevation-6"
                      alt=""
                      src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
                    >
                    </v-img>
                  </v-list-item-avatar>

                  <v-list-item-content>
                    <v-list-item-title>Andrew Lopif</v-list-item-title>
                  </v-list-item-content>

                  <v-row align="center" justify="end" class="margenIcono">
                    <v-icon class="mr-1" color="#D32F2F"> mdi-heart </v-icon>
                    <span class="subheading mr-2">6</span>
                  </v-row>
                </v-list-item>
              </v-card-actions>
            </v-card>

            <v-card class="mx-auto" color="#CE93D8" max-width="350">
              <v-card-title>
                <v-icon large left> mdi-instagram </v-icon>
                <span class="title">Instagram</span>
              </v-card-title>

              <v-card-text class="headline font-weight-bold">
                "Hacen trabajos excelentes, 100% recomensados”
              </v-card-text>

              <v-card-actions>
                <v-list-item class="grow">
                  <v-list-item-avatar color="grey darken-3">
                    <v-img
                      class="elevation-6"
                      alt=""
                      src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Pink&facialHairType=Blue&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
                    >
                    </v-img>
                  </v-list-item-avatar>

                  <v-list-item-content>
                    <v-list-item-title>Santiago Lopera</v-list-item-title>
                  </v-list-item-content>

                  <v-row align="center" justify="end" class="margenIcono">
                    <v-icon class="mr-1" color="#D32F2F"> mdi-heart </v-icon>
                    <span class="subheading mr-2">54</span>
                  </v-row>
                </v-list-item>
              </v-card-actions>
            </v-card>
          </v-row>
        </v-carousel-item>
      </v-carousel>
    </section>
  </v-content>
</template>

<script>
export default {
  name: "Testimonios",

  data() {
    return {
      items: [
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/sky.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/bird.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/planet.jpg",
        },
      ],
    };
  },
};
</script>

<style scoped>
.margenIcono {
  margin-right: -70%;
}
</style>