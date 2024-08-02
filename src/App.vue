<template>
  <div class="container">
    <div class="centered">
      <p class="classic-font">EMRE TUNA</p>
      <p class="subtitle">Agricultural Engineer</p>
      <p class="description">
        My name is Emre, and I am currently a senior student pursuing a degree in Agricultural Engineering at Ege University. I have completed my compulsory internship in the R&D department of Abalioglu Feed Company. From a young age, I have been deeply interested in and curious about animals. I am committed to continuously developing myself professionally in this field.
      </p>
      <div class="social-links">
        <div class="links">
          <div class="link-group">
            <h3>CONNECT</h3>
            <a href="mailto:etuna2867@gmail.com" target="_blank">Mail</a>
            <a href="https://www.linkedin.com/in/emre-tuna-48316b289?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank">LinkedIn</a>
          </div>
          <div class="link-group">
            <h3>SOCIAL</h3>
            <a href="https://www.instagram.com/_emretuna_/" target="_blank">Instagram</a>
            <a href="https://x.com/emretunna" target="_blank">X</a>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <p>© 2024 Emre Tuna</p>
    </div>
  </div>
</template>

<style>
/* Global CSS */
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  background-color: #909090;
  color: #000000;
  font-family: 'Arial', sans-serif;
}

.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  justify-content: center;
  align-items: center;
}

.centered {
  text-align: center;
  padding-bottom: 4rem; /* Ensure space for the footer */
}

.footer {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  font-family: 'BGrove';
  font-size: 1rem;
  color: #000000;
  text-align: center;
  padding: 0.5rem;
  background-color: #ffffff; /* Add a background color if needed */
}

/* Responsive Design */
@media (max-width: 768px) {
  .classic-font {
    font-size: 4rem;
  }

  .subtitle {
    font-size: 1.5rem;
  }

  .description {
    font-size: 1.2rem;
  }

  .links {
    flex-direction: column;
    gap: 2rem;
  }

  .link-group h3 {
    font-size: 1.2rem;
  }

  .footer {
    font-size: 0.9rem;
  }
}

@media (max-width: 480px) {
  .classic-font {
    font-size: 3rem;
  }

  .subtitle {
    font-size: 1.2rem;
  }

  .description {
    font-size: 1rem;
    padding: 0 1rem;
  }

  .links {
    flex-direction: column;
    gap: 1.5rem;
  }

  .link-group h3 {
    font-size: 1rem;
  }

  .footer {
    font-size: 0.8rem;
  }
}

/* Font definitions */
@font-face {
  font-family: 'BGrove';
  src: url('./assets/bgrove.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'LiberationSans';
  src: url('./assets/LiberationSans-Bold.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Forta';
  src: url('./assets/Forta.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Rawen';
  src: url('./assets/RawengulkSans-094.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}
</style>
