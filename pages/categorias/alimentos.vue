<template>
  <div>
    <section class="bg-yellow-600 py-8">
      <h1 class="text-center font-bold text-3xl uppercase mb-8">Alimentos</h1>
      <div>
        <div class="flex flex-wrap justify-center">
          <CategoriaEmpresaCard v-for="item in alimentos" :key="item.nombre" :empresa="item" />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import { alimentos } from "../../data/empresas";

export default {
  data() {
    return {
      alimentos,
    };
  },
};
</script>