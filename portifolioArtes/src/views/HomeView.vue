<template>
  <div
    class="w-screen h-screen flex flex-col bg-gradient-to-br from-indigo-50 to-purple-50 select-none overflow-hidden relative"
    @keydown.left.prevent="prev"
    @keydown.right.prevent="next"
    tabindex="0"
    ref="container"
  >
    <!-- Título com efeito de destaque -->
    <div class="text-center mt-12 mb-8 space-y-2">
      <h2 class="text-5xl font-bold bg-gradient-to-r from-indigo-600 to-purple-500 bg-clip-text text-transparent">
        Portifólio de Artes
      </h2>
      <p class="text-lg text-indigo-500 font-medium animate-pulse">Explore nossa jornada artística durante 2° ano</p>
    </div>

    <div class="relative flex-1 px-6 md:px-16">
      <!-- Botões de navegação estilizados -->
      <!-- <button
        @click="prev"
        :disabled="currentIndex === 0"
        class="absolute left-4 top-100 -translate-y-1/2 p-4 bg-blue-200 rounded-full hover:bg-indigo-50 disabled:opacity-30 disabled:cursor-not-allowed shadow-xl z-20 transition-all duration-300 group"
        aria-label="Voltar bimestre"
      >
        <svg class="w-8 h-8 text-indigo-600 group-hover:text-purple-600 transition-colors" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"/>
        </svg>
      </button>

      <button
        @click="next"
        :disabled="currentIndex === bimestres.length - 1"
        class="absolute right-4 top-100 -translate-y-1/2 p-4 bg-blue-200 rounded-full hover:bg-indigo-50 disabled:opacity-30 disabled:cursor-not-allowed shadow-xl z-20 transition-all duration-300 group"
        aria-label="Avançar bimestre"
      >
        <svg class="w-8 h-8 text-indigo-600 group-hover:text-purple-600 transition-colors" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
        </svg>
      </button> -->

      <!-- Container da timeline -->
      <div
        ref="timeline"
        class="flex h-full transition-transform duration-500 ease-out pr-12"
        :style="{ transform: `translateX(-${currentIndex * 100}vw)` }"
        @mousedown="onDragStart"
        @mouseup="onDragEnd"
        @mouseleave="onDragEnd"
        @mousemove="onDragMove"
        @touchstart="onTouchStart"
        @touchmove="onTouchMove"
        @touchend="onTouchEnd"
      >
        <!-- Bimestres -->
        <section
          v-for="(bimestre, idx) in bimestres"
          :key="idx"
          class="w-screen flex-shrink-0 flex flex-col px-8"
        >
          <!-- Título do bimestre -->
          <div class="mb-12 space-y-4">
            <h3 class="text-4xl md:text-5xl font-bold text-indigo-900/90">
              {{ bimestre.titulo }}
            </h3>
            <div class="h-1 w-24 bg-gradient-to-r from-indigo-400 to-purple-300 rounded-full"></div>
          </div>

          <div class="relative w-full h-full">
            <!-- Linha da timeline com efeito de brilho -->
            <div class="absolute top-45 left-0 right-0 h-2 bg-indigo-100 rounded-full transform -translate-y-1/2 shadow-inner">
              <div class="absolute inset-0 bg-gradient-to-r from-indigo-400 to-purple-300 w-full h-full rounded-full opacity-20"></div>
            </div>

            <!-- Aulas -->
            <div class="flex justify-between relative z-10">
              <div
                v-for="(aula, i) in bimestre.aulas"
                :key="i"
                class="flex flex-col items-center text-center w-[160px] mx-auto group"
                @click="abrirAula(i, aula)"
              >
                <!-- Marcador interativo -->
                <div  class="relative mb-6">
                  <div class="absolute -inset-4 bg-indigo-100 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
                  <button
                    
                    class="relative w-16 h-16 rounded-2xl bg-white shadow-xl hover:shadow-2xl transition-all duration-300 flex items-center justify-center transform group-hover:-translate-y-2"
                    :title="aula"
                  >
                    <div >
                      <svg  xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#6A0DAD " version="1.1" id="Capa_1" width="45px" height="45px" viewBox="0 0 45.22 45.22" xml:space="preserve">
                    <g>
                      <g>
                        <path d="M40.335,5.811H28.886c-2.586,0-4.878,1.281-6.275,3.242c-1.397-1.961-3.689-3.242-6.275-3.242h-2.591V8.78h2.591    c2.605,0,4.706,2.086,4.706,4.691v15.265c0,2.598-2.095,4.734-4.693,4.734H4.887c-1.039,0-1.917-0.868-1.917-1.907V10.63    c0-0.646,0.339-1.205,0.848-1.534V5.928C1.612,6.408,0,8.318,0,10.63l0.085,25.803c0,1.863,1.475,3.4,3.336,3.4h15.287    c0.057,1.103,0.971,1.951,2.089,1.951h3.75c1.12,0,2.033-0.849,2.09-1.951h15.162c1.861,0,3.336-1.537,3.336-3.4L45.22,10.63    C45.222,7.95,43.015,5.811,40.335,5.811z M42.252,31.563c0,1.039-0.878,1.907-1.917,1.907H28.873    c-2.598,0-4.692-2.137-4.692-4.734V13.471c0-2.605,2.101-4.691,4.706-4.691h11.449c1.039,0,1.917,0.812,1.917,1.851L42.252,31.563    L42.252,31.563z"/>
                        <path d="M6.219,15.26c0.085,0.034,0.181,0.051,0.27,0.051c0.185,0,0.369-0.074,0.504-0.211l1.282-1.316    c0.131-0.135,0.313-0.211,0.5-0.211c0.188,0,0.369,0.076,0.5,0.211l1.28,1.316c0.135,0.137,0.315,0.211,0.5,0.211    c0.087,0,0.198-0.017,0.282-0.051c0.263-0.107,0.456-0.362,0.456-0.646V4.695c0-0.697-0.606-1.26-1.303-1.26H7.06    c-0.696,0-1.292,0.563-1.292,1.26v9.919C5.769,14.898,5.957,15.153,6.219,15.26z"/>
                      </g>
                    </g>
                  </svg>
                </div>
                  </button>
                </div>

                <!-- Texto da aula -->
                <span class="text-lg font-medium text-indigo-900/90 px-3 py-2 bg-white/80 backdrop-blur-sm rounded-lg shadow-sm transition-all duration-300 group-hover:bg-white group-hover:shadow-md">
                  {{ aula[0] }}
                </span>
                <span class="mt-7 font-bold text-[1.3em] text-indigo-900">{{ aula[1] }}</span>

                <!-- Linha de conexão -->

              </div>
            </div>
          </div>
        </section>

      </div>
    </div>

<!-- Indicador de progresso -->
<div class="absolute bottom-25 left-1/2 -translate-x-1/2 flex items-center space-x-4 z-20">
  <!-- Botão anterior -->
  <div 
    @click="prev" 
    class="flex items-center justify-center rounded-full bg-indigo-100 h-12 w-12 flex-shrink-0"
  >
    <svg 
      xmlns="http://www.w3.org/2000/svg"
      class="text-indigo-600"
      width="30"
      height="30"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      stroke-width="2.5"
      stroke-linecap="round"
      stroke-linejoin="round"
    >
      <polyline points="15 18 9 12 15 6"/>
    </svg> 
  </div>

  <!-- Barra de progresso -->
  <div class="flex items-center space-x-2">
    <div
      v-for="(_, idx) in bimestres"
      :key="idx"
      class="h-2 rounded-full transition-all duration-300"
      :class="currentIndex === idx ? 'bg-indigo-600 w-10' : 'bg-indigo-200 w-6'"
    ></div>
  </div>

  <!-- Botão próximo -->
  <div class="flex items-center justify-center rounded-full bg-indigo-100 h-12 w-12 flex-shrink-0">
    <svg 
      xmlns="http://www.w3.org/2000/svg"
      @click="next"
      class="text-indigo-600"
      width="30"
      height="30"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      stroke-width="2.5"
      stroke-linecap="round"
      stroke-linejoin="round"
    >
      <polyline points="9 18 15 12 9 6"/>
    </svg>
  </div>
</div>
    <div class="text-center text-[17px] text-indigo-600 font-semibold mt-5 mb-5">
      Desenvolvido por: Eduardo Damasceno Lima
    </div>

    <!-- Modal estilizado -->
<!-- Modal estilizado -->
<div
  v-if="aulaAberta"
  class="fixed inset-0 z-50 bg-black/50 backdrop-blur-sm flex items-center justify-center p-4 transition-opacity duration-300"
>
  <div class="bg-white rounded-2xl shadow-2xl max-w-7xl w-full max-h-[90vh] overflow-auto relative">
    <button
      @click="fecharAula"
      class="absolute top-4 right-4 p-2 text-gray-500 hover:text-gray-700 transition-colors"
    >
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
      </svg>
    </button>

    <!-- Aqui vai o conteúdo dinâmico -->
    <div class="p-8 text-center">
      <component :is="componenteAtual" @close="fecharAula" class="h-full" />
    </div>

  </div>
</div>
</div>
</template>


<script setup>
import { ref, onMounted, defineAsyncComponent  } from "vue";
import { useStorePrincipal } from "@/stores/storePrincipal";
import Aula1_1 from '@/components/1bim/aula_1.vue'
import Aula1_2 from '@/components/1bim/aula_2.vue'
import Aula1_3 from '@/components/1bim/aula_3.vue'
import Aula1_4 from '@/components/1bim/aula_4.vue'
import Aula1_5 from '@/components/1bim/aula_5.vue'
import Aula1_6 from '@/components/1bim/aula_6.vue'
import Aula1_7 from '@/components/1bim/aula_7.vue'
import Aula2_1 from '@/components/2bim/aula_1.vue'
import Aula2_2 from '@/components/2bim/aula_2.vue'
import Aula2_3 from '@/components/2bim/aula_3.vue'
import Aula3_1 from '@/components/3bim/aula_1.vue'
import Aula3_2 from '@/components/3bim/aula_2.vue'
import Aula3_3 from '@/components/3bim/aula_3.vue'
import Aula3_4 from '@/components/3bim/aula_4.vue'
import Aula4_1 from '@/components/4bim/aula_1.vue'
import Aula4_2 from '@/components/4bim/aula_2.vue'
import Aula4_3 from '@/components/4bim/aula_3.vue'
import Aula4_4 from '@/components/4bim/aula_4.vue'
import Aula4_5 from '@/components/4bim/aula_5.vue'

const aulaAberta = ref(false);
const modalAulaNome = ref("");
const componenteAtual = ref(null);
const store = useStorePrincipal();

const componentes = {
  '1bim': [Aula1_1, Aula1_2, Aula1_3, Aula1_4, Aula1_5, Aula1_6, Aula1_7],
  '2bim': [Aula2_1, Aula2_2, Aula2_3],
  '3bim': [Aula3_1, Aula3_2, Aula3_3, Aula3_4],
  '4bim': [Aula4_1, Aula4_2, Aula4_3, Aula4_4, Aula4_5],
}

function abrirAula(indexAula, nomeAula) {
  const bimestreNumero = currentIndex.value + 1
  const key = `${bimestreNumero}bim`
  componenteAtual.value = componentes[key][indexAula]
  aulaAberta.value = true
}

function fecharAula() {
  aulaAberta.value = false;
  componenteAtual.value = null;
}

const bimestres = ref([
  {
    titulo: "1° Bimestre",
    aulas: [
      ["Barroco e Rococó no Brasil", '17/04/2025'],
      ["Arte brasileira séc XIX", '24/04/2025	'],
      ["Nossos antepassados", '08/05/2025	'],
      ["Modernizando o Brasil", '15/05/2025'],
      ["Trabalho Bimestral", '22/05/2025'],
      ["Arthur Timótheo", '29/05/2025'],
      ["Arte moderna no Brasil", '29/05/2025']
    ]
  },
  {
     titulo: "2° Bimestre",
     aulas: [
       ["Aula do cinema novo", "18/06/2025"],
       ["Filme Barravento", "03/07/2025"],
       ["Todo mundo odeia o IF."],
     ],
   },
  {
     titulo: "3° Bimestre",
     aulas: [
       ["Arte contemporânea", "09/09/2025"],
       ["Arte: Markenting", "19/09/2025"],
       ["O que é instalação", "03/10/2025"],
       ["Nosso trabalho"],
     ],
   },
     {
     titulo: "4° Bimestre",
     aulas: [
       ["Aula de Arte e política", "28/11/2025"],
       ["Continuação Arte e política", "12/12/2025"],
       ["Aula de Arte de mural", "19/12/2025"],
       ["Fazendo a Serigrafia", "16/01/2026"],
       ["Gravação serigrafia", "23/01/2026"],
     ],
   },
  // {
  //   titulo: "3° Bimestre",
  //   aulas: [
  //     "Funções Quadráticas",
  //     "Logaritmos",
  //     "Geometria Espacial",
  //     "Análise Combinatória",
  //   ],
  // },
  // {
  //   titulo: "4° Bimestre",
  //   aulas: [
  //     "Cálculo Diferencial",
  //     "Cálculo Integral",
  //     "Números Complexos",
  //     "Polinômios",
  //   ],
  // },
]);

const currentIndex = ref(0);
const container = ref(null);
const timeline = ref(null);

const prev = () => {
  if (currentIndex.value === 0) return;
  currentIndex.value--;
}

const next = () => {
  if (currentIndex.value === bimestres.value.length - 1) return;
  currentIndex.value++;

}


// Para garantir foco e capturar eventos de teclado
onMounted(() => {
  container.value.focus();
});
</script>

<style scoped>

/* Adiciona animação suave para os elementos */
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.3s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}

/* Efeito de parallax para profundidade */
.bimestre-card {
  transform-style: preserve-3d;
}


</style>
