<template>
  <div class="overflow-y bg-gradient-to-br from-amber-50 to-orange-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-amber-100 text-left">
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-amber-600 to-orange-700 bg-clip-text text-transparent mb-3">
        Oficina de Serigrafia
      </h1>
      <h2 class="text-xl text-orange-600 font-medium">Da teoria à prática no laboratório de ciências</h2>
      <div class="h-1 w-24 bg-gradient-to-r from-amber-400 to-orange-500 mx-auto rounded-full mt-4"></div>
    </header>

    <!-- Introdução -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-amber-400">
      <h2 class="text-xl font-semibold text-amber-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-amber-500 rounded-full mr-2"></span>
        Contexto da Aula Prática
      </h2>
      <p class="text-gray-700">
        Nesta aula, saímos da teoria para a prática no laboratório de ciências. O objetivo foi aprender a confeccionar uma matriz de serigrafia, que é a base para a produção de gravuras em massa.
      </p>
    </section>

    <!-- 1. O Processo Técnico (Passo a Passo) -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-orange-800 mb-4 border-b border-orange-200 pb-2">
        1. O Processo Técnico (Passo a Passo)
      </h2>
      
      <div class="mb-6 bg-white p-5 rounded-xl shadow-sm border border-amber-200">
        <p class="text-gray-700 mb-4">
          O método utilizado foi a emulsão fotossensível, que utiliza a luz para "gravar" o desenho na tela:
        </p>
      </div>

      <div class="space-y-4 mb-6">
        <!-- Passo 1 -->
        <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-blue-400">
          <div class="flex items-start">
            <div class="w-8 h-8 bg-blue-100 text-blue-800 rounded-full flex items-center justify-center font-bold mr-3 flex-shrink-0">
              1
            </div>
            <div>
              <h3 class="font-semibold text-blue-800 mb-2">Criação do Fotolito</h3>
              <p class="text-gray-700 text-sm">
                Desenhos manuais em folha branca com pincel preto. O contraste do preto é essencial para bloquear a luz posteriormente.
              </p>
              <div class="mt-2 flex items-center text-sm text-blue-600">
                <span class="w-3 h-3 bg-blue-200 rounded-full mr-1"></span>
                <span>Material: Folha branca + pincel preto</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Passo 2 -->
        <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-green-400">
          <div class="flex items-start">
            <div class="w-8 h-8 bg-green-100 text-green-800 rounded-full flex items-center justify-center font-bold mr-3 flex-shrink-0">
              2
            </div>
            <div>
              <h3 class="font-semibold text-green-800 mb-2">Preparação da Tela</h3>
              <p class="text-gray-700 text-sm">
                Aplicação de uma mistura de cola com produto fotossensível por toda a superfície da matriz.
              </p>
              <div class="mt-2 flex items-center text-sm text-green-600">
                <span class="w-3 h-3 bg-green-200 rounded-full mr-1"></span>
                <span>Mistura: Cola + emulsão fotossensível</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Passo 3 -->
        <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-purple-400">
          <div class="flex items-start">
            <div class="w-8 h-8 bg-purple-100 text-purple-800 rounded-full flex items-center justify-center font-bold mr-3 flex-shrink-0">
              3
            </div>
            <div>
              <h3 class="font-semibold text-purple-800 mb-2">Secagem</h3>
              <p class="text-gray-700 text-sm">
                Uso de ar (adaptado com aspirador de pó) para fixar a emulsão na tela antes da exposição.
              </p>
              <div class="mt-2 flex items-center text-sm text-purple-600">
                <span class="w-3 h-3 bg-purple-200 rounded-full mr-1"></span>
                <span>Técnica: Aspirador adaptado para gerar fluxo de ar</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Passo 4 -->
        <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-amber-400">
          <div class="flex items-start">
            <div class="w-8 h-8 bg-amber-100 text-amber-800 rounded-full flex items-center justify-center font-bold mr-3 flex-shrink-0">
              4
            </div>
            <div>
              <h3 class="font-semibold text-amber-800 mb-2">Insolação (Exposição à Luz)</h3>
              <p class="text-gray-700 text-sm">
                A tela foi colocada sobre os desenhos em uma mesa de luz por exatos 2 minutos e 30 segundos. A luz endurece a cola onde não há desenho, enquanto a parte protegida pelo traçado preto permanece mole.
              </p>
              <div class="mt-2 flex items-center text-sm text-amber-600">
                <span class="w-3 h-3 bg-amber-200 rounded-full mr-1"></span>
                <span>Tempo: 2 minutos e 30 segundos exatos</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Passo 5 -->
        <div class="bg-white p-4 rounded-xl shadow-sm border-l-4 border-red-400">
          <div class="flex items-start">
            <div class="w-8 h-8 bg-red-100 text-red-800 rounded-full flex items-center justify-center font-bold mr-3 flex-shrink-0">
              5
            </div>
            <div>
              <h3 class="font-semibold text-red-800 mb-2">Revelação</h3>
              <p class="text-gray-700 text-sm">
                Lavagem da tela com água para remover a cola das áreas do desenho, fazendo com que a imagem apareça vazada na matriz.
              </p>
              <div class="mt-2 flex items-center text-sm text-red-600">
                <span class="w-3 h-3 bg-red-200 rounded-full mr-1"></span>
                <span>Processo: Lavagem com água para revelar a imagem</span>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="bg-gradient-to-r from-amber-500 to-orange-600 p-5 rounded-xl text-white">
        <div class="flex items-center mb-3">
          <div class="w-10 h-10 bg-white/20 rounded-full flex items-center justify-center mr-3">
            <span class="text-xl">🎯</span>
          </div>
          <h3 class="text-lg font-bold">Objetivo da Aula</h3>
        </div>
        <p class="text-sm">
          A aula essencialmente foi para nos ensinar como fazer uma matriz a partir de nossos próprios desenhos. Mas somente na próxima aula que faríamos todo esse processo e colaríamos os desenhos feitos na matriz na parede.
        </p>
      </div>
    </section>

    <!-- Materiais Utilizados -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-orange-800 mb-4 border-b border-orange-200 pb-2">
        Materiais Utilizados
      </h2>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-4 mb-4">
        <div class="bg-white p-4 rounded-xl shadow-sm border border-amber-200 text-center">
          <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-3">
            <span class="text-amber-600 text-xl">🖌️</span>
          </div>
          <h3 class="font-semibold text-amber-800 mb-1">Desenho</h3>
          <p class="text-xs text-gray-600">Folha branca e pincel preto</p>
        </div>
        
        <div class="bg-white p-4 rounded-xl shadow-sm border border-blue-200 text-center">
          <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-3">
            <span class="text-blue-600 text-xl">🖼️</span>
          </div>
          <h3 class="font-semibold text-blue-800 mb-1">Matriz</h3>
          <p class="text-xs text-gray-600">Tela de serigrafia</p>
        </div>
        
        <div class="bg-white p-4 rounded-xl shadow-sm border border-green-200 text-center">
          <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-3">
            <span class="text-green-600 text-xl">🧪</span>
          </div>
          <h3 class="font-semibold text-green-800 mb-1">Emulsão</h3>
          <p class="text-xs text-gray-600">Cola + produto fotossensível</p>
        </div>
        
        <div class="bg-white p-4 rounded-xl shadow-sm border border-purple-200 text-center">
          <div class="w-12 h-12 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-3">
            <span class="text-purple-600 text-xl">💡</span>
          </div>
          <h3 class="font-semibold text-purple-800 mb-1">Iluminação</h3>
          <p class="text-xs text-gray-600">Mesa de luz</p>
        </div>
      </div>
    </section>

    <!-- Princípio Científico -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-blue-400">
      <h2 class="text-xl font-semibold text-blue-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-blue-500 rounded-full mr-2"></span>
        Princípio Científico Aplicado
      </h2>
      
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-1/3 mb-4 md:mb-0 md:pr-6 text-center">
          <div class="w-24 h-24 bg-gradient-to-r from-blue-100 to-indigo-100 rounded-full flex items-center justify-center mx-auto">
            <span class="text-3xl text-blue-600">🔬</span>
          </div>
        </div>
        <div class="md:w-2/3">
          <h3 class="font-semibold text-blue-800 mb-2">Fotossensibilidade</h3>
          <p class="text-gray-700 mb-3">
            A emulsão fotossensível reage à luz ultravioleta, endurecendo quando exposta. As áreas protegidas pelo desenho preto permanecem solúveis em água, permitindo a criação da matriz.
          </p>
          <div class="bg-blue-50 p-3 rounded-lg">
            <p class="text-sm text-blue-800">
              <span class="font-medium">Processo:</span> Exposição à luz → Polimerização → Lavagem com água → Revelação da imagem
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Próxima Aula -->
    <section class="mb-8 bg-gradient-to-r from-orange-100 to-amber-100 p-5 rounded-xl border border-amber-200">
      <h2 class="text-xl font-semibold text-orange-800 mb-3 flex items-center">
        <span class="w-3 h-3 bg-orange-500 rounded-full mr-2"></span>
        Continuidade na Próxima Aula
      </h2>
      
      <div class="flex items-start">
        <div class="w-10 h-10 bg-orange-200 rounded-full flex items-center justify-center mr-3 flex-shrink-0">
          <span class="text-orange-700 font-bold">→</span>
        </div>
        <div>
          <p class="text-gray-700 mb-2">
            Na próxima aula, completaremos o processo aplicando a tinta através da matriz revelada e transferindo nossos desenhos para a parede, finalizando assim a técnica de serigrafia.
          </p>
          <div class="flex items-center text-sm text-orange-700">
            <span class="w-2 h-2 bg-orange-500 rounded-full mr-2"></span>
            <span>Próxima etapa: Aplicação de tinta e impressão</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Reflexão Final -->
    <section class="flex flex-col items-center bg-white max-w-[750px] p-6 rounded-2xl shadow border border-amber-200 mt-6 mx-auto">
      <div class="text-center mb-6">
        <h2 class="text-2xl md:text-3xl font-bold text-orange-700 mb-2">Aprendizado Prático</h2>
        <div class="h-1 w-32 bg-gradient-to-r from-amber-400 to-orange-500 mx-auto rounded-full mt-1"></div>
        <p class="text-gray-700 mt-4 max-w-2xl mx-auto">
          Como a experiência prática de criar uma matriz de serigrafia complementa o aprendizado teórico sobre técnicas de reprodução artística?
        </p>
      </div>

      <div class="relative w-full max-w-xl mx-auto rounded-xl overflow-hidden shadow-md border border-gray-100">
        <div class="bg-gradient-to-r from-amber-100 to-orange-100 p-8 rounded-xl">
          <div class="text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 mx-auto text-orange-500 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z" />
            </svg>
            <p class="text-lg font-semibold text-gray-800 mb-4">
              A prática de criar uma matriz de serigrafia nos permite compreender fisicamente processos que antes eram apenas conceitos teóricos. Cada etapa - do desenho do fotolito à revelação da matriz - demonstra como a arte se conecta com princípios científicos, como a fotossensibilidade, e como técnicas tradicionais continuam relevantes na era digital.
            </p>
            <div class="mt-6 pt-4 border-t border-orange-300">
              <p class="text-sm text-gray-600 italic">
                "Aprender fazendo transforma conceitos abstratos em conhecimento concreto e memorável."
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
// Componente Vue.js para a aula prática de Serigrafia
// Descrição do processo de criação de matriz com emulsão fotossensível
</script>