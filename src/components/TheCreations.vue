<template>
  <h1>Mes créations</h1>
  <div class="mesCreatons">
    <!-- Projet 1 -->
    <button @click="showModal1 = true" class="btn">
      <a href="#"
        ><div class="CV">
          <img class="img-cv" src="../assets/modele-cv-minimaliste.svg" alt=" image cv ly" />
          <h2>Curriculum Vitae</h2>
        </div></a
      >
    </button>
    <Modal class="modal" :isOpen="showModal1" @close="showModal1 = false">
      <div class="header">
        <div class="title"><h1>Mon Curriculum Vitae</h1></div>
      </div>

      <div class="body">
        <div class="main">
          <span
            >Créé le <time datetime="2024-02-05"> 05 Février 2024 </time> sur
            <a href="https://code.visualstudio.com/" target="_blank">VS Code.</a></span
          >

          <p>
            Mon tout premier devoir réalisé en cours, la création de mon CV. <br />
            Il est accessible sur mon compte GitHub en cliquant <br />
            sur l'image ci-contre ou avec le lien tout en bas de la modale. <br />
            Les technologies utilisées pour la création sont les suivantes : <br />
            <span
              ><a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
                HTML</a
              ></span
            >
            et
            <span
              ><a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
                CSS</a
              ></span
            >
          </p>
          <div class="social-link">
            <div class="link">
              <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
                <img src="../assets/logo-html-ly.png" alt="logo et lien html" />
              </a>
            </div>
            <div class="link">
              <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
                <img src="../assets/logo-css-ly.png" alt="logo et lien css" />
              </a>
            </div>
          </div>
        </div>
        <div class="image-cv">
          <a href="https://github.com/christelichaly/Projet_CV" target="_blank"
            ><img src="../assets/modele-cv-minimaliste.svg" alt="l'image du cv"
          /></a>
        </div>
      </div>

      <div class="footer">
        <a href="https://github.com/christelichaly/Projet_CV" target="_blank"
          ><h3>Accéder au repository Github du cv</h3></a
        >
      </div>
    </Modal>

    <!-- Projet 2 -->
    <button @click="showModal2 = true" class="btn">
      <a href="#"
        ><div class="CV">
          <img
            class="img-cv"
            src="../assets/cahier-des-charges-ly.jpg"
            alt=" image cahier des charges"
          />
          <h2>Cahier des charges</h2>
        </div></a
      >
    </button>
    <Modal :isOpen="showModal2" @close="showModal2 = false">
      <div class="header">
        <div class="title"><h1>Cahier des charges</h1></div>
      </div>

      <div class="body">
        <div class="main">
          <span
            >Créé le <time datetime="2024-02-05"> 05 Février 2024 </time> sur
            <a
              href="https://www.adobe.com/products/indesign/campaign/pricing.html?gclid=Cj0KCQjw6oi4BhD1ARIsAL6pox0Ulw2JLfoRGyDLMA7e-TrxLHMLr8BSKxu_LJuW7KG1Vcaw572UlnAaAhqMEALw_wcB&sdid=YSYYFYJB&mv=search&mv2=paidsearch&ef_id=Cj0KCQjw6oi4BhD1ARIsAL6pox0Ulw2JLfoRGyDLMA7e-TrxLHMLr8BSKxu_LJuW7KG1Vcaw572UlnAaAhqMEALw_wcB:G:s&s_kwcid=AL!3085!3!356469619192!e!!g!!indesign!1711729601!70905759790&mv=search&gad_source=1"
              target="_blank"
              >InDesign.</a
            ></span
          >

          <p>
            Le deuxième devoir que j'ai réalisé est un cahier des charges, <br />
            en tant qu'entreprise fictive. Le PDF est accessible en cliquant <br />
            sur l'image ci-contre ou avec le lien tout en bas de la modale. <br />
            Les technologie utilisées pour la création sont les suivantes : <br />
            <span
              ><a
                href="https://www.adobe.com/products/indesign/campaign/pricing.html?gclid=Cj0KCQjw6oi4BhD1ARIsAL6pox0Ulw2JLfoRGyDLMA7e-TrxLHMLr8BSKxu_LJuW7KG1Vcaw572UlnAaAhqMEALw_wcB&sdid=YSYYFYJB&mv=search&mv2=paidsearch&ef_id=Cj0KCQjw6oi4BhD1ARIsAL6pox0Ulw2JLfoRGyDLMA7e-TrxLHMLr8BSKxu_LJuW7KG1Vcaw572UlnAaAhqMEALw_wcB:G:s&s_kwcid=AL!3085!3!356469619192!e!!g!!indesign!1711729601!70905759790&mv=search&gad_source=1"
                target="_blank"
              >
                Adobe Indesign</a
              ></span
            >et
            <span><a href="https://www.figma.com/login" target="_blank"> Figma</a></span>
          </p>
          <div class="social-link">
            <div class="link">
              <a
                href="https://www.adobe.com/products/indesign/campaign/pricing.html?gclid=Cj0KCQjw6oi4BhD1ARIsAL6pox0Ulw2JLfoRGyDLMA7e-TrxLHMLr8BSKxu_LJuW7KG1Vcaw572UlnAaAhqMEALw_wcB&sdid=YSYYFYJB&mv=search&mv2=paidsearch&ef_id=Cj0KCQjw6oi4BhD1ARIsAL6pox0Ulw2JLfoRGyDLMA7e-TrxLHMLr8BSKxu_LJuW7KG1Vcaw572UlnAaAhqMEALw_wcB:G:s&s_kwcid=AL!3085!3!356469619192!e!!g!!indesign!1711729601!70905759790&mv=search&gad_source=1"
                target="_blank"
              >
                <img src="../assets/indesign.png" alt="logo et lien indesign" />
              </a>
            </div>
            <div class="link">
              <a href="https://www.figma.com/login" target="_blank">
                <img src="../assets/figma.png" alt="logo et lien figma" />
              </a>
            </div>
          </div>
        </div>

        <div class="image-cv">
          <a :href="pdfPath" target="_blank">
            <img src="../assets/miniature-cahier-des-charges.png" alt="l'image du cv"
          /></a>
        </div>
      </div>

      <div class="footer">
        <a :href="pdfPath" target="_blank"><h3>Ouvrir le cahier des charges</h3></a>
      </div>
    </Modal>

    <!-- Projet 3 -->
    <button @click="showModal3 = true" class="btn">
      <a href="#"
        ><div class="CV">
          <img
            class="img-cv"
            src="../assets/espace-commentaire-ly.svg"
            alt="la miniature du cv ly"
          />
          <h2>Espace commentaire Dynamique</h2>
        </div></a
      >
    </button>
    <Modal :isOpen="showModal3" @close="showModal3 = false">
      <div class="header">
        <div class="title"><h1>Espace commentaire Dynamique</h1></div>
      </div>

      <div class="body">
        <div class="main">
          <span
            >Créé le <time datetime="2024-05-19"> 19 avril 2024 </time> sur
            <a href="https://code.visualstudio.com/" target="_blank">VS Code.</a></span
          >

          <p>
            Mon troisième devoir réalisé en découvrant
            <span
              ><a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
                JavaScript</a
              ></span
            >, dynamiser un espace commentaire. <br />
            Il est accessible sur mon compte GitHub en cliquant <br />
            sur l'image ci-contre ou avec le lien tout en bas de la modale. <br />
            La technologie utilisée pour la réalisation est :
            <span
              ><a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
                JavaScript</a
              ></span
            >
          </p>
          <div class="social-link">
            <div class="link">
              <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank">
                <img src="../assets/javascript.png" alt="logo et lien javascript" />
              </a>
            </div>
          </div>
        </div>
        <div class="image-cv">
          <a href="https://github.com/christelichaly/Espace-commentaire-" target="_blank"
            ><img src="../assets/espace-commentaire-ly.svg" alt="la miniature du cv"
          /></a>
        </div>
      </div>

      <div class="footer">
        <a href="https://github.com/christelichaly/Espace-commentaire-" target="_blank"
          ><h3>Accéder au repository Github</h3></a
        >
      </div>
    </Modal>
  </div>
</template>

<!-- <div class="mesCreations">
    <div v-for="(project, index) in projects" :key="index" class="project">
      <h3>{{ project.title }}</h3>
      <button @click="toggleModal(index)">Voir {{ project.title }}</button>

      <Modal :isOpen="project.isOpen" @close="closeModal(index)">
        <h2>{{ project.title }}</h2>

         Image du projet
        <img :src="project.image" :alt="`Image de ${project.title}`" class="project-image" />

         Description complète
        <p>{{ project.description }}</p>

         Technologies utilisées
        <h4>Technologies utilisées :</h4>
        <ul>
          <li v-for="(tech, techIndex) in project.technologies" :key="techIndex">{{ tech }}</li>
        </ul>

        Lien vers le projet ou le repo GitHub
        <a :href="project.link" target="_blank" rel="noopener noreferrer">Voir le projet</a>

        Optionnel : vidéo du projet
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

<!-- <div class="my-creation">
    <button v-on:click="toggleModale" class="btn">
      <a href="#"
        ><div class="CV">
          <img class="img-cv" src="../assets/modele-cv-minimaliste.svg" alt=" image cv ly" />
          <h2>Curriculum Vitae</h2>
        </div></a
      >
    </button>

    <div class="modal" v-if="revele" v-on:click="toggleModale">
      <div class="modal-content" v-on:click="toggleModale">
        <div class="header">
          <div class="close" v-if="revele" v-on:click="toggleModale">&times;</div>
          <div class="title"><h1>Mon Curriculum Vitae</h1></div>
        </div>

        <div class="body">
          <div class="main">
            <span
              >Créé le <time datetime="2024-02-05"> 05 Février 2024 </time> sur
              <a href="https://code.visualstudio.com/" target="_blank">VS Code.</a></span
            >

            <p>
              Les technologies utilisées pour la création sont les suivantes : <br />
              <span
                ><a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
                  HTML</a
                ></span
              >
              et
              <span
                ><a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
                  CSS</a
                ></span
              >
            </p>
            <div class="social-link">
              <div class="link">
                <a href="https://developer.mozilla.org/fr/docs/Web/HTML" target="_blank">
                  <img src="../assets/logo-html-ly.png" alt="logo et lien html" />
                </a>
              </div>
              <div class="link">
                <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank">
                  <img src="../assets/logo-css-ly.png" alt="logo et lien css" />
                </a>
              </div>
            </div>
          </div>
          <div class="image-cv">
            <a href="https://github.com/christelichaly/Projet_CV" target="_blank"
              ><img src="../assets/modele-cv-minimaliste.svg" alt="l'image du cv"
            /></a>
          </div>
        </div>

        <div class="footer">
          <a href="https://github.com/christelichaly/Projet_CV" target="_blank"
            ><h3>Accéder au repository Github du cv</h3></a
          >
        </div>
      </div>
    </div>

    <a href="#"
      ><div class="CDC">
        <img
          class="img-cdc"
          src="../assets/cahier-des-charges-ly.jpg"
          alt="imge cahier des charges ly"
        />
        <h2>Cahier des charges</h2>
      </div></a
    >

    <a href="#"
      ><div class="E-C">
        <img
          class="img-ec"
          src="../assets/espace-commentaire-ly.svg"
          alt=" image espace commentaire ly"
        />
        <h2>Espace commentaire</h2>
      </div></a
    >
  </div> -->

<script>
import Modal from './ModalView.vue'
// import VuePdfEmbed from 'vue-pdf-embed'

export default {
  components: {
    Modal
    // VuePdfEmbed
  },

  data() {
    return {
      showModal1: false, // État de la modale pour le projet 1
      showModal2: false, // État de la modale pour le projet 2
      showModal3: false, // État de la modale pour le projet 3
      pdfPath: '/cahier-des-charges.pdf' // Chemin vers le fichier PDF
    }
  }

  // methods: {
  //   openModal(modalNumber) {
  //     this[`showModal${modalNumber}`] = true
  //   },
  //   closeModal(modalNumber) {
  //     this[`showModal${modalNumber}`] = false
  //   }
  // }
}
</script>

<!-- <script>
import Modal from './Modal.vue'

export default {
  components: {
    Modal
  },
  data() {
    return {
              Un tableau d'objets représentant chaque projet, avec isOpen défini dès le départ
      projects: [
        {
          title: 'Projet 1',
          description: 'Ceci est une description complète du projet 1...',
          image: 'https://via.placeholder.com/300',
          technologies: ['Vue.js', 'Node.js', 'MongoDB'],
          link: 'https://github.com/monrepo/projet1',
          video: 'https://www.exemple.com/video1.mp4',
          isOpen: false      Chaque projet a la propriété isOpen
        },
        {
          title: 'Projet 2',
          description: 'Description du projet 2...',
          image: 'https://via.placeholder.com/300',
          technologies: ['React', 'Express', 'MySQL'],
          link: 'https://github.com/monrepo/projet2',
          video: '',
          isOpen: false     Toujours initialiser isOpen
        },
        {
          title: 'Projet 3',
          description: 'Description du projet 3...',
          image: 'modele-cv-minimaliste.svg',
          technologies: ['Angular', 'Firebase'],
          link: 'https://github.com/monrepo/projet3',
          video: 'https://www.exemple.com/video3.mp4',
          isOpen: false       Initialiser isOpen
        }
      ]
    }
  },
  methods: {
    getImage(imageName) {
       Utilise require()      pour charger l'image locale dynamiquement
      return require(`@/assets/${imageName}`)
    },
    toggleModal(index) {
      this.projects[index].isOpen = true
    },
    closeModal(index) {
      this.projects[index].isOpen = false
    }
  }
}

</script> -->
<!-- <script>
  export default {
name: 'Modale',
props: ['revele', 'toggleModale']
 }
</script> -->

<style scoped>
/* ------------CSS Modale dynamique---------------*/
/* .project {
  width: 300px;
  height: 300px;
  background: #f1f1f1;
  justify-content: center;
}
.project-image {
  width: 50%;
  height: auto;
  margin-bottom: 15px;
}
button {
  background: #002e39;
}
.mesCreations {
  width: 1024px;
  display: flex;
  justify-content: space-evenly;
  padding-left: 15%;
}
.project-title {
  background: #9a1414;
} */

/* -----------------------------------------------------*/
a {
  text-decoration: none;
  color: #1e001b;
}
.CV,
.CDC,
.E-C {
  align-content: center;
  text-align: center;
  width: 300px;
  height: 300px;
  margin: 50px;
  padding: 20px;
  border: 3px solid #ffffff;
  background: #002e39;
  color: #ffffff;
  /* opacity: 50%; */
}
.img-cdc,
.img-cv,
.img-ec {
  width: 200px;
  height: 200px;
}

/* .creas {
  width: 150px;
  height: 150px;
} */

h1 {
  text-align: center;
  color: #f1f1f1;
}

.mesCreatons {
  display: flex;
  justify-content: center;
}

.CV:hover,
.CDC:hover,
.E-C:hover {
  background: #ffffff;
  color: #1e001b;
  box-shadow: 3px 7px 8px #1e001b;
  transition: 0.55s;
  /* opacity: 100%; */
}

/* CSS Modale */

/* CV */

/* Le header */
.header {
  height: 70px;
  width: auto;
  align-content: center;
  background: #1e001b;
  color: #f1f1f1;
  margin-bottom: 10px;
}
.header {
  display: flex;
  justify-content: center;
}

.header h1:hover {
  opacity: 0.7;
}
.body {
  display: flex;
  align-items: center;
  margin-left: 50px;
}
/* Le contenu principal */
.body span {
  font-weight: bold;
}
span a {
  color: #00a4a0;
}

span a:hover {
  color: #3dd1f6;
}

/* .body span:hover {
  border-left: 3px solid #1e001b;
  padding-left: 5px;
} */

.main {
  padding-right: 50px;
}
.image-cv img {
  opacity: 1;
  width: 150px;
  height: 300px;
  /* border: 1px solid #002e39; */
}
.image-cv img:hover {
  opacity: 0.7;
}

/* .modal p:hover {
  border-left: 3px solid #1e001b;
  padding-left: 5px;
} */

.social-link {
  width: 80px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 10px;
}
img {
  height: 25px;
  width: 25px;
}

/* Le footer */
.footer {
  height: 70px;
  width: 100%;
  justify-content: center;
  align-content: center;
  background: #1e001b;
  color: #f1f1f1;
  margin-top: 13px;
}
.footer a {
  color: #f1f1f1;
}
.footer a {
  display: flex;
  justify-content: center;
}
.footer a:hover {
  opacity: 0.7;
}

/* La modale */
.modal {
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: 100%;
  background-color: rgb(0, 0, 0);
  background-color: rgba(0, 0, 0, 0.4);
}

/* Le Contenu de la modale/Box */
.modal-content {
  position: relative;
  background-color: #fefefe;
  margin: 15px auto;
  padding: 15;
  border: 1px solid #888;
  width: 65%;
  height: 60%;
  -webkit-animation-name: animatetop;
  -webkit-animation-duration: 0.7s;
  animation-name: animatetop;
  animation-duration: 0.7s;
}

/* Animation */
@-webkit-keyframes animatetop {
  from {
    top: -500px;
    opacity: 0;
  }
  to {
    top: 0;
    opacity: 1;
  }
}

@keyframes animatetop {
  from {
    top: -500px;
    opacity: 0;
  }
  to {
    top: 0;
    opacity: 1;
  }
}

/* Le Button de fermeture */
.close {
  text-align: center;
  width: 25px;
  height: 25px;
  padding: 0 6px 10px 6px;
  background: #f1f1f1;
  color: #e30707;
  float: right;
  font-size: 28px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: black;
  text-decoration: none;
  cursor: pointer;
}
</style>
