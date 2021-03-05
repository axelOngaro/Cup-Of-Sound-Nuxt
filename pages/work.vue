<template>
  <div>
    <div id="work-page" class="work">
      <h2>Mon travail.</h2>
      <div class="projet1">
        <h3>Projet1.</h3>
        <div class="projet-content">
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/-qrYeWAMjvI"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque ad
            veritatis beatae suscipit nisi ratione consectetur similique unde,
            laudantium iusto?
          </p>
        </div>
      </div>
      <div class="projet2">
        <h3>Projet2.</h3>
        <div class="projet-content">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque ad
            veritatis beatae suscipit nisi ratione consectetur similique unde,
            laudantium iusto?
          </p>
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/MWZam4jJrJg"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </div>
      <div class="projet3">
        <h3>Projet3.</h3>
        <div class="projet-content">
          <img src="#" alt="" />
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque ad
            veritatis beatae suscipit nisi ratione consectetur similique unde,
            laudantium iusto?
          </p>
        </div>
      </div>
      <p id="voirplus">
        Pour voir le reste de mes travaux, direction
        <a
          href="https://soundcloud.com/user-905879753"
          target="_blank"
          rel="noopener noreferrer"
          >Soundcloud</a
        >
        et
        <a
          href="https://www.youtube.com/channel/UC0Y_dTPUAt9BrusvmsSrvWg"
          target="_blank"
          rel="noopener noreferrer"
          >Youtube</a
        >!
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'work',
  transition: 'home',
}
</script>
<style scoped>
.work {
  min-height: 200vh;
  width: 100%;
  display: flex;
  flex-direction: column;
  padding: 0 10%;
  padding-top: 10%;
}
.projet-content {
  display: flex;
}
</style>
