<template>
    <div class="bg-white rounded-2xl shadow-2xl p-8 w-full text-center">
      <h1 class="text-2xl font-bold text-indigo-700">Modernizando o Brasil</h1>
      <!-- Botão para fechar (exemplo, use v-if ou v-show no pai para esconder o popup) -->
      <button
        @click="$emit('close')"
        class="mt-6 px-4 py-2 bg-indigo-600 text-white rounded hover:bg-indigo-700 transition"
      >
        Fechar
      </button>
    </div>
</template>

<script setup>
import { ref } from "vue";


</script>