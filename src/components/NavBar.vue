<template>
  <nav class="navbar bg-dark">
    <div class="container">
      <ul class="navbar-nav mr-auto">
        <!-- Rubriques principales avec marges droites -->
        <li class="nav-item">
          <a class="nav-link active" @click="scrollToPresentation">About me</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="/image/CV.pdf" target="_blank">My CV</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#">Experiences</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="mailto:maximebosse1@outlook.fr">Contact</a>
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
    }
  }
}
</script>


