<template>
  <div>
    <div class="work-intro">
      <h1>Mon travail</h1>
      <p>Quelques projets sélectionnés pour vous faire une idée...</p>
    </div>
    <div class="work-page">
      <section class="project project--1">
        <div class="embed-video"></div>
        <div class="project-text">
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iusto aut,
            fugiat impedit ut nisi nam rem libero laudantium, eius distinctio
            dolorem sit reprehenderit iure magni eaque at fuga consequuntur
            error dolore incidunt. Ab illo rem repellat voluptas, inventore
            iste. Eaque, necessitatibus maiores laudantium perspiciatis tempora
            esse, cum quidem nihil voluptate ipsum est inventore. Ab debitis
            maxime ratione omnis labore voluptates at deserunt quidem dolorum
            sint quae, quam adipisci doloribus quia natus voluptatum harum hic
            vitae quis cum iure eligendi aspernatur eum qui. Quis atque
            perspiciatis illo minima sunt, magni facere beatae? Explicabo nulla
            placeat, aliquam a vitae quibusdam sapiente? Placeat.
          </p>
        </div>
      </section>
      <section class="project project--2">
        <div class="project-text">
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iusto aut,
            fugiat impedit ut nisi nam rem libero laudantium, eius distinctio
            dolorem sit reprehenderit iure magni eaque at fuga consequuntur
            error dolore incidunt. Ab illo rem repellat voluptas, inventore
            iste. Eaque, necessitatibus maiores laudantium perspiciatis tempora
            esse, cum quidem nihil voluptate ipsum est inventore. Ab debitis
            maxime ratione omnis labore voluptates at deserunt quidem dolorum
            sint quae, quam adipisci doloribus quia natus voluptatum harum hic
            vitae quis cum iure eligendi aspernatur eum qui. Quis atque
            perspiciatis illo minima sunt, magni facere beatae? Explicabo nulla
            placeat, aliquam a vitae quibusdam sapiente? Placeat.
          </p>
        </div>
        <div class="embed-video"></div>
      </section>
      <section class="project project--3">
        <div class="embed-video"></div>
        <div class="project-text">
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iusto aut,
            fugiat impedit ut nisi nam rem libero laudantium, eius distinctio
            dolorem sit reprehenderit iure magni eaque at fuga consequuntur
            error dolore incidunt. Ab illo rem repellat voluptas, inventore
            iste. Eaque, necessitatibus maiores laudantium perspiciatis tempora
            esse, cum quidem nihil voluptate ipsum est inventore. Ab debitis
            maxime ratione omnis labore voluptates at deserunt quidem dolorum
            sint quae, quam adipisci doloribus quia natus voluptatum harum hic
            vitae quis cum iure eligendi aspernatur eum qui. Quis atque
            perspiciatis illo minima sunt, magni facere beatae? Explicabo nulla
            placeat, aliquam a vitae quibusdam sapiente? Placeat.
          </p>
        </div>
      </section>
      <section class="see-more">
        <p>Pour voir mes autres projets, reprises, mixs...</p>
        <p>direction Youtube, ou Soundcloud!</p>
      </section>
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
.work-intro {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  background-color: brown;
  color: white;
}
.work-intro p {
  margin-top: 8%;
  font-size: 3rem;
}

.project {
  min-height: 100vh;
  display: flex;
}

.project-text {
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.project-text p {
  width: 60%;
  font-size: 2.5rem;
}

.embed-video {
  width: 50%;
  background-color: darkblue;
}
.see-more {
  min-height: 50vh;
  font-size: 4rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
