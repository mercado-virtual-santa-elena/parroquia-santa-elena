<template>
  <nav id="header" class="w-full z-30 top-0 py-1">
    <div
      class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 px-2 py-3 sm:max-w-full md:max-w-full md:text-base"
    >
      <div class="w-full md:w-auto">
        <n-link to="/">
          <img :src="'/logo.jfif'" alt="Logo parroquia" class="object-contain h-24 m-auto md:h-40" />
        </n-link>
      </div>

      <div class="w-full text-center mt-4 md:w-auto md:mt-base">
        <n-link to="/">
          <span class="uppercase font-bold text-lg">Mercado virtual de pequeñas comunidades</span>
          <span class="uppercase text-xs block md:text-center">Parroquia Santa Elena</span>
        </n-link>
      </div>

      <label for="menu-toggle" class="w-full cursor-pointer md:hidden block">
        <span class="text-center text-xs block mt-6 bg-gray-900 p-2">MENÚ</span>
      </label>
      <input class="hidden" type="checkbox" id="menu-toggle" />

      <div class="hidden md:flex md:items-center md:w-auto w-full order-3 md:order-1" id="menu">
        <nav>
          <ul class="md:flex items-center justify-between text-base text-white pt-4 md:pt-0">
            <li>
              <n-link
                to="/pastoral-social"
                class="inline-block no-underline hover:underline py-2 px-4"
              >Pastoral social</n-link>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </nav>
</template>
<style>
#menu-toggle:checked + #menu {
  display: block;
}

/* .hover\:grow {
  transition: all 0.3s;
  transform: scale(1);
}

.hover\:grow:hover {
  transform: scale(1.02);
} */
</style>