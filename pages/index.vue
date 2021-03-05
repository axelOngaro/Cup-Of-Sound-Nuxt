<template>
  <div class="home-page">
    <h1>From thoughts</h1>
    <h1>to sound</h1>
    <p>
      Studio d'enregistrement, mixage et mastering, <br />à Toulouse, France.
    </p>
    <button>
      <nuxt-link class="nuxt-link" id="contactLink" to="contact"
        >me contacter
      </nuxt-link>
    </button>
  </div>
</template>

<script>
export default {
  components: {},
  transition: 'home',
}
</script>

<style scoped>
.home-page {
  min-height: 100vh;
  padding-top: 20vh;
}
h1,
p {
  margin-left: 8%;
}

p {
  font-size: 4rem;
  margin-top: 8vh;
}

h1 {
  line-height: 100%;
  font-weight: 400;
  font-size: 15rem;
}
button {
  margin-left: 20%;
  margin-top: 5vh;
  height: 100px;
  width: 400px;
  border: none;

  background-color: black;
  font-family: 'Jost';
  font-size: 3rem;
  border-radius: 50px;

  cursor: pointer;
}
button:hover {
  transition: 0.5s ease-in;
  transform: translate(-10px, -10px);
  box-shadow: grey 10px 10px 15px;
}

.nuxt-link {
  color: white;
}
</style>
