<template>
  <!-- <div class="mesCreations">
    <div v-for="(project, index) in projects" :key="index" class="project">
      <h3>{{ project.title }}</h3>
      <button @click="toggleModal(index)">Voir {{ project.title }}</button>

      <Modal :isOpen="project.isOpen" @close="closeModal(index)">
        <h2>{{ project.title }}</h2>

        
        <img :src="project.image" :alt="`Image de ${project.title}`" class="project-image" />

        
        <p>{{ project.description }}</p>

        
        <h4>Technologies utilisées :</h4>
        <ul>
          <li v-for="(tech, techIndex) in project.technologies" :key="techIndex">{{ tech }}</li>
        </ul>

        
        <a :href="project.link" target="_blank" rel="noopener noreferrer">Voir le projet</a>

        
        <div v-if="project.video">
          <h4>Vidéo de démonstration :</h4>
          <video controls>
            <source :src="project.video" type="video/mp4" />
            Votre navigateur ne supporte pas la vidéo.
          </video>
        </div>
      </Modal>
    </div>
  </div> -->
  <div class="title"><h1>Ok</h1></div>

  <!-- <div>
    
    <div class="project">
      <h3>Projet 1</h3>
      <button @click="showModal1 = true">Voir projet 1</button>

      <Modal :isOpen="showModal1" @close="showModal1 = false">
        <h2>Projet 1</h2>
        <p>Détails du projet 1...</p>
      </Modal>
    </div>

    
    <div class="project">
      <h3>Projet 2</h3>
      <button @click="showModal2 = true">Voir projet 2</button>

      <Modal :isOpen="showModal2" @close="showModal2 = false">
        <h2>Projet 2</h2>
        <p>Détails du projet 2...</p>
      </Modal>
    </div>

    
    <div class="project">
      <h3>Projet 3</h3>
      <button @click="showModal3 = true">Voir projet 3</button>

      <Modal :isOpen="showModal3" @close="showModal3 = false">
        <h2>Projet 3</h2>
        <p>Détails du projet 3...</p>
      </Modal>
    </div>
  </div> -->

  <!-- <div class="footer">
    <div class="social-link">
      <div class="link">
        <a href="https://github.com/christelichaly" target="_blank">
          <img src="../assets/github-ly.svg" alt="logo github ly.svg" />
        </a>
      </div>
      <div class="link">
        <a
          href="https://www.linkedin.com/feed/?trk=guest_homepage-basic_google-one-tap-submit"
          target="_blank"
        >
          <img src="../assets/linkedIn-ly.svg" alt="logo linkedIn ly" />
        </a>
      </div>
      <div class="link">
        <a href="https://www.instagram.com/sem/campaign/emailsignup/" target="_blank">
          <img src="../assets/instagram-ly.svg" alt="logo instagram ly" />
        </a>
      </div>
      <div class="link">
        <a href="https://x.com/?lang=fr" target="_blank">
          <img src="../assets/twitter-ly.svg" alt="logo twitter ly" />
        </a>
      </div>
    </div>
    <div class="maj">Dernière mise à jour du site le 19/09/2024</div>
  </div> -->
</template>

<script></script>

<!-- <script>
import Modal from './Modal.vue'

export default {
  components: {
    Modal
  },
  data() {
    return {
      showModal1: false, // État de la modale pour le projet 1
      showModal2: false, // État de la modale pour le projet 2
      showModal3: false // État de la modale pour le projet 3
    }
  }
}
</script> -->

<!-- <script>
import Contact from './components/ContactPage.vue'
export default {
  name: 'App',
  components: {
    Contact
  }
}
</script> -->

<style scoped>
/* .social-link {
  width: 150px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.footer {
  color: #f1f1f1;
  width: auto;
  height: 90px;
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: center;
  background-color: #1e001b;
  padding-left: 20%;
}
img {
  height: 25px;
  width: 25px;
} */
</style>
