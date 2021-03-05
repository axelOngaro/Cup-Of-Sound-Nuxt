<template>
  <div class="contact">
    <div class="contact-text">
      <h2>Contact.</h2>

      <p>
        N’hésite pas à me contacter pour plus de renseignement, ou simplement
        passer un bonjour!
      </p>
    </div>
    <div class="contact-content">
      <p>Via mes réseaux:</p>
      <ul>
        <li><a href="">facebook</a></li>
        <li><a href="#">Instagram</a></li>
        <li><a href="#">Soundcloud</a></li>
        <li><a href="#">Youtube</a></li>
      </ul>
      <p>Ou directement par email à: <a href="#">machin.truc@email.fr</a></p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'contact',
  transition: 'home',
}
</script>
<style scoped>
.contact {
  height: 100vh;
  display: flex;
  padding: 0 10%;

  padding-top: 20vh;
  justify-content: space-evenly;
}
.contact-text {
  width: 50%;
}
.contact-text h2 {
  margin-bottom: 8vh;
  font-size: 4rem;
}
.contact-text p {
  font-size: 3rem;
  width: 80%;
}

.contact-content {
  width: 50%;
  font-size: 2rem;
}
.contact-content a {
  text-decoration: none;
  color: black;
}
.contact-content p {
  padding: 5vh 0;
}
.contact-content li {
  padding: 1vh 0;
}
</style>
