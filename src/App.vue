<template>
  <div id="app">
    <Navbar />
    <HomePage/>,
    <CardProjects/>,
    <LoadingPage/>,

    <br>
    <p style="text-align:center;color:rgb(7, 140, 149);font-family: cursive;">"Avec de l'entraînement, même un raté peut devenir un génie." | Rock Lee</p>
    <br>
    <footer class="footer">
      <div class="container">
        <p>Copyright © 2024 by MLB Production</p>
      </div>
    </footer>


  </div>
</template>

<script>
import { createApp } from 'vue';
import App from './App.vue';
import HomePage from './components/HomePage.vue';
import Navbar from './components/NavBar.vue';
import CardProjects from './components/CardProjects.vue';
import LoadingPage from './components/LoadingPage.vue';
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootswatch/dist/litera/bootstrap.min.css'; // Chemin vers le thème Litera

export default {
  name: 'App',
  components: {
    Navbar,
    HomePage,
    CardProjects,
    LoadingPage
  },
  
 
};

createApp(App).mount('#app');
</script>

<style>
  @import '@/assets/styles/main.css';
</style>
