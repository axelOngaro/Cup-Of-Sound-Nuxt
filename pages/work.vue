<template>
  <div>
    <div class="workIntro">
      <h1>Mon travail</h1>
      <p>Quelques projets sélectionnés pour vous faire une idée...</p>
    </div>
    <div id="work-page" class="work">
      <div class="projet1 projet">
        <h3>Projet1.</h3>
        <div class="projet-content">
          <div class="embedVideo">
            <iframe
              width="560"
              height="315"
              src="https://www.youtube.com/embed/-qrYeWAMjvI"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>

          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque ad
            veritatis beatae suscipit nisi ratione consectetur similique unde,
            laudantium iusto?
          </p>
        </div>
      </div>
      <div class="projet2 projet">
        <h3>Projet2.</h3>
        <div class="projet-content">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque ad
            veritatis beatae suscipit nisi ratione consectetur similique unde,
            laudantium iusto?
          </p>
          <div>
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
      </div>
      <div class="projet3 projet">
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
h1 {
  font-size: 10rem;
  font-weight: 700;
}
.workIntro {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  background-color: brown;
  color: white;
}
.workIntro p {
  margin-top: 8%;
  font-size: 3rem;
}
.work {
  width: 100%;
  display: flex;
  flex-direction: column;
  padding: 0 10%;
  padding-top: 8%;
}
.projet-content {
  display: flex;
  height: 100%;
}

.projet-content p {
  width: 50%;
}
.projet-content div {
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.embedVideo {
  height: 100%;
}
.projet {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.projet h3 {
  font-size: 3rem;
  font-weight: bold;
}
</style>
