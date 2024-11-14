<template>
  <div class="profile-container">
    <div class="profile">
      <div class="image">
        <a href="#">
          <img src="../assets/image-profile-ly.jpg" alt="image profile ly" />
        </a>
      </div>
      <div class="dst">
        <h3>Christ Ly</h3>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Harum magnam quam nesciunt
          corrupti explicabo? Nisi quia nostrum quaerat velit laborum placeat! Laboriosam molestias
          ad impedit sequi, dignissimos nam possimus corrupti.
        </p>
      </div>
    </div>
  </div>

  <!-- <div>
    <a :href="pdfPath" target="_blank" rel="noopener noreferrer">
      <button>Ouvrir le PDF</button>
    </a>
  </div> -->

  <div class="search">
    <form role="search">
      <input class="form-control" type="search" placeholder="Rechercher..." aria-label="Search" />
    </form>
    <button class="btn" type="submit">
      <img src="../assets/chercher.svg" alt="image de loop pour la recherche" />
    </button>
  </div>

  <!-- <div>
    <h2>Mon fichier PDF</h2>
    <iframe :src="pdfPath" width="25%" height="600px" style="border: none"
      ><img src="../assets/indesign.png" alt="Miniature PDF"
    /></iframe>
  </div> -->
</template>

<script>
// import { ref } from 'vue'
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Profile'

  // data() {
  //   return {
  //     // Chemin du fichier PDF
  //     pdfPath: '../assets/cahier-des-charges.pdf' // Chemin local dans les assets
  //   }
  // }
}

//  const searchQuery = ref('')

// const handleSearch = () => {

//   console.log('Recherche effectuée pour:', searchQuery.value)
// }
</script>

<style>
.profile-container {
  position: relative;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;

  animation-name: animateleft;
  animation-duration: 1.2s;
}
@keyframes animateleft {
  from {
    top: -300px;
    opacity: 0;
  }
  to {
    top: 0;
    opacity: 1;
  }
}

.profile {
  width: 400px;
  height: 300px;

  background: #1e001b;
  color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  box-shadow: 1px 1px 4px #1e001b;
  border-radius: 5px;
  /* transition-duration: 0.4; */
}

.profile:hover {
  border-left: 5px solid #ffffff;
  box-shadow: 3px 7px 8px #1e001b;
  width: 500px;
  height: 350px;
  transition: 500ms;
}

.profile img {
  height: 10rem;
  width: 10rem;
  margin: 30px;
}

.dst {
  border-left: 3px solid #ffffff;
  padding: 8px;
}

/* Bar de recherche */

.search {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 30px;
}

.form-control {
  width: 500px;
  height: 44px;
  background: rgba(255, 255, 255, 0.1);
  border: 2px solid #ffffff;
  border-radius: 25px 0 0 25px;
  padding: 13px;
  outline: none;
}
.search img {
  width: 29px;
  height: 29px;
  padding: 5px;
  /* border: none;
  margin-left: 5px;
  color: #f1f1f1; */

  border-radius: 0 25px 25px 0;
  /* background: #00a4a0; */
}
.search .btn {
  border: none;
  border-radius: 0 25px 25px 0;
  background: #ffffff;
}

/* 
.form-control {
  width: 500px;
  height: 44px;
  background: rgba(255, 255, 255, 0.1);
  border: 2px solid #ffffff;
  border-radius: 25px;
  padding: 13px;
  outline: none;
  padding-right: 40px; 
}

.search {
  display: flex;
  justify-content: center;
  margin: 30px;
}

.search .btn {
  border: none;
  padding: 10px; 
  margin-left: 5px;
  color: #f1f1f1;
  border-radius: 20px;
  background: #00a4a0;
  display: flex; 
  align-items: center; 
  justify-content: center; 
}

.search .btn i {
  position: absolute; 
  left: 10px; 
  top: 50%; 
  transform: translateY(-50%); 
}

 */
</style>
