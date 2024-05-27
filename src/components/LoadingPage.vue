<template>
  <div class="loading-container" v-if="loading">
    <div class="loading-spinner">
      <div class="dot"></div>
      <div class="dot"></div>
      <div class="dot"></div>
    </div>
    <p style="font-size: 25px;">&nbsp;MLB Production</p>
  </div>
</template>

<script>
export default {
  name: 'LoadingPage',
  data() {
    return {
      loading: true
    };
  },
  mounted() {
    setTimeout(() => {
      this.loading = false; // Changez l'état du chargement après 3 secondes
    }, 3000); // Délai de 3 secondes (3000 millisecondes)
  }
};
</script>

<style>
.loading-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: linear-gradient( 117.5deg,  rgb(35 126 132) 20.5%, rgb(19, 91, 122) 100.2% );
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 9999;
}

.loading-spinner {
  display: flex;
  justify-content: center;
  align-items: center;
}

.dot {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background-color: #f3f3f3;
  margin: 0 5px;
  animation: bounce 0.5s alternate infinite ease-in-out;
}

@keyframes bounce {
  0% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(-20px);
  }
}
</style>
