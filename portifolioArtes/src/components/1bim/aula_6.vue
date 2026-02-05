<template>
  <div class="overflow-y bg-gradient-to-br from-blue-50 to-indigo-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-blue-100">
    <!-- Cabeçalho -->
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-indigo-600 to-purple-700 bg-clip-text text-transparent mb-3">
        Arthur Timótheo da Costa
      </h1>
      <h2 class="text-xl text-indigo-600 font-medium">Modernizando o Brasil</h2>
      <div class="h-1 w-24 bg-gradient-to-r from-indigo-400 to-purple-500 mx-auto rounded-full mt-4"></div>
    </header>

    <!-- Biografia -->
    <div class="grid md:grid-cols-3 gap-6 mb-8">
      <!-- Foto do artista -->
      <div class="md:col-span-1">
        <div class="bg-white p-4 rounded-xl shadow-sm border border-indigo-200 h-full">
          <img 
            src="../../../public/imagens/1bimestre/aula6/arthur-timotheo.png" 
            class="w-full h-64 object-cover rounded-lg shadow-md border border-indigo-100"
            alt="Arthur Timótheo da Costa">
          <p class="text-xs text-gray-500 mt-2 italic">Arthur Timótheo da Costa (1882-1922)</p>
        </div>
      </div>
      
      <!-- Dados biográficos -->
      <div class="md:col-span-2 bg-white p-5 rounded-xl shadow-sm border-l-4 border-indigo-400">
        <h2 class="text-xl font-semibold text-indigo-700 mb-3 flex items-center">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-indigo-500" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd" />
          </svg>
          Biografia
        </h2>
        
        <div class="space-y-4">
          <div>
            <h3 class="font-semibold text-indigo-800 mb-1">Nascimento e Família</h3>
            <p class="text-gray-700">Nasceu no Rio de Janeiro em 1882. Tinha mais oito irmãos, incluindo João Timóteo da Costa, que também se dedicou à arte.</p>
          </div>
          
          <div>
            <h3 class="font-semibold text-indigo-800 mb-1">Morte</h3>
            <p class="text-gray-700">Faleceu no asilo de alienados do Rio de Janeiro após a Semana de Arte Moderna de 1922, o mesmo local descrito por Lima Barreto em suas obras.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Educação e Formação -->
    <section class="mb-8 bg-gradient-to-r from-indigo-50 to-purple-50 p-5 rounded-xl border border-indigo-200">
      <h2 class="text-xl font-semibold text-indigo-800 mb-3 flex items-center">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-indigo-500" viewBox="0 0 20 20" fill="currentColor">
          <path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z" />
        </svg>
        Educação e Formação
      </h2>
      
      <div class="grid md:grid-cols-2 gap-4">
        <div class="bg-white p-4 rounded-lg shadow-sm">
          <p class="text-gray-700 mb-3">Em 1894, matriculou-se na Escola Nacional de Belas Artes.</p>
          <div class="border-t border-gray-200 pt-3">
            <h4 class="font-semibold text-2xl text-indigo-700 mb-1">Professores notáveis:</h4>
            <ul class="list-disc pl-5 text-[20px] text-gray-600" style="list-style: none;">
              <li>Daniel Bérard</li>
              <li>Zeferino da Costa</li>
              <li>Rodolfo Amoedo</li>
              <li>Henrique Bernardelli</li>
            </ul>
          </div>
        </div>
        
        <div class="bg-white p-4 rounded-lg shadow-sm flex flex-col">
          <img 
            src="../../../public/imagens/1bimestre/aula6/escola-belas-artes.png" 
            class="w-full h-50 object-cover rounded-lg mb-3"
            alt="Escola Nacional de Belas Artes">
          <p class="text-xs text-gray-500 italic">Escola Nacional de Belas Artes, Rio de Janeiro</p>
        </div>
      </div>
    </section>

    <!-- Carreira e Reconhecimento -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-purple-800 mb-4 border-b border-purple-200 pb-2">Carreira e Reconhecimento</h2>
      
      <div class="grid md:grid-cols-3 gap-4">
        <!-- Primeira Participação -->
        <div class="bg-gradient-to-br from-indigo-50 to-purple-50 p-4 rounded-xl border border-indigo-200">
          <div class="text-indigo-500 font-bold text-2xl mb-2">1905</div>
          <h3 class="font-semibold text-indigo-800 mb-2">Primeira Exposição</h3>
          <p class="text-gray-700 text-sm">Participou do Salão Geral de Belas-Artes pela primeira vez</p>
        </div>
        
        <!-- Prêmio Europa -->
        <div class="bg-gradient-to-br from-purple-50 to-indigo-50 p-4 rounded-xl border border-purple-200">
          <div class="text-purple-500 font-bold text-2xl mb-2">1907</div>
          <h3 class="font-semibold text-purple-800 mb-2">Prêmio de Viagem</h3>
          <p class="text-gray-700 text-sm">Venceu o prêmio de Viagem à Europa na Exposição Geral de Belas Artes</p>
        </div>
        
        <!-- Exposição Turim -->
        <div class="bg-gradient-to-br from-indigo-50 to-blue-50 p-4 rounded-xl border border-blue-200">
          <div class="text-blue-500 font-bold text-2xl mb-2">1911</div>
          <h3 class="font-semibold text-blue-800 mb-2">Exposição Internacional</h3>
          <p class="text-gray-700 text-sm">Convidado para o Pavilhão Brasileiro na Exposição de Turim</p>
        </div>
      </div>
    </section>

    <!-- Estilo Artístico -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow border border-indigo-200">
      <h2 class="text-[1.5em] font-semibold text-indigo-800 mb-3">Estilo Artístico</h2>
      
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-2/3 mt-[5%]">
          <blockquote class="border-l-4 border-indigo-500 pl-4 italic text-gray-700 mb-4">
            "As obras de Arthur Timóteo apresentam marcas do neo-impressionismo. Seu temperamento era vigoroso e suas pinceladas rudes e fulminantes."
            <footer class="mt-2 text-gray-600">- Gilda de Mello e Souza</footer>
          </blockquote>
          
          <div class="bg-indigo-50 p-4 rounded-lg">
            <h3 class="font-medium text-indigo-700 mb-2">Autorretrato (1908)</h3>
            <p class="text-gray-700 text-sm">Atualmente na Pinacoteca de São Paulo</p>
          </div>
        </div>
        
        <div class="md:w-1/3">
          <img 
            src="../../../public/imagens/1bimestre/aula6/autorretrato.png" 
            class="w-full h-70 object-cover rounded-lg shadow-md border border-indigo-100"
            alt="Autorretrato de Arthur Timótheo">
          <p class="text-xs text-gray-500 mt-2 italic">Autorretrato (1908) - Pinacoteca de São Paulo</p>
        </div>
      </div>
    </section>

    <!-- Obras Destacadas -->
    <section class="mb-8">
      <h2 class="text-xl font-semibold text-purple-800 mb-4 border-b border-purple-200 pb-2">Obras Destacadas</h2>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-5">
        <!-- Passeio Público -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-blue-200">
          <img 
            src="../../../public/imagens/1bimestre/aula6/passeio-publico.png" 
            class="w-full h-70 object-cover rounded-lg mb-3"
            alt="Passeio Público">
          <h3 class="font-semibold text-blue-800 mb-1">Passeio Público (1919)</h3>
          <p class="text-gray-700 text-sm">Óleo sobre tela</p>
        </div>
        
        <!-- Marinha -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-indigo-200">
          <img 
            src="../../../public/imagens/1bimestre/aula6/marinha.png" 
            class="w-full h-70 object-cover rounded-lg mb-3"
            alt="Marinha">
          <h3 class="font-semibold text-indigo-800 mb-1">Marinha (1919)</h3>
          <p class="text-gray-700 text-sm">Óleo sobre tela</p>
        </div>
        
        <!-- Estudo de Cabeças -->
        <div class="bg-white p-4 rounded-xl shadow-sm border border-purple-200">
          <img 
            src="../../../public/imagens/1bimestre/aula6/estudo-cabeças.png" 
            class="w-full h-70 object-cover rounded-lg mb-3"
            alt="Estudo de Quatro Cabeças">
          <h3 class="font-semibold text-purple-800 mb-1">Estudo de Quatro Cabeças</h3>
          <p class="text-gray-700 text-sm">Óleo sobre tela</p>
        </div>
      </div>
    </section>

    <!-- Contexto Histórico -->
    <section class="bg-gradient-to-r from-indigo-500 to-purple-600 p-5 rounded-xl text-white">
      <h2 class="text-xl font-bold mb-3">Contexto Histórico</h2>
      <p class="mb-4">
        Arthur Timótheo foi um dos artistas que ajudou a modernizar a arte brasileira no início do século XX, 
        transitando entre a tradição acadêmica e novas tendências artísticas.
      </p>
      
      <div class="flex items-center bg-indigo-400/30 p-4 rounded-lg border border-indigo-300">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
        <p>Viveu na transição entre o século XIX e XX, testemunhando as transformações que levariam à Semana de Arte Moderna de 1922</p>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";
</script>
