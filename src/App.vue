<template>
  <div id="app">
    <Navbar />
    <HelloWorld msg="Portfolio MLB"/>
  </div>
</template>

<script>
import { createApp } from 'vue';
import App from './App.vue';
import HelloWorld from './components/HelloWorld.vue';
import Navbar from './components/NavBar.vue';
import 'bootswatch/dist/litera/bootstrap.min.css'; // Chemin vers le thème Litera
import 'bootstrap/dist/css/bootstrap.min.css';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
  },
};

// Cette partie devrait être déplacée dans le fichier main.js (ou main.ts)
createApp(App).mount('#app');
</script>

<!-- CSS -->
<style>
  @import '@/assets/styles/main.css';
</style>
