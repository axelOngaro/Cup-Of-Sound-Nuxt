<template>
  <div class="home-page">
    <h1>From thoughts</h1>
    <h1>to sound</h1>
    <p>
      Studio d'enregistrement, mixage et mastering, <br />à Toulouse, France.
    </p>
  </div>
</template>

<script>
import gsap from 'gsap'
export default {
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
  font-family: 'Almarena';
}

.nuxt-link {
  color: white;
}
</style>
