<template>
  <div>
    <h1>A propos</h1>
    <p>
      Cup Of Sound est un home-studio de production musicale, situé à
      Rouffiac-tolosan près de Toulouse. Je propose des services
      d’enregistrement, mixage, mastering ou encore des voix-offs, accompagnés
      de conseils artistiques.
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum enim eius,
      pariatur eum debitis fugiat!
    </p>
  </div>
</template>
<script>
export default {
  name: 'about',
  transition: 'home',
}
</script>
<style scoped>
div {
  height: 100vh;
  width: 100%;
  padding-top: 20vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}
h1 {
  font-size: 10rem;
  margin-bottom: 4vh;
}
p {
  width: 50%;
  padding: 5vh 0;
  font-size: 3rem;
}
</style>
