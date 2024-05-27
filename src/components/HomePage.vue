<template>

  <div class="head">
    <v-row id="zua">  
      <v-col cols="5">
        <div style="position:relative" class="mt-16">
          <h1 class="hOne" style="color: #c4c4c4;">Bonjour,</h1>
          <h1 class="hOne">Maxime Njo</h1>
          <h1 class="hOne" style="color: #c4c4c4;">Développeur Web</h1>
          <br>
          <a href="mailto:maximebosse1@outlook.fr" class="bukateh">Contact me</a>
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
<br><br>
<main style="color: black;">
  <h3 style="text-align: center;color: rgb(7, 140, 149);" id="presentation">À propos de moi</h3>
  <br><br>
  <div class="presentation" >
    <p style="color: rgb(7, 140, 149);">
       Je m'appelle Maxime Njo, j'ai 20 ans et je suis sur le point de commencer ma troisième année à l'ETNA, je suis à la recherche d'une alternance pour effectuer mon bachelor concepteur développeur d'application.
       Je suis profondément passionné par le développement web, et mon parcours académique a été déterminant pour perfectionner mes compétences en programmation. Mon portfolio
       met en valeur ma créativité et mon souci du détail
       à travers des projets concrets.
    </p>
  </div>
    <br><br>
    <h3 style="text-align: center;color: rgb(7, 140, 149);">Mes dernières réalisation</h3>
    <div class="zolamba" id="projets">

    </div>
</main>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

