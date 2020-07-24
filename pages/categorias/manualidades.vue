<template>
  <div>
    <section class="bg-yellow-600 py-8">
      <h1 class="text-center font-bold text-3xl uppercase mb-8">Manualidades</h1>
      <div>
        <div class="flex flex-wrap justify-center">
          <CategoriaEmpresaCard v-for="item in manualidades" :key="item.nombre" :empresa="item" />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import { manualidades } from "../../data/empresas";

export default {
  data() {
    return {
      manualidades,
    };
  },
};
</script>