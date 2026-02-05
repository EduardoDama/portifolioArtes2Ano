<template>
  <div class="overflow-y bg-gradient-to-br from-amber-50 to-orange-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-amber-100">
    <!-- Cabeçalho -->
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-amber-600 to-orange-700 bg-clip-text text-transparent mb-3">
        Nossos Antepassados
      </h1>
      <div class="h-1 w-24 bg-gradient-to-r from-amber-400 to-orange-500 mx-auto rounded-full"></div>
    </header>

    <!-- Resumo da Aula -->
    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-amber-400">
      <h2 class="text-xl font-semibold text-amber-700 mb-3 flex items-center">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
          <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd" />
        </svg>
        O que foi visto?
      </h2>
      <p class="text-gray-700">
        Nessa aula minha turma teve a oportunidade de falar um pouco da história da família de cada um, explorando nossos antepassados e tentando entender um pouco sobre cada um.
      </p>
    </section>

    <!-- Processo -->
    <section class="mb-8">
      <div class="flex flex-col md:flex-row gap-6 items-center">
        <div class="md:w-1/3">
          <div class="bg-amber-100 rounded-full p-4 w-48 h-48 mx-auto flex items-center justify-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-24 w-24 text-amber-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>
          </div>
        </div>
        
        <div class="md:w-2/3 bg-white p-5 rounded-xl shadow-sm border-l-4 border-orange-400">
          <h2 class="text-xl font-semibold text-orange-700 mb-3 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
            </svg>
            Processo
          </h2>
          <p class="text-gray-700">
            Fomos para a sala de metrologia e organizamos as cadeiras em círculo, onde todos podiam se ver. Essa disposição facilitou a visualização e a conexão quando cada pessoa compartilhava sua história.
          </p>
        </div>
      </div>
    </section>

    <!-- Minha História -->
    <section class="mb-8 bg-gradient-to-r from-amber-500 to-orange-600 p-5 rounded-xl text-white">
      <div class="flex flex-col md:flex-row gap-6">
        <div class="md:w-2/3">
          <h2 class="text-2xl font-bold mb-3 flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
            </svg>
            Minha História
          </h2>
          
          <div class="bg-amber-400/30 p-4 rounded-lg border border-amber-300 mb-4">
            <p class="mb-3">Cada um compartilhou sua história familiar. Alguns conseguiram traçar longas linhagens, outros histórias mais recentes, mas todos contribuíram com suas origens.</p>
          </div>
          
          <ul class="list-disc pl-5 space-y-2">
            <li>Comecei pela história da família paterna</li>
            <li>Conheço melhor a história materna</li>
            <li>Compartilhei a trajetória de meus avós</li>
            <li>As dificuldades que enfrentaram para sustentar a família</li>
          </ul>
        </div>
        
        <div class="md:w-1/3 flex items-center justify-center">
          <div class="relative">
            <div class="bg-white/20 rounded-full w-40 h-40 flex items-center justify-center border-2 border-white">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
              </svg>
            </div>
            <div class="absolute -top-2 -left-2 bg-amber-200 rounded-full w-16 h-16"></div>
            <div class="absolute -bottom-2 -right-2 bg-amber-300 rounded-full w-16 h-16"></div>
          </div>
        </div>
      </div>
    </section>

    <!-- Conclusão -->
    <section class="mb-6 bg-white p-5 rounded-xl shadow">
      <h2 class="text-xl font-semibold text-amber-800 mb-3">Aprendizados</h2>
      <p class="text-gray-700 mb-4">
        Através desse círculo de histórias, conseguimos entender melhor nossas origens e criar conexões mais profundas com nossos colegas.
      </p>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="bg-amber-50 p-4 rounded-lg border border-amber-200">
          <h3 class="font-medium text-amber-700 mb-1">Diversidade</h3>
          <p class="text-sm">Cada história familiar única e especial</p>
        </div>
        <div class="bg-amber-50 p-4 rounded-lg border border-amber-200">
          <h3 class="font-medium text-amber-700 mb-1">Resiliência</h3>
          <p class="text-sm">Superação de desafios pelas gerações anteriores</p>
        </div>
        <div class="bg-amber-50 p-4 rounded-lg border border-amber-200">
          <h3 class="font-medium text-amber-700 mb-1">Entendimento</h3>
          <p class="text-sm">Sobre o passado que parece distante, mas não é.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";
</script>