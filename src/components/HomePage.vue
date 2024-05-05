<template>
<v-container fluid>
  <div class="head">
    <v-row id="zua">  
      <v-col cols="5">
        <div style="position:relative" class="mt-16">
          <h1 class="hOne" style="color: #c4c4c4;">Hello,</h1>
          <h1 class="hOne">I'm Maxime Njo</h1>
          <h1 class="hOne" style="color: #c4c4c4;">Web Developer & Integrator</h1>
          <a href="mailto:maximebosse1@outlook.fr">
            <button type="button" class="btn btn-outline-warning">Contact me</button>
          </a>
        </div>
        &nbsp; &nbsp; &nbsp;
      </v-col>
      <v-col cols="5" >
        <div style="position:relative;z-index: 999;" class="mt-16">
          <v-icon>
            <img src="image/me.png" >
          </v-icon>
        </div>
      </v-col>
    </v-row>
  </div> 
</v-container>
<br><br>
<main style="color: black;">
  <h3 style="text-align: center;color: rgb(35, 126, 132);" id="presentation">About me</h3>
  <br><br>
  <div class="presentation" >
    <p style="color: rgb(35, 126, 132);">
      As a web development student in a BTS SIO 
      program, I'm 20 years old and about to start 
      my third year at ETNA, combining work and study.
      I'm deeply passionate about crafting innovative
      websites, and my academic journey has been
      instrumental in honing my programming skills
      and project management abilities. My portfolio
      showcases my creativity and attention to detail
      through concrete projects.
    </p>
  </div>
    <br><br>
    <h3 style="text-align: center;color: rgb(35, 126, 132);">My latest projects</h3>
    <div class="zolamba" id="projets">

    </div>
</main>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

