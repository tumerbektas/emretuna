<script setup>
</script>

<template>
  <div class="container">
  <div class="centered">
    <p class="classic-font">Emre Tuna</p>
    <p class="subtitle">Agricultural Engineer</p>
    <p class="description">
      My name is Emre, and I am currently a senior student pursuing a degree in Agricultural Engineering at Ege University. I have completed my compulsory internship in the R&D department of Abalıoğlu Feed Company. From a young age, I have been deeply interested in and curious about animals. I am committed to continuously developing myself professionally in this field.
    </p>
    <div class="social-links">
      <div class="links">
        <div class="link-group">
          <h3>CONNECT</h3>
          <a href="mailto:etuna2867@gmail.com" target="_blank">Gmail</a>
          <a href="https://www.linkedin.com/in/emre-tuna-48316b289?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank">Linkedin</a>
        </div>
        <div class="link-group">
          <h3>SOCIAL</h3>
          <a href="https://www.instagram.com/_emretuna_/" target="_blank">İnstagram</a>
          <a href="https://x.com/emretunna" target="_blank">X</a>
        </div>
      </div>
    </div>
  </div>
</div>
  <footer class="footer">
    © 2024 Emre Tuna
  </footer>
</template>

<style>
/* Global CSS */
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  background-color: #000000;
  color: #ffffff;
  font-family: 'Arial', sans-serif;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  position: relative; /* Ensures that footer positioning works */
}

.centered {
  transform: translateY(-5%);
}

.classic-font {
  font-size: 6rem;
  font-family: 'Rawen';
  color: #ffffff;
  margin: 0;
}

.subtitle {
  font-size: 2rem;
  color: #ffffff;
  font-family: 'BGrove';
  margin-top: 0.5rem;
}

.description {
  font-size: 1.5rem;
  color: #ffffff;
  margin-top: 1rem;
  margin-left: auto;
  margin-right: auto;
  font-family: 'BGrove';
  max-width: 90%;
  line-height: 1.5;
}

.social-links {
  margin-top: 3rem;
}

.links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
}

.link-group {
  text-align: center;
  font-family: 'Rawen';
}

.link-group h3 {
  font-size: 1.5rem;
  color: #ffffff;
  margin-bottom: 1.5rem;
}

.link-group a {
  display: block;
  color: #ffffff;
  text-decoration: none;
  margin-bottom: 0.5rem;
}

.link-group a:hover {
  color: #d0d0d0;
}

/* Footer styles */
/* Footer styles */
.footer {
  position: absolute;
  bottom: 1rem;
  left: 1rem;
  color: #ffffff;
  font-size: 0.9rem;
  font-weight: 300; /* Light font weight */
  font-family: 'Rawen'; /* Use a light-weight font if available */
}

/* Font definitions */
@font-face {
  font-family: 'BGrove';
  src: url('./assets/bgrove.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Rawen';
  src: url('./assets/RawengulkSans-094.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

/* Mobile styles */
@media (max-width: 768px) {
  body {
    padding: 1rem; /* Add padding to the body for mobile */
  }

  .classic-font {
    font-size: 4rem; /* Smaller font size for mobile */
  }

  .subtitle {
    font-size: 1.5rem; /* Smaller font size for mobile */
  }

  .description {
    font-size: 1.2rem; /* Smaller font size for mobile */
    max-width: 100%; /* Full width for better mobile readability */
  }

  .social-links {
    margin-top: 2rem; /* Adjust margin for mobile */
  }

  .links {
    gap: 1.5rem; /* Smaller gap for mobile */
  }

  .link-group h3 {
    font-size: 1.25rem; /* Smaller heading size for mobile */
  }
}
</style>
