<template>
  <header class="header">
    <h1>Cup of sound studio</h1>
    <p id="toggleTheme">*</p>
    <nav>
      <ul>
        <li>
          <nuxt-link class="nuxt-link" id="homeLink" to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link class="nuxt-link" id="aboutLink" to="about"
            >About</nuxt-link
          >
        </li>
        <li>
          <nuxt-link class="nuxt-link" id="workLink" to="work">Work</nuxt-link>
        </li>
        <li>
          <nuxt-link class="nuxt-link" id="contactLink" to="contact"
            >Contact</nuxt-link
          >
        </li>
      </ul>
    </nav>
  </header>
</template>
<script>
export default {
  name: 'Header',
}
</script>
<style scoped>
.header {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-top: 20px;
  min-height: 10vh;
  position: fixed;
  z-index: 1;
}
h1 {
  cursor: pointer;
}
p {
  cursor: pointer;
}
ul {
  width: 500px;
  display: flex;
  justify-content: space-evenly;
}
li {
  cursor: pointer;
  padding: 1% 1.5%;
  border-radius: 10px;
}
.nuxt-link {
  text-decoration: none;
  color: black;
}
</style>
