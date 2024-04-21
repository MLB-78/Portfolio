<template>
  <div id="app">
    <Navbar />,
    <HomePage/>,
    <CardProjects/>,
    
  </div>
</template>

<script>
import { createApp } from 'vue';
import App from './App.vue';
import HomePage from './components/HomePage.vue';
import Navbar from './components/NavBar.vue';
import CardProjects from './components/CardProjects.vue';
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootswatch/dist/litera/bootstrap.min.css'; // Chemin vers le thème Litera

export default {
  name: 'App',
  components: {
    Navbar,
    HomePage,
    CardProjects,
  },
  
 
};

createApp(App).mount('#app');
</script>

<style>
  @import '@/assets/styles/main.css';
</style>
