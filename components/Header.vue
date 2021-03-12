<template>
  <header class="header">
    <nuxt-link class="nuxt-link" id="contactLink" to="/home">
      <div class="brand">
        <h1>Cup of sound studio</h1>
      </div></nuxt-link
    >
    <nav>
      <ul>
        <li>
          <nuxt-link class="nuxt-link" id="homeLink" to="/home">Home</nuxt-link>
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
.brand {
  display: flex;
  align-items: center;
}
.header {
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding: 0 8%;
  align-items: center;
  padding-top: 20px;
  min-height: 10vh;
  position: fixed;
  z-index: 1;
  font-size: 2rem;
}
.logo {
  margin-left: 25px;
  width: 60px;
  height: 60px;
}
h1 {
  cursor: pointer;
}
p {
  cursor: pointer;
}
ul {
  width: 30vw;
  display: flex;
  justify-content: space-evenly;
}
li {
  cursor: pointer;
  padding: 1% 1.5%;
  border-radius: 10px;
}

li .nuxt-link::after {
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

li .nuxt-link:hover::after {
  transform: scaleX(1);
  transform-origin: left;
}
.nuxt-link {
  text-decoration: none;
  color: black;
  position: relative;
}
li .nuxt-link {
  padding: 0 10px;
  border-radius: 25px;
}
li .nuxt-link-active {
  transition: ease 1s;
  background-color: rgba(156, 160, 141, 0.637);
  color: white;
}
</style>
