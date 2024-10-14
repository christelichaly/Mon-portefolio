<template>
  <h2 class="Contact-title">Contact</h2>
  <div class="contact">
    <div class="contact_container">
      <form action="action_page.php">
        <label for="fname">Prénom</label>
        <input type="text" id="fname" name="firstname" placeholder="Votre prénom..." />

        <label for="lname">Nom :</label>
        <input type="text" id="lname" name="lastname" placeholder="Votre nom..." />

        <label for="objet"><b>Objet</b></label>
        <input type="text" placeholder="L'objet de votre email" name="objet" id="objet" required />

        <label for="subject">Message</label>
        <textarea
          id="subject"
          name="subject"
          placeholder="Votre message ici..."
          style="height: 200px"
        ></textarea>

        <input type="submit" value="Envoyer" />
      </form>
    </div>
    <div class="map">
      <a
        href="https://fr.mappy.com/activite/telephonie-installation#?bbox=2.3960591056734586%2C48.845093986515025%2C2.45685305508664%2C48.86988858353024"
        ><img src="../assets/map-adresse.png" alt="image map"
      /></a>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .contact {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
.Contact-title {
  height: 50px;
  text-align: center;
  align-content: center;
  background-color: #f1f1f1;
}
input[type='text'],
textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
  outline: none;
}
input[type='text']:hover,
textarea:hover {
  background-color: #2a5960;
  color: #fff;
}

input[type='submit'] {
  background-color: #00a4a0;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
input[type='submit']:hover {
  background-color: #295560;
}

.contact_container {
  width: 50%;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
.contact {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 50px;
}
.map img {
  width: 500px;
  height: 500px;
  border-radius: 5px;
}
</style>
