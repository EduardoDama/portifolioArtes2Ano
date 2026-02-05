<template>
  <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-2xl shadow-xl p-6 md:p-8 w-full border border-blue-100 text-left">
    <header class="mb-8 text-center">
      <h1 class="text-3xl md:text-4xl font-bold bg-gradient-to-r from-blue-600 to-indigo-700 bg-clip-text text-transparent mb-3">
        Filme Barravento
      </h1>
      <h2 class="text-xl text-indigo-600 font-medium">Um filme de Glauber Rocha</h2>
      <div class="h-1 w-24 bg-gradient-to-r from-blue-400 to-indigo-500 mx-auto rounded-full mt-4"></div>
    </header>

    <section class="mb-8 bg-white p-5 rounded-xl shadow-sm border-l-4 border-indigo-400">
      <h2 class="text-xl font-semibold text-indigo-700 mb-3 flex items-center">
        <span class="w-3 h-3 bg-indigo-500 rounded-full mr-2"></span>
        Sobre o Filme: Um Marco do Cinema Novo
      </h2>
      <p class="text-gray-700 mb-4">
Nesse dia o professor nos levou ao auditório para assistir o filme "Barravento", de Glauber Rocha, de 1962. O enredo acompanha o retorno de Firmino à sua vila de pescadores na Bahia, após uma temporada na cidade grande      </p>
      <p class="text-gray-700">
Firmino, influenciado por ideias modernas, tenta convencer a comunidade a abandonar o Candomblé, que ele acredita ser a causa da miséria local. O filme retrata o choque entre sua visão mais nova e a fé dos pescadores, que veem o mar, ou "barravento", como uma entidade sagrada que comanda suas vidas.      </p>
    
        <div class="mt-6 grid grid-cols-2 md:grid-cols-2 gap-4">
            <img src="../../../public/imagens/2bimestre/aula2/img1.jpg" alt="" class="w-full h-auto rounded-lg border border-blue-200">
            <img src="../../../public/imagens/2bimestre/aula2/img2.png" alt="" class="w-full h-auto rounded-lg border border-blue-200">
        </div>
</section>

    <section class="mb-8 bg-gradient-to-r from-indigo-500 to-purple-600 p-5 rounded-xl text-white">
      <h2 class="text-xl font-bold mb-4">Conflito entre Tradição e Modernidade</h2>
      <p class="mb-4">
        Glauber Rocha aborda o conflito entre o moderno e o arcaico. É uma narrativa visualmente marcante:
      </p>
      <ul class="list-disc pl-5 space-y-2 mb-4">
        <li>
          Estética Visual: Com longas cenas de rituais e paisagens, o diretor utiliza uma estética que ressalta a força da cultura local.
        </li>
        <li>
          Luta Interna e Externa: O filme mostra a luta de um homem contra as crenças de sua própria comunidade e a impossibilidade de impor uma nova realidade sem entender a complexidade de suas raízes. 
        </li>
      </ul>
    </section>

    <section class="bg-white p-5 rounded-xl shadow border border-indigo-200">
      <div class="flex flex-col md:flex-row gap-6 items-center">
        <div class="md:w-2/3">
          <h3 class="text-xl font-semibold text-indigo-800 mb-3">Legado: Metáfora de um País</h3>
          <p class="text-gray-700 mb-4">
            "Barravento" não é apenas um filme sobre pescadores; é uma poderosa metáfora sobre a alienação, a colonização cultural e a busca por identidade em um país de tantas contradições.
          </p>
          <div class="bg-blue-50 p-3 rounded-lg border border-blue-200">
            <h4 class="font-medium text-blue-700 mb-1">Crítica e Celebração</h4>
            <p class="text-sm">É uma crítica contundente ao sistema que mantém os pobres na marginalidade, mas, ao mesmo tempo, uma celebração vibrante da riqueza cultural e da resistência do povo brasileiro.</p>
          </div>
        </div>
        <div class="md:w-1/3 text-center hidden md:block">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-24 w-24 mx-auto text-indigo-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z" />
          </svg>
        </div>
      </div>
    </section>

  </div>
</template>

<script setup>
// Este é um componente estático, então não é necessário um script complexo.
// Apenas a estrutura básica do <script setup> para conformidade com o Vue 3.
</script>
