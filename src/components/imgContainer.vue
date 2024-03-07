<template>
<main class="main">
  <div class="bg-n">
    <section class="mt-5">
      <img src="/src/images/salud.avif" alt="salud">
      <img src="/src/images/entrenador.jpg" alt="entrenador">
      <img src="/src/images/accesories.avif" alt="accesorios">
      <img src="/src/images/bMediacados.jpg" alt="b-Medicados">
      <img src="/src/images/peluqueria.avif" alt="peluqueria">
    </section>
    <div>
      <p>Servicios</p>
    </div>
  </div>
</main>
</template>

<style scoped>
.main {
  min-height: calc(100vh - 56px);
}

.bg-n{
  background-color: #FFDAB9;
}
img {
  object-fit: cover;
  width: 100%;
  height: 100%;
}
#texto{
  display: inline-block;
  vertical-align: top;
}

section {
  display: flex;
  width: 600px;
  height: 430px;
}

section img {
  width: 0px;
  flex-grow: 1;
  object-fit: cover;
  opacity: .8;
  transition: 1s ease;
}

section img:hover {
  width: 300px;
  opacity: 1;
  filter: contrast(120%);
}
</style>
