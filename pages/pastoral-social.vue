<template>
  <div>
    <section class="bg-yellow-600 py-8">
      <div class="gallery">
        <img src="~/assets/images/pastoral-social/Víveres1.jpeg" />
        <img src="~/assets/images/pastoral-social/Comunidades2.jpeg" />
        <img src="~/assets/images/pastoral-social/Comunidades5.jpeg" />
        <img src="~/assets/images/pastoral-social/Navidad1.jpeg" />
        <img src="~/assets/images/pastoral-social/Navidad3.jpeg" />
        <img src="~/assets/images/pastoral-social/Navidad5.jpeg" />
        <img src="~/assets/images/pastoral-social/Comunidades1.jpeg" />
        <img src="~/assets/images/pastoral-social/Víveres3.jpeg" />
        <img src="~/assets/images/pastoral-social/Víveres5.jpeg" />
        <img src="~/assets/images/pastoral-social/Víveres4.jpeg" />
      </div>
    </section>
  </div>
</template>
<style>
.gallery {
  display: grid;
  height: 900px;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  grid-gap: 5px;
  padding: 1rem;
  align-items: center;
  justify-content: center;
  grid-auto-flow: dense;
}

.gallery img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.gallery img:nth-child(3) {
  grid-row: 1 / span 2;
  grid-column: 2 / span 2;
}

.gallery img:nth-child(4) {
  grid-column: 1 / 3;
}

.gallery img:nth-child(7) {
  grid-column: span 2;
}

.gallery img:nth-child(9) {
  grid-column: span 2;
}
</style>