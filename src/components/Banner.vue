<template>
    <div>
        <v-carousel :show-arrows="false" height="600" class="text-dark">
            <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src" reverse-transition="fade-transition"
                transition="fade-transition">
                <v-col class=" text-center" cols="12" tag="h1">
                    <span :class="[$vuetify.breakpoint.smAndDown ? 'display-3' : 'display-2']"
                        class="font-weight-light">
                        {{item.text1}}
                    </span>

                    <br />

                    <span :class="[$vuetify.breakpoint.smAndDown ? 'display-6' : 'display-6']"
                        class="font-weight-black">
                        {{ item.text2 }}
                    </span>

                    <!-- <v-btn class="align-self-end" fab outlined @click="$vuetify.goTo('#Servicios')">
                        <v-icon>mdi-chevron-double-down</v-icon>
                    </v-btn> -->



                </v-col>
            </v-carousel-item>
        </v-carousel>
    </div>
</template>

<script>
    export default {
        name: "Banner",

        data() {
            return {
                items: [{
                        src: "https://house22site.files.wordpress.com/2017/08/vfdsbghjjhgfd.jpg?w=740", 
                        text1: "Repisas Colmena",
                        text2: "Repisas tipo biblioteca con forma de Colmena y tamaño ajustado al producto que necesite almacenar. "
                    },
                    {
                        src: "https://www.maderformas.co/wp-content/uploads/2016/05/DSC01624-1024x768.jpg",
                    text1: "Repisas con o sin puertas",
                        text2: "Repisas a la pared o al piso con o sin puertas con compartimientos personalizados al producto que busca almacenar. "
                    },
                    {
                        src: "https://lh3.googleusercontent.com/proxy/gyy8yWaQ2qLGjnEk_ui86IDVossCSGam9RPFwaT-Hs0hO7M9FNzy58b7liraj02KBp1qkYt22VVPAsR3eOvti-RLcTgaj8Uit9zQFiSrlEByCH1gdA6RAkdwuvv6PGOHbQWHTdU",
                    text1: "Archivadores multiuso personalizados",
                        text2: "Archivadores tipo cajón con divisiones interiores dependiendo del tamaño del producto y sus necesidades. "
                    },
   
                ],
            };
        },
    };
</script>

<style>
</style>