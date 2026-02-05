<template>
  <div class="overflow-y bg-gradient-to-br from-blue-50 to-indigo-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-blue-100 text-justify">
    <!-- Cabeçalho com gradiente -->
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-blue-600 to-indigo-700 bg-clip-text text-transparent mb-3">
        Barroco e Rococó no Brasil
      </h1>
      <div class="h-1 w-20 bg-gradient-to-r from-blue-400 to-indigo-500 mx-auto rounded-full"></div>
    </header>

    <!-- Seção 1 -->
    <section class="mb-6 bg-white p-5 rounded-xl shadow-sm border-l-4 border-blue-400">
      <h2 class="text-xl font-semibold text-blue-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-blue-500 rounded-full mr-2"></span>
        O que a gente viu na aula?
      </h2>
      <p class="text-gray-700 leading-relaxed">
        Na aula vemos sobre o desenvolvimento do Barroco e Rococó no Brasil entre o século XVIII e o início do século XIX, destacando como a figura central, Antônio Francisco Lisboa (Aleijadinho) e o início de uma arte brasileira que procura afirmar os seus próprios valores.
      </p>
    </section>

    <!-- Seção 2 -->
    <section class="mb-6 bg-white p-5 rounded-xl shadow-sm border-l-4 border-indigo-400">
      <h2 class="text-xl font-semibold text-indigo-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-indigo-500 rounded-full mr-2"></span>
        O Contexto Histórico:
      </h2>
      <p class="text-gray-700 mb-3">
        O Barroco e o Rococó desenvolveram-se plenamente no Brasil entre o século XVIII e o início do século XIX.
      </p>
      <p class="text-gray-700">
        É importante notar que, na mesma época, estes estilos já tinham sido abandonados na Europa, onde a arte regressava aos modelos clássicos.
      </p>
    </section>

    <!-- Subseções com grid otimizada -->
    <div class="grid md:grid-cols-2 gap-5 mb-6">
      <!-- Subseção 1 com imagem integrada -->
      <div class="relative bg-blue-50 rounded-xl overflow-hidden border border-blue-200">
        <div class="p-5">
          <h3 class="text-lg font-semibold text-blue-800 mb-2">A Ligação com a Religião:</h3>
          <p class="text-gray-700 mb-4">
            No Brasil, o Barroco e o Rococó estão claramente associados à religião católica. Existem inúmeras igrejas por todo o país construídas segundo os princípios barrocos.
          </p>
        </div>
        <img src="../../../public/imagens/1bimestre/img1.png" class="w-full h-48 md:h-56 object-cover" alt="Igreja barroca">
        <div class="absolute inset-0 bg-gradient-to-t from-blue-900/30 to-transparent pointer-events-none"></div>
      </div>

      <!-- Subseção 2 -->
      <div class="bg-indigo-50 p-5 rounded-xl border border-indigo-200">
        <h3 class="text-lg font-semibold text-indigo-800 mb-2">Regiões de Destaque:</h3>
        <p class="text-gray-700">
          Estes estilos são mais notáveis em regiões que enriqueceram com o comércio de açúcar e a mineração. As principais regiões mencionadas são Minas Gerais, Rio de Janeiro, Bahia e Pernambuco.
        </p>
      </div>
    </div>

    <!-- Destaque Aleijadinho com layout otimizado -->
    <section class="mb-6 bg-gradient-to-r from-blue-500 to-indigo-600 p-5 rounded-xl text-white">
      <div class="flex flex-col lg:flex-row gap-5">
        <div class="lg:w-3/5">
          <h2 class="text-xl md:text-2xl font-bold mb-3 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
            </svg>
            Antônio Francisco Lisboa (Aleijadinho)
          </h2>
          <ul class="list-disc pl-5 space-y-1.5 mb-4">
            <li>Extraordinário arquiteto, carpinteiro e escultor</li>
            <li>Escultor de talento incomparável</li>
            <li>Obras presentes em museus e igrejas, principalmente em Ouro Preto</li>
            <li>Santuário do Bom Jesus de Matosinhos em Congonhas (MG) como principal obra (1805)</li>
          </ul>
        </div>
        
        <!-- Grid de imagens compacta -->
        <div class="lg:w-2/5 grid grid-cols-2 gap-3">
          <div class="relative rounded-lg overflow-hidden h-40">
            <img src="../../../public/imagens/1bimestre/img2.png" class="w-full h-full object-cover" alt="Obra do Aleijadinho">
            <div class="absolute inset-0 bg-gradient-to-t from-blue-900/40 to-transparent"></div>
          </div>
          <div class="relative rounded-lg overflow-hidden h-40">
            <img src="../../../public/imagens/1bimestre/img3.png" class="w-full h-full object-cover" alt="Detalhe escultural">
            <div class="absolute inset-0 bg-gradient-to-t from-indigo-900/40 to-transparent"></div>
          </div>
          <div class="col-span-2 bg-blue-400/20 p-3 rounded-lg border border-white/20">
            <p class="text-sm italic">"Patrono da Arte no Brasil" (Lei nº 5.984/1973)</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Artistas e Obras integrados -->
    <section class="mb-6">
      <div class="flex flex-col md:flex-row gap-5">
        <div class="md:w-2/3 bg-white p-5 rounded-lg shadow">
          <h2 class="text-xl font-semibold text-blue-800 mb-3">Outros Artistas e Obras:</h2>
          <p class="text-gray-700 mb-2">
            <span class="font-medium text-indigo-700">Manuel da Costa Ataíde</span> e sua obra "Assunção da Virgem".
          </p>
          <p class="text-gray-700">
            Destaque para seu uso característico de 
            <span class="text-blue-600 font-medium">azuis</span> e 
            <span class="text-red-500 font-medium">vermelhos</span> na pintura.
          </p>
        </div>
        
        <div class="md:w-1/3 bg-gradient-to-br from-blue-100 to-indigo-100 p-5 rounded-lg border border-blue-200">
          <h3 class="font-semibold text-blue-800 mb-2">Técnicas Brasileiras:</h3>
          <ul class="list-disc pl-5 text-gray-700 space-y-1">
            <li>Técnica da <span class="font-medium">taipa de pilão</span></li>
            <li>Uso da <span class="font-medium">pedra-sabão</span></li>
            <li>Paleta de cores nacional</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Arte Brasileira -->
    <section class="mb-6 bg-white p-5 rounded-xl shadow">
      <h2 class="text-xl font-semibold text-blue-800 mb-3">A Busca por uma Arte Brasileira:</h2>
      <p class="text-gray-700 mb-3">
        O Barroco marcou o início da busca por identidade artística nacional, com:
      </p>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="bg-blue-50 p-4 rounded-lg border border-blue-200">
          <h3 class="font-medium text-blue-700 mb-1">Técnicas Locais</h3>
          <p class="text-sm">Taipa de pilão na arquitetura</p>
        </div>
        <div class="bg-blue-50 p-4 rounded-lg border border-blue-200">
          <h3 class="font-medium text-blue-700 mb-1">Materiais Regionais</h3>
          <p class="text-sm">Pedra-sabão nas esculturas</p>
        </div>
        <div class="bg-blue-50 p-4 rounded-lg border border-blue-200">
          <h3 class="font-medium text-blue-700 mb-1">Cores Identitárias</h3>
          <p class="text-sm">Azuis e vermelhos característicos</p>
        </div>
      </div>
    </section>

    <!-- Reconhecimento compacto -->
    <section class="bg-blue-100 border border-blue-200 rounded-xl p-5">
      <div class="flex items-start">
        <div class="mr-4 mt-1 text-blue-700">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
          </svg>
        </div>
        <div>
          <h2 class="text-lg font-semibold text-blue-800 mb-1">Reconhecimento Oficial</h2>
          <p class="text-gray-700 text-sm">
            Lei Federal 5.984/1973 declara Aleijadinho Patrono da Arte no Brasil
          </p>
        </div>
      </div>
    </section>
  </div>
</template>
<script setup>
import { ref } from "vue";
</script>