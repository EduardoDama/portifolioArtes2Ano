<template>
  <div class="overflow-y bg-gradient-to-br from-purple-50 to-indigo-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-purple-100">
    <!-- Cabeçalho -->
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-purple-600 to-indigo-700 bg-clip-text text-transparent mb-3">
        Semana de Arte Moderna de 1922
      </h1>
      <h2 class="text-xl text-purple-600 font-medium">Modernizando o Brasil</h2>
      <div class="h-1 w-24 bg-gradient-to-r from-purple-400 to-indigo-500 mx-auto rounded-full mt-4"></div>
    </header>

    <!-- Introdução -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-purple-400">
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-2/3">
          <p class="text-gray-700 mb-4">
            Evento crucial realizado no Teatro Municipal de São Paulo entre 11 e 18 de fevereiro de 1922, com o objetivo de apresentar a produção artística mais atualizada do país.
          </p>
          <div class="bg-purple-50 p-4 rounded-lg border border-purple-200">
            <p class="text-gray-700">
              No hall do teatro, houve uma exposição coletiva com esculturas, projetos arquitetônicos e pinturas. O cartaz do evento foi criado por Di Cavalcanti.
            </p>
          </div>
        </div>
        <div class="md:w-1/3">
          <img 
            src="../../../public/imagens/1bimestre/aula7/cartaz-semana-22.png" 
            class="w-full h-50 object-cover rounded-xl shadow-md border border-purple-200"
            alt="Cartaz da Semana de Arte Moderna">
          <p class="text-xs text-gray-500 mt-2 italic">Cartaz por Di Cavalcanti (1922)</p>
        </div>
      </div>
    </section>

    <!-- Precursores -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-purple-800 mb-4 border-b border-purple-200 pb-2">Os Precursores do Modernismo</h2>
      
      <div class="grid md:grid-cols-2 gap-6">
        <!-- Anita Malfatti -->
        <div class="bg-white p-5 rounded-xl shadow-sm border border-purple-200">
          <div class="flex items-center mb-3">
            <div class="bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm mr-3">Pioneira</div>
            <h3 class="text-lg font-semibold text-purple-800">Anita Malfatti</h3>
          </div>
          <p class="text-gray-700 mb-4">
            Considerada mártir e pioneira do modernismo brasileiro, apresentou 20 das 100 obras expostas no evento.
          </p>
          <div class="flex flex-col md:flex-row gap-4">
            <div class="md:w-1/2">
              <img 
                src="../../../public/imagens/1bimestre/aula7/anita-malfatti.png" 
                class="w-full h-80 object-cover rounded-lg shadow-sm"
                alt="Anita Malfatti">
              <p class="text-xs text-gray-500 mt-2 italic">Anita Malfatti</p>
            </div>
            <div class="md:w-1/2">
              <img 
                src="../../../public/imagens/1bimestre/aula7/estudante.png" 
                class="w-full h-80 object-cover rounded-lg shadow-sm"
                alt="A Estudante">
              <p class="text-xs text-gray-500 mt-2 italic">"A Estudante" (1915-16)</p>
            </div>
          </div>
        </div>
        
        <!-- Lasar Segall -->
        <div class="bg-white p-5 rounded-xl shadow-sm border border-indigo-200">
          <div class="flex items-center mb-3">
            <div class="bg-indigo-100 text-indigo-800 px-3 py-1 rounded-full text-sm mr-3">Precursor</div>
            <h3 class="text-lg font-semibold text-indigo-800">Lasar Segall</h3>
          </div>
          <p class="text-gray-700 mb-4">
            Identificado como um dos precursores da arte moderna no Brasil, trouxe influências expressionistas para o país.
          </p>
          <div class="bg-gradient-to-r from-indigo-100 to-purple-100 rounded-lg flex items-center justify-center text-gray-500">
              <img 
              class="w-full h-80 object-cover rounded-lg shadow-sm"
              src="../../../public/imagens/1bimestre/aula7/bananal.png" 
              alt="">
            </div>
            <p class="text-xs text-gray-500 mt-2 italic">Bananal feito por Lasar Sagall (1927)</p>
        </div>
      </div>
    </section>

    <!-- Tarsila do Amaral -->
    <section class="mb-8 bg-gradient-to-r from-purple-500 to-indigo-600 p-5 rounded-xl text-white">
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-1/3">
          <img 
            src="../../../public/imagens/1bimestre/aula7/tarsila.png" 
            class="w-full h-82 object-cover rounded-xl shadow-lg border-2 border-white"
            alt="Tarsila do Amaral">
          <p class="text-xs text-purple-200 mt-2 italic">Tarsila do Amaral em Paris (1923)</p>
        </div>
        
        <div class="md:w-2/3">
          <h2 class="text-2xl font-bold mb-3">Tarsila do Amaral</h2>
          <p class="mb-4">
            Embora não tenha participado da Semana de 22 por estar em Paris, tornou-se o grande nome da Arte Moderna brasileira.
          </p>
          
          <div class="bg-purple-400/30 p-4 rounded-lg border border-purple-300 mb-4">
            <p class="font-bold mb-2">Características marcantes:</p>
            <ul class="list-disc pl-5">
              <li>Incorporou a tropicalidade brasileira</li>
              <li>Uso intenso das cores nacionais</li>
              <li>Síntese entre influências europeias e identidade brasileira</li>
            </ul>
          </div>
          
          <div class="grid grid-cols-2 gap-4">
            <div class="bg-white/20 p-3 rounded-lg">
              <p class="font-medium">Abaporu (1928)</p>
              <p class="text-sm">Obra seminal do movimento antropofágico</p>
            </div>
            <div class="bg-white/20 p-3 rounded-lg">
              <p class="font-medium">Operários (1933)</p>
              <p class="text-sm">Representação da industrialização brasileira</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Patrícia Galvão (Pagu) -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow border border-indigo-200">
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-2/3">
          <div class="flex items-center mb-3">
            <div class="bg-red-100 text-red-800 px-3 py-1 rounded-full text-sm mr-3">Revolucionária</div>
            <h2 class="text-xl font-semibold text-indigo-800">Patrícia Galvão (Pagu)</h2>
          </div>
          
          <p class="text-gray-700 mb-4">
            Conheceu Tarsila e Oswald de Andrade em 1929, trazendo engajamento político para o modernismo e participando da revista de Antropofagia.
          </p>
          
          <div class="grid md:grid-cols-2 gap-4">
            <div class="bg-indigo-50 p-4 rounded-lg border border-indigo-200">
              <h3 class="font-medium text-indigo-700 mb-1">Contribuição</h3>
              <p class="text-sm">Intelectual que conectou arte e política</p>
            </div>
            <div class="bg-purple-50 p-4 rounded-lg border border-purple-200">
              <h3 class="font-medium text-purple-700 mb-1">Movimento</h3>
              <p class="text-sm">Participante ativa da Antropofagia</p>
            </div>
          </div>
        </div>
        
        <div class="md:w-1/3">
          <img 
            src="../../../public/imagens/1bimestre/aula7/pagu.png" 
            class="w-full h-50 object-cover rounded-lg shadow-md border border-indigo-100"
            alt="Patrícia Galvão (Pagu)">
          <p class="text-xs text-gray-500 mt-2 italic">Patrícia Galvão (Pagu)</p>
        </div>
      </div>
    </section>

    <!-- Outros Artistas e Obras -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-purple-800 mb-4 border-b border-purple-200 pb-2">Outros Destaques do Período</h2>
      
      <div class="grid md:grid-cols-3 gap-4">
        <!-- Victor Brecheret -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-blue-200">
          <h3 class="font-semibold text-blue-800 mb-2">Victor Brecheret</h3>
          <p class="text-gray-700 text-sm mb-3">
            <span class="font-medium">Obra:</span> "Cabeça de Cristo" (1919-1920)
          </p>
          <div class="rounded-lg flex items-center justify-center ">
            <img class="h-50" src="../../../public/imagens/1bimestre/aula7/cabeça-cristo.png" alt="">
          </div>
        </div>
        
        <!-- Wilhelm Haarberg -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-indigo-200">
          <h3 class="font-semibold text-indigo-800 mb-2">Wilhelm Haarberg</h3>
          <p class="text-gray-700 text-sm mb-3">
            <span class="font-medium">Obra:</span> "Mãe e Filho"
          </p>
          <div class="rounded-lg flex items-center justify-center ">
            <img class="h-50" src="../../../public/imagens/1bimestre/aula7/mae-filho.png" alt="">
          </div>
        </div>
        
        <!-- John Graz -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-purple-200">
          <h3 class="font-semibold text-purple-800 mb-2">John Graz</h3>
          <p class="text-gray-700 text-sm mb-3">
            <span class="font-medium">Obra:</span> "Paisagem de Espanha (Ciprestes em Toledo)" (1916)
          </p>
          <div class="rounded-lg flex items-center justify-center ">
            <img class="w-full h-50" src="../../../public/imagens/1bimestre/aula7/paisagem-espanha.png" alt="">
          </div>
        </div>
      </div>
    </section>

    <!-- Evento Final -->
    <section class="bg-gradient-to-r from-purple-600 to-indigo-700 p-5 rounded-xl text-white text-center">
      <h2 class="text-2xl font-bold mb-3">Legado da Semana de 22</h2>
      <p class="mb-4 max-w-2xl mx-auto">
        A Semana de Arte Moderna lançou as bases para o desenvolvimento de uma arte genuinamente brasileira, 
        rompendo com as tradições acadêmicas e abrindo caminho para movimentos como a Antropofagia.
      </p>
      <div class="flex justify-center">
        <div class="bg-white/20 px-4 py-2 rounded-full text-sm">
          "O evento que redefiniu a cultura brasileira no século XX"
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";
</script>