<template>
  <div class="contact">
    <div class="contact-text">
      <h2>Contact</h2>

      <p>
        N’hésite pas à me contacter pour plus de renseignement, ou simplement
        passer un bonjour!
      </p>
    </div>
    <div class="contact-content">
      <p>Via mes réseaux:</p>
      <ul>
        <li>
          <a href="#" class="contact-link">Facebook</a>
        </li>
        <li>
          <a href="#" class="contact-link">Instagram</a>
        </li>
        <li>
          <a href="#" class="contact-link">Soundcloud</a>
        </li>
        <li><a href="#" class="contact-link">Youtube</a></li>
      </ul>
    </div>
    <p class="email">
      <a href="#" class="contact-link">machin.truc@email.fr</a>
    </p>
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
  flex-wrap: wrap;
  padding: 0 10%;

  padding-top: 10vh;
  justify-content: space-evenly;
}
.contact-text {
  width: 50%;
}
.contact-text h2 {
  margin-bottom: 8vh;
  font-size: 8rem;
}
.contact-text p {
  font-size: 5rem;
  width: 80%;
}

.contact-content {
  width: 50%;
  font-size: 3rem;
  display: flex;
  flex-direction: column;
  padding-left: 15%;
  margin-top: 10%;
}

.contact-content p {
  padding: 5vh 0;
}
.contact-content li {
  padding: 1vh 0;
}
.email {
  font-size: 4rem;
  font-weight: bold;
}
.contact-link {
  position: relative;
}
.contact-link::after {
  content: '';
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 2px;
  background-color: currentColor;

  transform: scaleX(0);
  transform-origin: right;
  transition: transform 250ms ease-in;
}
.contact-link:hover::after {
  transform: scaleX(1);
  transform-origin: left;
}
</style>
