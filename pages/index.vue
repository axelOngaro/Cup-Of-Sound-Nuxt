<template>
  <div>
    <p>
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Et, sapiente
      reiciendis. Qui cum saepe nulla quibusdam molestias excepturi fugit nemo
      necessitatibus maiores sunt quidem nobis asperiores enim dolorum delectus
      voluptatibus distinctio, itaque provident, explicabo optio facere culpa
      tenetur quaerat blanditiis? Nam ullam necessitatibus voluptate fugit
      architecto odit sit, possimus velit.
    </p>
  </div>
</template>

<script>
import Header from '../components/Header'
export default {
  components: 'Header',
  transition: 'home',
}
</script>

<style>
div {
  background-color: #efeee7;
}

.home-enter-active,
.home-leave-active {
  transition: opacity 0.5s;
}
.home-enter,
.home-leave-active {
  opacity: 0;
}
</style>
