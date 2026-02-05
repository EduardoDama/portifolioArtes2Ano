<template>
  <div class="overflow-y bg-gradient-to-br from-indigo-50 to-purple-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-indigo-100 text-left">
    <!-- Cabeçalho -->
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-indigo-600 to-purple-700 bg-clip-text text-transparent mb-3">
        Arte Brasileira no Século XIX
      </h1>
      <div class="h-1 w-24 bg-gradient-to-r from-indigo-400 to-purple-500 mx-auto rounded-full"></div>
    </header>

    <!-- Resumo da Aula -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-indigo-400">
      <h2 class="text-xl font-semibold text-indigo-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-indigo-500 rounded-full mr-2"></span>
        O que vimos na aula?
      </h2>
      <p class="text-gray-700">
        A aula focou na arte brasileira do séc. XIX, com destaque para o impacto da Missão Artística Francesa, e explorou o seu diálogo com a produção de artistas contemporâneos.
      </p>
    </section>

    <!-- Linha do Tempo -->
    <div class="relative mb-8">
      <div class="absolute left-1/2 transform -translate-x-1/2 h-full w-0.5 bg-gradient-to-b from-indigo-300 to-purple-300"></div>
      
      <!-- Evento 1 -->
      <div class="flex items-center mb-10">
        <div class="w-5 h-5 rounded-full bg-indigo-500 z-10"></div>
        <div class="ml-6 w-5/12 bg-white p-4 rounded-xl shadow-sm border border-indigo-100">
          <div class="text-xs text-indigo-500 font-semibold mb-1">1808</div>
          <h3 class="font-semibold text-indigo-800 mb-1">Chegada da Família Real</h3>
          <p class="text-gray-700 text-sm">Dom João VI chega ao Brasil fugindo de Napoleão, com 15 mil pessoas</p>
        </div>
      </div>
      
      <!-- Evento 2 -->
      <div class="flex items-center justify-end mb-10">
        <div class="mr-6 w-5/12 bg-white p-4 rounded-xl shadow-sm border border-purple-100 text-right">
          <div class="text-xs text-purple-500 font-semibold mb-1">1816</div>
          <h3 class="font-semibold text-purple-800 mb-1">Missão Artística Francesa</h3>
          <p class="text-gray-700 text-sm">Chefiada por Joachin Lebreton, com Taunay, Debret e Montigny</p>
        </div>
        <div class="w-5 h-5 rounded-full bg-purple-500 z-10"></div>
      </div>
      
      <!-- Evento 3 -->
      <div class="flex items-center mb-10">
        <div class="w-5 h-5 rounded-full bg-indigo-500 z-10"></div>
        <div class="ml-6 w-5/12 bg-white p-4 rounded-xl shadow-sm border border-indigo-100">
          <div class="text-xs text-indigo-500 font-semibold mb-1">1826</div>
          <h3 class="font-semibold text-indigo-800 mb-1">Academia Imperial de Belas-Artes</h3>
          <p class="text-gray-700 text-sm">Transformação da Escola Real fundada em 1816</p>
        </div>
      </div>
    </div>

    <!-- Artistas e Obras -->
    <div class="grid md:grid-cols-2 gap-6 mb-8">
      <!-- Nicolas Taunay -->
      <div class="bg-gradient-to-br from-indigo-50 to-purple-50 p-5 rounded-xl border border-indigo-200">
        <h3 class="text-lg font-semibold text-indigo-800 mb-2 flex items-center">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-2" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z" clip-rule="evenodd" />
          </svg>
          Nicolas Antoine Taunay
        </h3>
        <p class="text-gray-700 mb-3">
          <span class="font-medium">Obra:</span> "Vista do Outeiro, Praia e Igreja da Glória" (1817)
        </p>
        <p class="text-gray-700 text-sm mb-3">
          Óleo sobre tela - Museus Castro Maya, Rio de Janeiro
        </p>
        
        <!-- Imagem com legenda -->
        <div class="mt-4">
          <img 
            src="../../../public/imagens/1bimestre/aula2/img2.png" 
            class="w-full h-70 object-cover rounded-lg shadow-md border border-indigo-100"
            alt="Vista do Outeiro, Praia e Igreja da Glória por Nicolas Taunay">
          <p class="text-xs text-gray-500 mt-2 italic">"Vista do Outeiro, Praia e Igreja da Glória" (1817), óleo sobre tela</p>
        </div>
      </div>
      
      <!-- Jean-Baptiste Debret -->
      <div class="bg-gradient-to-br from-purple-50 to-indigo-50 p-5 rounded-xl border border-purple-200">
        <h3 class="text-lg font-semibold text-purple-800 mb-2 flex items-center">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-2" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z" clip-rule="evenodd" />
          </svg>
          Jean-Baptiste Debret
        </h3>
        <div class="space-y-2 mb-3">
          <p class="text-gray-700">
            <span class="font-medium">Obra 1:</span> "Coroação de Dom Pedro I" (1828)
          </p>
          <p class="text-gray-700">
            <span class="font-medium">Obra 2:</span> "Um jantar brasileiro" (1827)
          </p>
          <p class="text-gray-700 text-sm">
            Publicado em "Viagem Pitoresca e Histórica ao Brasil" (1834-1839)
          </p>
        </div>
        
        <!-- Imagem com legenda -->
        <div class="mt-4">
          <img 
            src="../../../public/imagens/1bimestre/aula2/img1.png" 
            class="w-full h-70 object-cover rounded-lg shadow-md border border-purple-100"
            alt="Coroação de Dom Pedro I por Jean-Baptiste Debret">
          <p class="text-xs text-gray-500 mt-2 italic">"Coroação de Dom Pedro I" (1828), parte do Acervo do Palácio Itamaraty</p>
        </div>
      </div>
    </div>

    <!-- Artistas Contemporâneos -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-purple-800 mb-4 border-b border-purple-200 pb-2">Diálogo com a Arte Contemporânea</h2>
      
      <!-- Gê Viana -->
      <div class="mb-6 bg-white p-5 rounded-xl shadow-sm">
        <div class="flex flex-col md:flex-row gap-5">
          <div class="md:w-3/4">
            <h3 class="text-lg font-semibold text-indigo-800 mb-2 flex items-center">
              <span class="bg-indigo-100 text-indigo-800 px-2 py-1 rounded mr-2 text-sm">Indígena</span>
              Gê Viana (Povo Anapuru Muypurá)
            </h3>
            <ul class="list-disc pl-5 text-gray-700 space-y-1 mb-3">
              <li>Vencedora do Prêmio PIPA 2020</li>
              <li>Técnica: Colagens e fotomontagens ("remixagens")</li>
              <li>Obra: "Sentem para jantar" (2021) da série "Atualização traumática de Debret"</li>
              <li><span class="italic">"Recortar é recontar"</span> - confronta a cultura colonizadora</li>
            </ul>
            
            <!-- Imagem da obra de Gê Viana com legenda -->
            <div class="mt-4">
              <img 
                src="../../../public/imagens/1bimestre/aula2/img4.png" 
                class="w-full h-80 object-cover rounded-lg shadow-md border border-indigo-100"
                alt="Obra de Gê Viana: Sentem para jantar">
              <p class="text-xs text-gray-500 mt-2 italic">"Sentem para jantar" (2021) - Série "Atualização traumática de Debret"</p>
            </div>
          </div>
          
          <div class="md:w-1/4 bg-indigo-50 p-4 rounded-lg border border-indigo-200 flex items-center justify-center">
            <p class="text-indigo-700 text-center italic">"As imagens olham de volta, desestruturam o passado"</p>
          </div>
        </div>
      </div>
      
      <!-- Outros artistas em grid -->
      <div class="grid md:grid-cols-2 gap-5">
        <!-- Aline Motta -->
        <div class="bg-purple-50 p-4 rounded-xl border border-purple-200">
          <h3 class="font-semibold text-purple-800 mb-2">Aline Motta</h3>
          <p class="text-gray-700 text-sm">
            <span class="font-medium">Obra:</span> "Filha Natural" (2018/2019)
          </p>
          <p class="text-gray-700 text-sm mb-3">
            Instalação multimeios (fotografia, publicação, performance, vídeo)
          </p>
          
          <!-- Imagem com legenda -->
          <div>
            <img 
              src="../../../public/imagens/1bimestre/aula2/img5.png" 
              class="w-full h-60 object-cover rounded-lg shadow-md border border-purple-100"
              alt="Obra de Aline Motta: Filha Natural">
            <p class="text-xs text-gray-500 mt-2 italic">"Filha Natural" (2018/2019) - Instalação multimeios</p>
          </div>
        </div>
        
        <!-- Barbara Walker -->
        <div class="bg-indigo-50 p-4 rounded-xl border border-indigo-200">
          <h3 class="font-semibold text-indigo-800 mb-2">Barbara Walker</h3>
          <p class="text-gray-700 text-sm">
            <span class="font-medium">Obra:</span> "barbara-walker-titian" (2019)
          </p>
          <p class="text-gray-700 text-sm mb-3">
            Diálogo com "Diana and Actaeon" de Titian (1556–59)
          </p>
          
          <!-- Imagem com legenda -->
          <div>
            <img 
              src="../../../public/imagens/1bimestre/aula2/img7.png" 
              class="w-full h-60 object-cover rounded-lg shadow-md border border-indigo-100"
              alt="Obra de Barbara Walker">
            <p class="text-xs text-gray-500 mt-2 italic">"barbara-walker-titian" (2019) - Vanishing Point series</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Legado -->
    <section class="bg-gradient-to-r from-indigo-500 to-purple-600 p-5 rounded-xl text-white">
      <h2 class="text-xl font-bold mb-3">Legado Artístico</h2>
      <p class="mb-3">
        A Missão Artística Francesa estabeleceu as bases do ensino acadêmico de arte no Brasil, criando um diálogo permanente entre tradição e contemporaneidade.
      </p>
      <div class="flex items-center">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
          <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
        </svg>
        <p class="text-sm">Da arte acadêmica do século XIX às intervenções contemporâneas, a arte brasileira continua seu diálogo com a história</p>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";
</script>