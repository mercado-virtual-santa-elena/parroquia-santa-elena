<template>
  <div class="p-2 w-full md:w-1/3 xl:w-1/4">
    <div class="bg-white rounded-lg shadow-xl">
      <div class="p-12">
        <div class="flex justify-center">
          <img
            :src="empresa.imagenes[0]"
            class="bg-white rounded-full h-16 w-16 -mt-8 flex items-center justify-center"
          />
        </div>
        <div class="mt-8 text-center">
          <h1 class="font-bold text-lg text-gray-700 mb-1">{{empresa.nombre}}</h1>
          <!-- <button
                    @click="showImages(item)"
                    class="mt-6 bg-yellow-600 hover:bg-yellow-400 text-white rounded-full px-12 py-3 shadow-xl focus:outline-none"
          >Ver</button>-->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    empresa: Object,
  },
};
</script>