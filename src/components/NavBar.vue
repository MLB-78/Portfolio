<template>
  <nav class="navbar bg-dark">
    <div class="container">
      <ul class="navbar-nav mr-auto">
        <!-- Rubriques principales avec marges droites -->
        <li class="nav-item">
          <button class="nav-link active" @click="scrollToPresentation" style="color: rgb(35 126 132);">About me</button>
        </li>
        <li class="nav-item">
          <a href="image/CV.pdf" >
            <button class="nav-link active" target="_blank" style="color: rgb(35 126 132);">My CV</button>
          </a>
        </li>
        <li class="nav-item">
          <button class="nav-link active" @click="scrollToProjets" href="#" style="color: rgb(35 126 132);">Projects</button>
        </li>
        <li class="nav-item">
          <button class="nav-link active" href="mailto:maximebosse1@outlook.fr" style="color: rgb(35 126 132);">Contact</button>
        </li>
        <!-- Logos LinkedIn et GitHub -->
        <li class="nav-item logo-item">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="https://www.linkedin.com/in/mlb-njo/" target="_blank">
                <img src="image/lk.png" alt="LinkedIn Logo" style="height: 30px;">
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://github.com/MLB-78" target="_blank">
                <img src="image/git.png" alt="GitHub Logo" style="height: 30px;">
              </a>
            </li>
          </ul>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  methods: {
    scrollToPresentation() {
      const presentationSection = document.getElementById('presentation');
      if (presentationSection) {
        window.scrollTo({
          top: presentationSection.offsetTop,
          behavior: 'smooth'
        });
      }
    },
    scrollToProjets() {
      const projetsSection = document.getElementById('projets');
      if (projetsSection) {
        window.scrollTo({
          top: projetsSection.offsetTop,
          behavior: 'smooth'
        });
      }
    }
  }
}
</script>


