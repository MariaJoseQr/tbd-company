<template>
  <v-container class="my-4">
    <div>
      <h1>Inicio</h1>
      <p>Bienvenido a la página de Inicio!</p>
    </div>
  </v-container>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Footer,
  },
};
</script>
