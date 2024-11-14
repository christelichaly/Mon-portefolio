<template>
  <div class="about">
    <div class="title">
      <h1>À Propos de moi</h1>
    </div>
    <div class="description">
      <h2>Ly Christ Elicha</h2>
      <h3>développeur web junior</h3>
      <div class="contenu">
        <p>
          Lorem ipsum dolor sit amet consectetur
          <span><a href="https://github.com/christelichaly" target="_blank">GitHub</a></span>
          adipisicing elit. Suscipit perferendis id, iste explicabo error obcaecati soluta
          laboriosam minus! Ipsa sed doloremque quod provident temporibus accusamus aspernatur culpa
          quasi veritatis nam.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe facere sint officia
          inventore minus
          <span
            ><a
              href="https://www.linkedin.com/feed/?trk=guest_homepage-basic_google-one-tap-submit"
              target="_blank"
              >Linkedin</a
            ></span
          >
          pariatur repellat reiciendis quisquam? Repellendus illum mollitia tempore reprehenderit
          totam temporibus at cumque reiciendis aliquam perspiciatis.
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum doloribus ipsam quis saepe
          dolorem, inventore aliquam deserunt reprehenderit molestiae doloremque ad eligendi culpa
          fugiat, dolores, aliquid tempore earum eveniet nemo.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
}

.about {
  align-items: center;
  color: #f1f1f1;
  margin-top: 90px;
}
.title {
  color: #1e001b;
}
.description {
  width: 600px;
  height: 500px;
  background-color: #f1f1f1;
  /* box-shadow: 3px 3px 7px 3px #1e001b; */
}
h2 {
  background-color: #1e001b;
  border: 1px solid #f1f1f1;
  border-radius: 25px;
}
h2,
h3,
.contenu {
  padding: 5px 20px;
}
h3,
.contenu {
  color: #1e001b;
}

span a {
  font-weight: bold;
  text-decoration: none;
  color: #00a4a0;
}
span a:hover {
  color: #3dd1f6;
}
p {
  padding-left: 5px;
}
p:hover {
  border-left: 3px solid #1e001b;
}
</style>
