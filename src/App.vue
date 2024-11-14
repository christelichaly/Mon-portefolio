<template>
  <div id="app">
    <header>
      <a href="#"
        ><div class="logo">
          <img src="./assets/image-profile-ly.jpg" alt="image profile ly" /></div
      ></a>

      <nav class="navbar">
        <RouterLink to="/">Portefolio</RouterLink>
        <RouterLink to="#creations">Creations </RouterLink>
        <RouterLink to="#apropos">À Propos </RouterLink>
        <RouterLink to="#contact">Contact </RouterLink>
        <!-- <a href="#creations">Creations</a>
        <a href="#apropos">À Propos</a>
        <a href="#contact">Contact</a> -->
        <!-- 
        <RouterLink to="/#creations">Creations</RouterLink>
        <RouterLink to="/Apropos">À Propos</RouterLink>
        <RouterLink to="/Contact">Contact</RouterLink> -->
      </nav>
    </header>

    <!-- <div class="creations"><TheCreations /><TheCreations /><TheCreations /></div> -->

    <RouterView />

    <!-- <section id="lien">
      <div>
        <h1>Utilisation de liens d'encrage</h1>
        <p>Vérifier l'utilisation des liens d'encrage</p>
      </div>
    </section> -->
    <!-- footer /> -->
    <div class="footer">
      <div class="footer-content">
        <div class="social-link">
          <div class="link">
            <a href="https://github.com/christelichaly" target="_blank">
              <img src="./assets/github-ly.svg" alt="logo github ly.svg" />
            </a>
          </div>
          <div class="link">
            <a
              href="https://www.linkedin.com/feed/?trk=guest_homepage-basic_google-one-tap-submit"
              target="_blank"
            >
              <img src="./assets/linkedIn-ly.svg" alt="logo linkedIn ly" />
            </a>
          </div>
          <div class="link">
            <a href="https://www.instagram.com/sem/campaign/emailsignup/" target="_blank">
              <img src="./assets/instagram-ly.svg" alt="logo instagram ly" />
            </a>
          </div>
          <div class="link">
            <a href="https://x.com/?lang=fr" target="_blank">
              <img src="./assets/twitter.png" alt="logo twitter ly" />
            </a>
          </div>
        </div>
        <div class="maj">
          <time datetime="2024-10-11">Dernière mise à jour du site le 11 octobre 2024 </time>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
// import { onMounted, onUnmounted } from 'vue'

//onMounted(() => {
// const header = document.querySelector('header')
// const stickyScrollPoint = 200 // Point de défilement (en pixels) pour rendre le header fixe

// const handleScroll = () => {
//   if (header) {
// Vérification pour s'assurer que 'header' n'est pas null
//       if (window.scrollY > stickyScrollPoint) {
//         header.classList.add('header-fixed')
//       } else {
//         header.classList.remove('header-fixed')
//       }
//     }
//   }

//   window.addEventListener('scroll', handleScroll)

//   onUnmounted(() => {
//     window.removeEventListener('scroll', handleScroll)
//   })
// })
</script>

<style scoped>
@media (min-width: 1024px) {
  .app {
    min-height: 100vh;
    display: flex;
  }
}

html {
  scroll-behavior: smooth;
}

/* Le fond du site */
#app {
  background-image: url('./assets/background-portefolio-christ-ly.jpg');
  background-repeat: no-repeat;
  width: auto;
  height: auto;
  padding-top: 170px;
}

/* Header */
header {
  width: 100%;
  height: 80px;
  position: fixed; /* Rend le header fixe */
  top: 0; /* Positionne le header en haut de la page */
  left: 0; /* Alignement à gauche */
  z-index: 1000; /* Assure que le header reste au-dessus des autres éléments */
  align-items: center;
  display: flex;
  color: #ffffff;
  justify-content: space-between;
  background: #295560;
  padding: 20px;
  margin-bottom: 20px;
  transition: all 0.3s;
}

/* .header-fixed {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1000;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2); 
} */

.logo img {
  height: 5rem;
  width: 5rem;
  border-radius: 50%;
}
.logo img:hover {
  border: 3px solid #f1f1f1;
  box-shadow: 0 3px 7px 3px #1e001b;
  transition: 0.3s;
}

.navbar {
  width: auto;
  display: flex;
  flex-direction: row;
  justify-content: center;
  justify-content: space-between;
  font: 13px;
  margin-right: 120px;
  margin-left: 10px;
}
a {
  display: flex;
  text-decoration: none;
  color: #ffffff;
  font: 13px;
  padding: 15px;
}

.navbar a:hover {
  background-color: #1e001b;
  font-size: 18px;
  transition: 0.4s;
}
.navbar a:focus {
  border-bottom: 3px solid #f1f1f1;
}

/* main */

/* Les créations */
.creations {
  display: flex;
}

/* footer */

.footer {
  color: #f1f1f1;
  width: auto;
  height: 90px;
  display: flex;
  /* flex-direction: column; */
  background-color: #1e001b;
  /* align-content: center;
  justify-content: center; */

  /* padding-left: 20%; */
  /* margin-top: 20px; */
}
.social-link {
  /* width: 150px; */
  display: flex;
  justify-content: center;
}

.footer-content {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.footer img {
  height: 25px;
  width: 25px;
}

.maj {
  display: flex;
  justify-content: center;
}

/* header {
  line-height: 1.5;
  max-height: 100vh;
} */

/* nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1440px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  } */

/* nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  } */
</style>
