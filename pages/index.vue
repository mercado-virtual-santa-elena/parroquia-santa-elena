<template>
  <div>
    <HomeCarousel />

    <section class="bg-yellow-600 py-8">
      <div class="container mx-auto flex items-center flex-wrap pt-4 pb-12">
        <nav id="store" class="w-full z-30 top-0 px-6 py-1">
          <div
            class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 px-2 py-3"
          >
            <span class="uppercase tracking-wide font-bold text-white text-xl">Empresas</span>
          </div>
        </nav>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/alimentos" class="m-auto">
            <img
              src="/icons/categorias/alimentos.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">Alimentos</p>
            </div>
          </n-link>
        </div>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/alquileres" class="m-auto">
            <img
              src="/icons/categorias/alquiler.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">Alquileres</p>
            </div>
          </n-link>
        </div>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/construccion" class="m-auto">
            <img
              src="/icons/categorias/construccion.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">
                Construcción y
                <br />Mantenimiento
              </p>
            </div>
          </n-link>
        </div>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/limpieza" class="m-auto">
            <img
              src="/icons/categorias/limpieza.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">Limpieza</p>
            </div>
          </n-link>
        </div>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/manualidades" class="m-auto">
            <img
              src="/icons/categorias/manualidades.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">Manualidades</p>
            </div>
          </n-link>
        </div>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/salud" class="m-auto">
            <img
              src="/icons/categorias/salud.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">Salud</p>
            </div>
          </n-link>
        </div>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/servicios" class="m-auto">
            <img
              src="/icons/categorias/servicios.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">Servicios</p>
            </div>
          </n-link>
        </div>

        <div class="w-full md:w-1/3 xl:w-1/4 p-6 flex flex-col">
          <n-link to="/categorias/tecnologia" class="m-auto">
            <img
              src="/icons/categorias/tecnologia.svg"
              class="w-16 fill-current text-gray-500 hover:text-black m-auto"
            />
            <div class="pt-3 flex items-center justify-center">
              <p class="font-bold">Tecnología</p>
            </div>
          </n-link>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* .worksans {
  font-family: "Work Sans", sans-serif;
} */
</style>
