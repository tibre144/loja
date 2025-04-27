<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Viena Racing</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-black text-white font-sans">

  <!-- Header -->
  <header class="bg-red-600 p-4 flex justify-between items-center">
    <h1 class="text-3xl font-bold">Viena Racing</h1>
    <nav class="space-x-4">
      <a href="#home" class="hover:underline">Home</a>
      <a href="#produtos" class="hover:underline">Produtos</a>
      <a href="#sobre" class="hover:underline">Sobre</a>
      <a href="#contato" class="hover:underline">Contato</a>
      <a href="#carrinho" class="hover:underline">Carrinho</a>
    </nav>
  </header>

  <!-- Home -->
  <section id="home" class="text-center py-20 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1549924231-f129b911e442');">
    <div class="bg-black bg-opacity-50 p-10">
      <h2 class="text-4xl font-bold mb-4">Performance em Cada Detalhe</h2>
      <p class="text-xl">Os melhores produtos para seu carro de corrida.</p>
    </div>
  </section>

  <!-- Produtos -->
  <section id="produtos" class="py-20 px-8">
    <h2 class="text-3xl font-bold text-center mb-12">Nossos Produtos</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

      <!-- Produto exemplo -->
      <div class="bg-white text-black p-6 rounded-lg shadow-lg">
        <img src="https://via.placeholder.com/300x200" alt="Produto 1" class="rounded mb-4">
        <h3 class="text-2xl font-semibold mb-2">Pneu de Alta Performance</h3>
        <p class="mb-4">Durabilidade e aderência para pistas e estradas.</p>
        <button class="bg-red-600 text-white px-4 py-2 rounded hover:bg-red-700">Adicionar ao Carrinho</button>
      </div>

      <div class="bg-white text-black p-6 rounded-lg shadow-lg">
        <img src="https://via.placeholder.com/300x200" alt="Produto 2" class="rounded mb-4">
        <h3 class="text-2xl font-semibold mb-2">Kit de Suspensão Esportiva</h3>
        <p class="mb-4">Melhore o desempenho e a estabilidade do seu carro.</p>
        <button class="bg-red-600 text-white px-4 py-2 rounded hover:bg-red-700">Adicionar ao Carrinho</button>
      </div>

      <div class="bg-white text-black p-6 rounded-lg shadow-lg">
        <img src="https://via.placeholder.com/300x200" alt="Produto 3" class="rounded mb-4">
        <h3 class="text-2xl font-semibold mb-2">Freios de Alta Performance</h3>
        <p class="mb-4">Segurança máxima com tecnologia de ponta.</p>
        <button class="bg-red-600 text-white px-4 py-2 rounded hover:bg-red-700">Adicionar ao Carrinho</button>
      </div>

    </div>
  </section>

  <!-- Sobre -->
  <section id="sobre" class="py-20 px-8 bg-gray-900">
    <h2 class="text-3xl font-bold text-center mb-12">Sobre a Viena Racing</h2>
    <div class="max-w-4xl mx-auto text-center">
      <p class="text-lg">Com anos de experiência no mercado automobilístico, a Viena Racing é referência em qualidade e performance. Nosso objetivo é levar o melhor para você e seu carro, garantindo segurança, velocidade e inovação.</p>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="py-20 px-8">
    <h2 class="text-3xl font-bold text-center mb-12">Contato</h2>
    <div class="max-w-2xl mx-auto">
      <form class="space-y-6">
        <input type="text" placeholder="Nome" class="w-full p-3 rounded bg-gray-800 text-white">
        <input type="email" placeholder="Email" class="w-full p-3 rounded bg-gray-800 text-white">
        <textarea placeholder="Mensagem" class="w-full p-3 rounded bg-gray-800 text-white" rows="5"></textarea>
        <button type="submit" class="bg-red-600 px-6 py-3 rounded text-white hover:bg-red-700">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-center py-6">
    <p>&copy; 2025 Viena Racing - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
