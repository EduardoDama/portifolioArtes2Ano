<template>
  <div class="overflow-y bg-gradient-to-br from-blue-50 to-indigo-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-blue-100 text-left">
    <!-- Cabeçalho -->
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-blue-600 to-indigo-700 bg-clip-text text-transparent mb-3">
        Modernizando o Brasil
      </h1>
      <h2 class="text-xl text-indigo-600 font-medium">A Arte Acadêmica e a Construção da Nação no Século XIX</h2>
      <div class="h-1 w-24 bg-gradient-to-r from-blue-400 to-indigo-500 mx-auto rounded-full mt-4"></div>
    </header>
    
    <!-- Resumo da Aula -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-indigo-400">
      <h2 class="text-xl font-semibold text-indigo-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-indigo-500 rounded-full mr-2"></span>
        O que vimos na aula?
      </h2>
      <p class="text-gray-700">
        A aula explorou a arte académica brasileira da segunda metade do século XIX, destacando a pintura histórica e as novas direções influenciadas pelo impressionismo, culminando na ruptura do modernismo com Anita Malfatti e a crítica de Monteiro Lobato
      </p>
    </section>

    <!-- Pedro Américo -->
    <section class="mb-8">
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-1/2 bg-gradient-to-br from-blue-50 to-indigo-50 p-5 rounded-xl border border-blue-200">
          <h3 class="text-xl font-semibold text-blue-800 mb-3 flex items-center">
            <span class="w-3 h-3 bg-blue-500 rounded-full mr-2"></span>
            Pedro Américo (1843-1905)
          </h3>
          <ul class="list-disc pl-5 text-gray-700 space-y-2 mb-4">
            <li>"Pintor oficial do Império" - apoiado pela família imperial</li>
            <li>Formação na Escola de Belas Artes de Paris</li>
            <li>Obras monumentais: <span class="font-medium">4-11m de comprimento</span></li>
            <li>Debate sobre posição política (monarquista vs republicano)</li>
          </ul>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <div class="bg-white p-3 rounded-lg border border-blue-200">
              <h4 class="font-medium text-blue-700 mb-1">Independência ou morte</h4>
              <p class="text-sm text-gray-600">1888 (4,15x7,60m)</p>
            </div>
            <div class="bg-white p-3 rounded-lg border border-blue-200">
              <h4 class="font-medium text-blue-700 mb-1">Batalha do Avaí</h4>
              <p class="text-sm text-gray-600">1872-1877 (6x11m)</p>
            </div>
            <div class="md:col-span-2 bg-white p-3 rounded-lg border border-blue-200">
              <h4 class="font-medium text-blue-700 mb-1">Tiradentes esquartejado</h4>
              <p class="text-sm text-gray-600">1893 - "Visão da violência sobre o corpo"</p>
            </div>
          </div>
        </div>
        
        <div class="md:w-1/2">
          <div class="h-full">
            <img 
              src="../../../public/imagens/1bimestre/aula4/img1.png" 
              class="w-full h-64 object-cover rounded-xl shadow-md border border-blue-200"
              alt="Obra de Pedro Américo">
            <p class="text-xs text-gray-500 mt-2 italic">"Independência ou Morte" (1888) - Pedro Américo</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Victor Meireles -->
    <section class="mb-8 bg-gradient-to-r from-indigo-500 to-purple-600 p-5 rounded-xl text-white">
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-1/2">
          <h3 class="text-xl font-bold mb-3 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
            </svg>
            Victor Meireles (1832-1903)
          </h3>
          <ul class="list-disc pl-5 space-y-2 mb-4">
            <li>Nascido em Nossa Senhora do Desterro (Florianópolis)</li>
            <li>Estudou na AIBA e conquistou Prêmio de Viagem à Europa</li>
            <li>Formação na Itália e França</li>
            <li>Primeiro artista brasileiro em mostra internacional</li>
          </ul>
          
          <div class="bg-indigo-400/30 p-4 rounded-lg border border-indigo-300">
            <h4 class="font-bold mb-2">Primeira Missa no Brasil</h4>
            <p class="text-sm mb-2">Aceita no Salão Oficial de Paris (1861)</p>
            <p class="text-sm italic">"Mito fundador que obscurece confrontos da colonização"</p>
          </div>
        </div>
        
        <div class="md:w-1/2">
          <div class="h-full">
            <img 
              src="../../../public/imagens/1bimestre/aula4/img2.png" 
              class="w-full h-64 object-cover rounded-xl shadow-md border border-indigo-300"
              alt="Primeira Missa no Brasil por Victor Meireles">
            <p class="text-xs text-indigo-200 mt-2 italic">"Primeira Missa no Brasil" (1861) - Victor Meireles</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Novas Direções -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-purple-800 mb-4 border-b border-purple-200 pb-2">Novas Direções no Final do Século XIX</h2>
      <p class="text-gray-700 mb-4">
        Artistas que viajaram para a Europa entraram em contato com movimentos como Impressionismo e Pontilhismo.
      </p>
      
      <div class="grid md:grid-cols-3 gap-4">
        <!-- Almeida Júnior -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-blue-200">
          <h3 class="font-semibold text-blue-800 mb-2">Almeida Júnior</h3>
          <p class="text-gray-700 text-sm mb-2">
            <span class="font-medium">Obra:</span> "O violeiro" (1899)
          </p>
          <p class="text-gray-700 text-xs italic mb-3">
            "Tema regionalista mostrando costumes afáveis das pessoas simples"
          </p>
          <div class="mt-3">
            <img 
              src="../../../public/imagens/1bimestre/aula4/img5.png" 
              class="w-full h-40 object-cover rounded-lg shadow-sm border border-gray-200"
              alt="O violeiro por Almeida Júnior">
            <p class="text-xs text-gray-500 mt-2 italic">"O violeiro" (1899) - Almeida Júnior</p>
          </div>
        </div>
        
        <!-- Belmiro de Almeida -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-indigo-200">
          <h3 class="font-semibold text-indigo-800 mb-2">Belmiro de Almeida</h3>
          <p class="text-gray-700 text-sm mb-2">
            <span class="font-medium">Obra:</span> "Efeitos do sol" (1892)
          </p>
          <div class="mt-3">
            <img 
              src="../../../public/imagens/1bimestre/aula4/img6.png" 
              class="w-full h-40 object-cover rounded-lg shadow-sm border border-gray-200"
              alt="Efeitos do sol por Belmiro de Almeida">
            <p class="text-xs text-gray-500 mt-2 italic">"Efeitos do sol" (1892) - Belmiro de Almeida</p>
          </div>
        </div>
        
        <!-- Eliseu Visconti -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-purple-200">
          <h3 class="font-semibold text-purple-800 mb-2">Eliseu Visconti</h3>
          <p class="text-gray-700 text-sm mb-2">
            <span class="font-medium">Obra:</span> "Trigal" (1913-1916)
          </p>
          <p class="text-gray-700 text-xs italic mb-3">
            "Cena ao ar livre com influência impressionista, ausência de contornos nítidos"
          </p>
          <div class="mt-3">
            <img 
              src="../../../public/imagens/1bimestre/aula4/img7.png" 
              class="w-full h-40 object-cover rounded-lg shadow-sm border border-gray-200"
              alt="Trigal por Eliseu Visconti">
            <p class="text-xs text-gray-500 mt-2 italic">"Trigal" (1913-1916) - Eliseu Visconti</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Modernismo -->
    <section class="mb-8 bg-gradient-to-r from-purple-500 to-indigo-600 p-5 rounded-xl text-white">
      <h2 class="text-xl font-bold mb-4">O Início do Modernismo e a Ruptura</h2>
      
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-1/2">
          <h3 class="text-lg font-bold mb-3 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M12.316 3.051a1 1 0 01.633 1.265l-4 12a1 1 0 11-1.898-.632l4-12a1 1 0 011.265-.633zM5.707 6.293a1 1 0 010 1.414L3.414 10l2.293 2.293a1 1 0 11-1.414 1.414l-3-3a1 1 0 010-1.414l3-3a1 1 0 011.414 0zm8.586 0a1 1 0 011.414 0l3 3a1 1 0 010 1.414l-3 3a1 1 0 11-1.414-1.414L16.586 10l-2.293-2.293a1 1 0 010-1.414z" clip-rule="evenodd" />
            </svg>
            Anita Malfatti (1889-1964)
          </h3>
          
          <div class="bg-purple-400/30 p-4 rounded-lg border border-purple-300 mb-4">
            <p class="mb-2">"Exposição de pintura moderna" (1917) - marco do modernismo brasileiro</p>
            <p class="text-sm">Proposta de mudanças significativas na arte brasileira</p>
          </div>
          
          <ul class="list-disc pl-5 space-y-2">
            <li>Estudos na Alemanha e Estados Unidos</li>
            <li>Distanciamento da arte acadêmica e herança neoclássica</li>
            <li>Obra destacada: "O Homem Amarelo" (1915-16)</li>
            <li>Exposição teve grande repercussão e duras críticas</li>
          </ul>
        </div>
        
        <div class="md:w-1/2 bg-white p-4 rounded-lg text-gray-800">
          <h3 class="text-lg font-semibold text-purple-800 mb-3 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-red-500" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7 4a1 1 0 11-2 0 1 1 0 012 0zm-1-9a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z" clip-rule="evenodd" />
            </svg>
            A Crítica de Monteiro Lobato
          </h3>
          <p class="italic mb-3">"Paranoia ou mistificação?" - O Estado de São Paulo (20/12/1917)</p>
          
          <div class="space-y-3">
            <div class="flex items-start">
              <span class="bg-red-100 text-red-800 px-2 py-1 rounded mr-2 text-sm">✘</span>
              <p class="text-sm">Associa tendências a "extravagâncias de Picasso e companhia"</p>
            </div>
            
            <div class="flex items-start">
              <span class="bg-red-100 text-red-800 px-2 py-1 rounded mr-2 text-sm">✘</span>
              <p class="text-sm">Distingue artistas que "vêem normalmente" (arte pura) dos que "vêem anormalmente"</p>
            </div>
            
            <div class="flex items-start">
              <span class="bg-red-100 text-red-800 px-2 py-1 rounded mr-2 text-sm">✘</span>
              <p class="text-sm">Considera vanguardas como "ramos da arte caricatural"</p>
            </div>
          </div>
          
          <div class="mt-4 p-3 bg-gray-100 rounded-lg border border-gray-300">
            <p class="text-xs italic">"Futurismo, cubismo, impressionismo e tutti quanti não passam de outros tantos ramos da arte caricatural"</p>
          </div>
        </div>
      </div>
    </section>

    <!-- O Homem Amarelo -->
    <section class="bg-white p-5 rounded-xl shadow border border-indigo-200">
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-1/3">
          <img 
            src="../../../public/imagens/1bimestre/aula4/img8.png" 
            class="w-full h-64 object-cover rounded-xl shadow-md border border-indigo-200"
            alt="O Homem Amarelo por Anita Malfatti">
          <p class="text-xs text-gray-500 mt-2 italic">"O Homem Amarelo" (1915-16) - Anita Malfatti</p>
        </div>
        
        <div class="md:w-2/3">
          <h3 class="text-xl font-semibold text-indigo-800 mb-3">O Homem Amarelo (1915-16)</h3>
          <p class="text-gray-700 mb-4">
            Obra emblemática de Anita Malfatti que sintetiza a ruptura com a tradição acadêmica e a adoção das vanguardas europeias.
          </p>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <div class="bg-indigo-50 p-3 rounded-lg border border-indigo-200">
              <h4 class="font-medium text-indigo-700 mb-1">Técnica</h4>
              <p class="text-sm">Óleo sobre tela</p>
            </div>
            <div class="bg-indigo-50 p-3 rounded-lg border border-indigo-200">
              <h4 class="font-medium text-indigo-700 mb-1">Influências</h4>
              <p class="text-sm">Expressionismo alemão</p>
            </div>
            <div class="md:col-span-2 bg-blue-50 p-3 rounded-lg border border-blue-200">
              <h4 class="font-medium text-blue-700 mb-1">Significado</h4>
              <p class="text-sm">Símbolo da revolução modernista no Brasil</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>