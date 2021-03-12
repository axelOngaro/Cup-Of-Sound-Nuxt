<template>
  <div>
    <Header />
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Jost', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #efeee7;
  overflow-y: scroll;
}
html::-webkit-scrollbar-track {
  border-radius: 10px;
  background-color: transparent;
}

html::-webkit-scrollbar {
  width: 12px;
  background-color: transparent;
}

html::-webkit-scrollbar-thumb {
  border-radius: 10px;
  background-color: gray;
}
a {
  text-decoration: none;
  color: black;
}

li {
  list-style: none;
}
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.home-enter-active,
.home-leave-active {
  transition: opacity 0.75s;
}
.home-enter,
.home-leave-active {
  opacity: 0;
}
</style>
