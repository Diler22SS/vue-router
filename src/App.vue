<template>
  <v-app>
    <NavigationBar />
    <v-content fluid>
      <router-view />
    </v-content>
    <FooterComponent />
  </v-app>
</template>

<script>
import NavigationBar from "./components/NavigationBar.vue";
import FooterComponent from "./components/FooterComponent.vue";
export default {
  name: 'App',
  components: {NavigationBar, FooterComponent}
}
</script>
