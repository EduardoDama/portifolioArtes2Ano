<template>
  <div class="overflow-y bg-gradient-to-br from-blue-50 to-indigo-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-blue-100 text-left">
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-blue-600 to-indigo-700 bg-clip-text text-transparent mb-3">
        Cinema Novo
      </h1>
      <h2 class="text-xl text-indigo-600 font-medium">Uma câmera na mão e uma ideia na cabeça</h2>
      <div class="h-1 w-24 bg-gradient-to-r from-blue-400 to-indigo-500 mx-auto rounded-full mt-4"></div>
    </header>

    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-indigo-400">
      <h2 class="text-xl font-semibold text-indigo-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-indigo-500 rounded-full mr-2"></span>
        Estética e Ideias
      </h2>
      <p class="text-gray-700 mb-4">
        A frase mais famosa que resume a essência do Cinema Novo é a de Glauber Rocha (um dos seus principais diretores): <span class="font-medium">"Uma câmera na mão e uma ideia na cabeça."</span> Isso significava que o cinema não precisava de grandes orçamentos ou superproduções. O mais importante era ter uma visão crítica e autoral para mostrar o Brasil real, com seus problemas sociais, desigualdades, e a vida das pessoas comuns.
      </p>
      <p class="text-gray-700">
        Eles se inspiraram em movimentos internacionais como o <span class="font-semibold">Neorrealismo Italiano</span> e a <span class="font-semibold">Nouvelle Vague Francesa</span>, que também valorizavam a filmagem em locações reais, atores não profissionais e uma abordagem mais crua e realista.
      </p>
    </section>

    <section class="mb-8 bg-gradient-to-r from-indigo-500 to-purple-600 p-5 rounded-xl text-white">
      <h2 class="text-xl font-bold mb-4">Temas Abordados</h2>
      <p class="mb-4">
        Os filmes do Cinema Novo não tinham medo de tocar em feridas sociais. Alguns dos temas mais recorrentes eram:
      </p>
      <ul class="list-disc pl-5 space-y-2 mb-4">
        <li>A miséria e a seca no Nordeste, que retratavam a luta pela sobrevivência dos camponeses.</li>
        <li>A desigualdade social e a pobreza nas grandes cidades.</li>
        <li>O subdesenvolvimento do Brasil, criticando a elite e as estruturas de poder.</li>
        <li>A cultura popular e as raízes do povo brasileiro, muitas vezes usando elementos do folclore e da religião.</li>
      </ul>
    </section>

    <section class="mb-8">
      <h2 class="text-xl font-semibold text-purple-800 mb-4 border-b border-purple-200 pb-2">Diretores e Filmes Icônicos</h2>
      <p class="text-gray-700 mb-4">
        É fundamental associar o movimento a alguns dos seus maiores nomes e obras:
      </p>
      
      <div class="grid md:grid-cols-2 gap-4">
        <div class="bg-white p-4 rounded-xl shadow-sm border border-blue-200">
          <h3 class="font-semibold text-blue-800 mb-2">Glauber Rocha</h3>
          <p class="text-gray-700 text-sm mb-2 italic">
            Foi o grande nome do movimento. Seus filmes são conhecidos por uma estética mais agressiva e simbólica.
          </p>
          <div class="bg-blue-50 p-3 rounded-lg border border-blue-200 mt-2">
            <p class="text-xs text-blue-900"><span class="font-medium">Obras:</span> Barravento (1962) e "Terra em Transe" (1967).</p>
          </div>
          <div class="mt-3">
            <img 
              src="../../../public/imagens/2bimestre/aula1/img1.jpg" 
              class="w-full h-40 object-cover rounded-lg shadow-sm border border-gray-200"
              alt="Cena do filme de Glauber Rocha">
          </div>
        </div>
        
        <div class="bg-white p-4 rounded-xl shadow-sm border border-indigo-200">
          <h3 class="font-semibold text-indigo-800 mb-2">Nelson Pereira dos Santos</h3>
          <p class="text-gray-700 text-sm mb-2 italic">
            Considerado um dos precursores.
          </p>
          <div class="bg-indigo-50 p-3 rounded-lg border border-indigo-200 mt-2">
            <p class="text-xs text-indigo-900"><span class="font-medium">Obra:</span> "Vidas Secas" (1963), baseado na obra de Graciliano Ramos.</p>
          </div>
          <div class="mt-3">
            <img 
              src="../../../public/imagens/2bimestre/aula1/img2.jpg" 
              class="w-full h-40 object-cover rounded-lg shadow-sm border border-gray-200"
              alt="Cena do filme Vidas Secas">
          </div>
        </div>
        
        <div class="bg-white p-4 rounded-xl shadow-sm border border-purple-200">
          <h3 class="font-semibold text-purple-800 mb-2">Carlos Diegues (Cacá Diegues)</h3>
          <p class="text-gray-700 text-sm mb-2 italic">
            Contribuiu com filmes que exploram a realidade dos migrantes nas metrópoles.
          </p>
          <div class="bg-purple-50 p-3 rounded-lg border border-purple-200 mt-2">
            <p class="text-xs text-purple-900"><span class="font-medium">Obra:</span> "A Grande Cidade" (1966)</p>
          </div>
          <div class="mt-3">
            <img 
              src="../../../public/imagens/2bimestre/aula1/img3.jpg" 
              class="w-full h-40 object-cover rounded-lg shadow-sm border border-gray-200"
              alt="Cena do filme A Grande Cidade">
          </div>
        </div>

        <div class="bg-white p-4 rounded-xl shadow-sm border border-blue-200">
          <h3 class="font-semibold text-blue-800 mb-2">Joaquim Pedro de Andrade</h3>
          <p class="text-gray-700 text-sm mb-2 italic">
            Dirigiu filmes com uma estética mais alegórica e tropicalista.
          </p>
          <div class="bg-blue-50 p-3 rounded-lg border border-blue-200 mt-2">
            <p class="text-xs text-blue-900"><span class="font-medium">Obra:</span> "Macunaíma" (1969)</p>
          </div>
          <div class="mt-3">
            <img 
              src="../../../public/imagens/2bimestre/aula1/img4.jpg" 
              class="w-full h-40 object-cover rounded-lg shadow-sm border border-gray-200"
              alt="Cena do filme Macunaíma">
          </div>
        </div>
      </div>
    </section>

    <section class="bg-white p-5 rounded-xl shadow border border-indigo-200 ">
      <div class="flex flex-col md:flex-row gap-6 items-center">
        <div class="md:w-2/3">
          <h3 class="text-xl font-semibold text-indigo-800 mb-3">Legado do Cinema Novo</h3>
          <p class="text-gray-700 mb-4">
            O Cinema Novo não foi apenas um movimento estético, mas também um projeto político e cultural que queria dar voz a quem nunca tinha sido visto no cinema.
          </p>
          <div class="bg-blue-50 p-3 rounded-lg border border-blue-200">
            <h4 class="font-medium text-blue-700 mb-1">Impacto Duradouro</h4>
            <p class="text-sm">Ele mudou para sempre a forma como o Brasil se olhava e se representava na tela, e sua influência pode ser sentida no cinema brasileiro até hoje.</p>
          </div>
        </div>
        <div class="md:w-1/3 text-center">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-24 w-24 mx-auto text-indigo-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z" />
          </svg>
        </div>
      </div>
    </section>

   <section class="flex flex-col items-center bg-white max-w-[750px] p-6 rounded-2xl shadow border border-blue-200 mt-6 mx-auto">
  <div class="text-center mb-6">
    <h2 class="text-2xl md:text-3xl font-bold text-indigo-700 mb-2">Nossa Atividade de Aula</h2>
    <div class="h-1 w-32 bg-gradient-to-r from-blue-400 to-indigo-500 mx-auto rounded-full mt-1"></div>
    <p class="text-gray-700 mt-4 max-w-2xl mx-auto">
      Inspirados pelo Cinema Novo, que buscava mostrar a realidade sem firulas, decidimos registrar um problema real do nosso dia a dia no IF: a longa fila do café da manhã. Nossas fotos contam uma história sobre essa situação e a possível solução.
    </p>
  </div>

  <div class="relative w-full max-w-xl mx-auto rounded-xl overflow-hidden shadow-md border border-gray-100">
    <img :src="currentImg" alt="Fotos da atividade de aula" class="w-full h-auto object-cover rounded-t-xl transition-opacity duration-500">

    <div class="absolute inset-y-0 left-0 right-0 flex justify-between items-center px-4">
      <button @click="prevImg" class="p-2 bg-indigo-200 text-white rounded-full hover:bg-indigo-300 transition-colors focus:outline-none focus:ring-2 focus:ring-indigo-300 focus:ring-opacity-50">
        <span class="text-2xl text-blue-900 leading-none">&lt;</span>
      </button>
      <button @click="nextImg" class="p-2 bg-indigo-200 text-white rounded-full hover:bg-indigo-300 transition-colors focus:outline-none focus:ring-2 focus:ring-indigo-300 focus:ring-opacity-50">
        <span class="text-2xl text-blue-900 leading-none">&gt;</span>
      </button>
    </div>
    <div class="mt-4 text-center text-xl font-semibold text-gray-800 bg-amber-50/70 p-3 rounded-b-xl shadow-inner max-w-xl mx-auto">
{{ msgFoto[currentIndex] }}
</div>
  </div>
</section>

  </div>
</template>

<script setup>
import { ref } from 'vue';
import ativImg1 from '../../../public/imagens/2bimestre/aula1/ativImg1.jpg';
import ativImg2 from '../../../public/imagens/2bimestre/aula1/ativImg2.jpg';
import ativImg3 from '../../../public/imagens/2bimestre/aula1/ativImg3.jpg';
import ativImg4 from '../../../public/imagens/2bimestre/aula1/ativImg4.jpg';
const fotos = [
  ativImg1,
  ativImg2,
  ativImg3,
  ativImg4
];
const msgFoto = [
  'Miguel e Artur descem a escada',
  'Eles se deparam com algo',
  'Ficam assustados com o tamanho da fila',
  'Solução é comer tijolos :D'
];
const currentIndex = ref(0);

const currentImg = ref(fotos[currentIndex.value]);

function nextImg() {
  if (currentIndex.value !== 3){
    currentIndex.value = (currentIndex.value + 1) % fotos.length;
    currentImg.value = fotos[currentIndex.value];
  }
}

function prevImg() {
  if (currentIndex.value !== 0) {
      currentIndex.value = (currentIndex.value - 1 + fotos.length) % fotos.length;
  currentImg.value = fotos[currentIndex.value];
  } 
}
</script>