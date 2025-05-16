<html class="scroll-smooth" lang="pt-BR">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Nossa Escolha - Loja de Moda
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&amp;display=swap" rel="stylesheet"/>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Poppins', sans-serif;
    }
  </style>
 </head>
 <body class="bg-gray-50 text-gray-800">
  <!-- Header / Navbar -->
  <header class="bg-white shadow sticky top-0 z-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
     <a class="flex items-center space-x-2" href="#">
      <img alt="Logo Nossa Escolha estilizado com as letras NE em branco sobre fundo vermelho" class="h-10 w-10 rounded-full" height="40" src="https://storage.googleapis.com/a1aa/image/11518747-63ad-4ea6-e1e6-cf2647d7fa4d.jpg" width="40"/>
      <span class="text-2xl font-bold text-red-600">
       Nossa Escolha
      </span>
     </a>
     <nav class="hidden md:flex space-x-8 font-semibold text-gray-700">
      <a class="hover:text-red-600 transition" href="#">
       Mulheres
      </a>
      <a class="hover:text-red-600 transition" href="#">
       Homens
      </a>
      <a class="hover:text-red-600 transition" href="#">
       Acessórios
      </a>
      <a class="hover:text-red-600 transition" href="#">
       Promoções
      </a>
      <a class="hover:text-red-600 transition" href="#">
       Novidades
      </a>
     </nav>
     <div class="flex items-center space-x-4">
      <button aria-label="Buscar produtos" class="text-gray-600 hover:text-red-600 transition focus:outline-none">
       <i class="fas fa-search fa-lg">
       </i>
      </button>
      <button aria-label="Favoritos" class="text-gray-600 hover:text-red-600 transition focus:outline-none relative">
       <i class="fas fa-heart fa-lg">
       </i>
       <span class="absolute -top-1 -right-2 bg-red-600 text-white text-xs rounded-full px-1.5">
        3
       </span>
      </button>
      <button aria-label="Carrinho de compras" class="text-gray-600 hover:text-red-600 transition focus:outline-none relative">
       <i class="fas fa-shopping-cart fa-lg">
       </i>
       <span class="absolute -top-1 -right-2 bg-red-600 text-white text-xs rounded-full px-1.5">
        5
       </span>
      </button>
      <button aria-label="Menu mobile" class="md:hidden text-gray-600 hover:text-red-600 transition focus:outline-none" id="mobile-menu-button">
       <i class="fas fa-bars fa-lg">
       </i>
      </button>
     </div>
    </div>
   </div>
   <!-- Mobile menu -->
   <nav aria-label="Menu mobile" class="hidden md:hidden bg-white border-t border-gray-200" id="mobile-menu">
    <a class="block px-4 py-3 text-gray-700 font-semibold hover:bg-red-50 hover:text-red-600" href="#">
     Mulheres
    </a>
    <a class="block px-4 py-3 text-gray-700 font-semibold hover:bg-red-50 hover:text-red-600" href="#">
     Homens
    </a>
    <a class="block px-4 py-3 text-gray-700 font-semibold hover:bg-red-50 hover:text-red-600" href="#">
     Acessórios
    </a>
    <a class="block px-4 py-3 text-gray-700 font-semibold hover:bg-red-50 hover:text-red-600" href="#">
     Promoções
    </a>
    <a class="block px-4 py-3 text-gray-700 font-semibold hover:bg-red-50 hover:text-red-600" href="#">
     Novidades
    </a>
   </nav>
  </header>
  <!-- Hero Section -->
  <section class="relative bg-white max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mt-8 rounded-lg shadow-md overflow-hidden">
   <div class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center py-12">
    <div class="space-y-6">
     <h1 class="text-4xl sm:text-5xl font-extrabold text-red-600 leading-tight">
      Nossa Escolha
      <br/>
      Moda que inspira você
     </h1>
     <p class="text-gray-600 text-lg max-w-md">
      Descubra as últimas tendências em roupas, calçados e acessórios com
          preços incríveis em Kz.
     </p>
     <a class="inline-block bg-red-600 text-white px-6 py-3 rounded-md font-semibold hover:bg-red-700 transition" href="#produtos">
      Comprar Agora
     </a>
    </div>
    <div class="flex justify-center">
     <img alt="Mulher jovem vestindo roupa moderna e colorida, posando em fundo claro minimalista" class="rounded-lg shadow-lg w-full max-w-md object-cover" height="500" src="https://storage.googleapis.com/a1aa/image/1b405623-1bd5-453c-3679-c4c74afc4b59.jpg" width="500"/>
    </div>
   </div>
  </section>
  <!-- Categories Section -->
  <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mt-12">
   <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">
    Categorias Populares
   </h2>
   <div aria-label="Categorias de produtos" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-6 text-center">
    <a class="group block bg-white rounded-lg shadow hover:shadow-lg transition p-4" href="#">
     <img alt="Vestidos femininos variados em manequins, fundo branco" class="mx-auto mb-3 rounded-md object-cover w-24 h-24" height="120" src="https://storage.googleapis.com/a1aa/image/e0071be7-4b9a-4d41-edf9-0296ebc1cb4c.jpg" width="120"/>
     <span class="text-gray-700 font-semibold group-hover:text-red-600 transition">
      Vestidos
     </span>
    </a>
    <a class="group block bg-white rounded-lg shadow hover:shadow-lg transition p-4" href="#">
     <img alt="Camisas masculinas coloridas penduradas em cabides, fundo branco" class="mx-auto mb-3 rounded-md object-cover w-24 h-24" height="120" src="https://storage.googleapis.com/a1aa/image/239e540f-d1a7-48cc-d022-a75244d90640.jpg" width="120"/>
     <span class="text-gray-700 font-semibold group-hover:text-red-600 transition">
      Camisas
     </span>
    </a>
    <a class="group block bg-white rounded-lg shadow hover:shadow-lg transition p-4" href="#">
     <img alt="Calçados variados, tênis e sandálias, sobre superfície branca" class="mx-auto mb-3 rounded-md object-cover w-24 h-24" height="120" src="https://storage.googleapis.com/a1aa/image/a5aa7d96-e861-40c8-1372-0085ae5e128e.jpg" width="120"/>
     <span class="text-gray-700 font-semibold group-hover:text-red-600 transition">
      Calçados
     </span>
    </a>
    <a class="group block bg-white rounded-lg shadow hover:shadow-lg transition p-4" href="#">
     <img alt="Acessórios de moda como bolsas, relógios e óculos sobre fundo branco" class="mx-auto mb-3 rounded-md object-cover w-24 h-24" height="120" src="https://storage.googleapis.com/a1aa/image/46c94bdd-76af-4ba5-5700-f021c41bd088.jpg" width="120"/>
     <span class="text-gray-700 font-semibold group-hover:text-red-600 transition">
      Acessórios
     </span>
    </a>
    <a class="group block bg-white rounded-lg shadow hover:shadow-lg transition p-4" href="#">
     <img alt="Roupas infantis coloridas penduradas em cabides, fundo branco" class="mx-auto mb-3 rounded-md object-cover w-24 h-24" height="120" src="https://storage.googleapis.com/a1aa/image/17020801-d5ca-4867-bbf4-e674e3b2e994.jpg" width="120"/>
     <span class="text-gray-700 font-semibold group-hover:text-red-600 transition">
      Infantis
     </span>
    </a>
    <a class="group block bg-white rounded-lg shadow hover:shadow-lg transition p-4" href="#">
     <img alt="Etiqueta de promoção vermelha com texto desconto, fundo branco" class="mx-auto mb-3 rounded-md object-cover w-24 h-24" height="120" src="https://storage.googleapis.com/a1aa/image/66be537a-0d2a-434b-1eda-ff6c2d3e7c67.jpg" width="120"/>
     <span class="text-gray-700 font-semibold group-hover:text-red-600 transition">
      Promoções
     </span>
    </a>
   </div>
  </section>
  <!-- Products Section -->
  <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mt-16 mb-20" id="produtos">
   <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">
    Produtos em Destaque
   </h2>
   <div aria-label="Lista de produtos em destaque" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Vestido vermelho elegante em manequim feminino, fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/e9372b51-905f-4a57-3cd2-a79e76039b00.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Vestido Vermelho Elegante
      </h3>
      <p class="text-gray-600 flex-grow">
       Vestido longo com corte fluido, perfeito para ocasiões especiais.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        7.500 Kz
       </span>
       <button aria-label="Adicionar Vestido Vermelho Elegante ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Camisa masculina azul clara pendurada em cabide, fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/4dcf7061-71a4-43bd-4952-8071a8ae4d76.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Camisa Masculina Azul
      </h3>
      <p class="text-gray-600 flex-grow">
       Camisa casual de algodão, confortável para o dia a dia.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        3.200 Kz
       </span>
       <button aria-label="Adicionar Camisa Masculina Azul ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Tênis branco moderno sobre superfície branca, vista lateral" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/b28c32c3-cc10-4f56-b852-cbca7c99e473.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Tênis Branco Moderno
      </h3>
      <p class="text-gray-600 flex-grow">
       Tênis esportivo com design clean e solado confortável.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        5.000 Kz
       </span>
       <button aria-label="Adicionar Tênis Branco Moderno ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Bolsa de ombro marrom em fundo branco, vista frontal" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/01e84463-9ef7-4a9f-f702-489da8c7ac8f.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Bolsa de Ombro Marrom
      </h3>
      <p class="text-gray-600 flex-grow">
       Bolsa espaçosa e elegante para o dia a dia.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        4.300 Kz
       </span>
       <button aria-label="Adicionar Bolsa de Ombro Marrom ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Jaqueta jeans feminina clara em manequim, fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/202718f7-5770-4984-0761-ccd7d4b89abb.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Jaqueta Jeans Feminina
      </h3>
      <p class="text-gray-600 flex-grow">
       Jaqueta jeans clássica com lavagem clara e corte moderno.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        6.100 Kz
       </span>
       <button aria-label="Adicionar Jaqueta Jeans Feminina ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Relógio masculino moderno com pulseira preta em fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/7109c084-0766-409d-1d18-03a70451b085.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Relógio Masculino Moderno
      </h3>
      <p class="text-gray-600 flex-grow">
       Relógio analógico com design sofisticado e pulseira de couro.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        8.200 Kz
       </span>
       <button aria-label="Adicionar Relógio Masculino Moderno ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Calça jeans masculina azul escura dobrada sobre superfície branca" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/da310cfd-910a-4b61-c659-7802696cbcbd.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Calça Jeans Masculina
      </h3>
      <p class="text-gray-600 flex-grow">
       Calça jeans azul escura com corte reto e confortável.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        5.700 Kz
       </span>
       <button aria-label="Adicionar Calça Jeans Masculina ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Blusa feminina de malha rosa clara pendurada em cabide, fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/e4c5db34-7df9-418c-1706-0d05a1d6e907.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Blusa Feminina Rosa
      </h3>
      <p class="text-gray-600 flex-grow">
       Blusa de malha leve, ideal para o dia a dia e conforto.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        2.900 Kz
       </span>
       <button aria-label="Adicionar Blusa Feminina Rosa ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Saia feminina estampada colorida pendurada em cabide, fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/dd4b1e5f-828a-48bf-d60e-666769ec1f74.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Saia Estampada Colorida
      </h3>
      <p class="text-gray-600 flex-grow">
       Saia midi com estampa vibrante, perfeita para o verão.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        3.600 Kz
       </span>
       <button aria-label="Adicionar Saia Estampada Colorida ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Chinelo feminino vermelho sobre superfície branca, vista lateral" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/4dbf1a6f-dd25-4b50-d83f-60df7a5b9870.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Chinelo Feminino Vermelho
      </h3>
      <p class="text-gray-600 flex-grow">
       Chinelo confortável para uso casual e praia.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        1.200 Kz
       </span>
       <button aria-label="Adicionar Chinelo Feminino Vermelho ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Óculos de sol masculino estiloso com armação preta, fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/b8fc47f4-fe8f-4dc6-e364-178ca1f93523.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Óculos de Sol Masculino
      </h3>
      <p class="text-gray-600 flex-grow">
       Óculos de sol com proteção UV e design moderno.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        4.800 Kz
       </span>
       <button aria-label="Adicionar Óculos de Sol Masculino ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Casaco masculino preto de inverno pendurado em cabide, fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/9ede2b1d-3b9b-4b37-08b2-00adf2d1f2d4.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Casaco Masculino Preto
      </h3>
      <p class="text-gray-600 flex-grow">
       Casaco quente e estiloso para os dias frios.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        9.000 Kz
       </span>
       <button aria-label="Adicionar Casaco Masculino Preto ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Vestido curto floral feminino com fundo branco" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/2d03de1c-cca2-43bb-d261-e17b577a6bb6.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Vestido Curto Floral
      </h3>
      <p class="text-gray-600 flex-grow">
       Vestido leve com estampa floral para dias ensolarados.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        4.100 Kz
       </span>
       <button aria-label="Adicionar Vestido Curto Floral ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow hover:shadow-lg transition flex flex-col">
     <img alt="Calça legging feminina preta esticada sobre superfície branca" class="rounded-t-lg object-cover w-full h-64" height="500" src="https://storage.googleapis.com/a1aa/image/2d393a3e-f93d-4e50-672a-c57fad89a1bf.jpg" width="400"/>
     <div class="p-4 flex flex-col flex-grow">
      <h3 class="text-lg font-semibold text-gray-800 mb-1">
       Calça Legging Preta
      </h3>
      <p class="text-gray-600 flex-grow">
       Legging confortável e versátil para exercícios e uso casual.
      </p>
      <div class="mt-4 flex items-center justify-between">
       <span class="text-red-600 font-bold text-xl">
        2.500 Kz
       </span>
       <button aria-label="Adicionar Calça Legging Preta ao carrinho" class="bg-red-600 text-white px-4 py-2 rounded-md hover:bg-red-700 transition">
        Comprar
       </button>
      </div>
     </div>
    </article>
   </div>
  </section>
  <!-- Footer -->
  <footer class="bg-white border-t border-gray-200 mt-20">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12 grid grid-cols-1 md:grid-cols-4 gap-8">
    <div>
     <h3 class="text-xl font-bold text-red-600 mb-4">
      Nossa Escolha
     </h3>
     <p class="text-gray-600">
      A sua loja online de moda com as melhores tendências e preços em Kz.
     </p>
     <div class="flex space-x-4 mt-6 text-gray-600">
      <a aria-label="Facebook" class="hover:text-red-600 transition" href="#">
       <i class="fab fa-facebook fa-lg">
       </i>
      </a>
      <a aria-label="Instagram" class="hover:text-red-600 transition" href="#">
       <i class="fab fa-instagram fa-lg">
       </i>
      </a>
      <a aria-label="Twitter" class="hover:text-red-600 transition" href="#">
       <i class="fab fa-twitter fa-lg">
       </i>
      </a>
      <a aria-label="YouTube" class="hover:text-red-600 transition" href="#">
       <i class="fab fa-youtube fa-lg">
       </i>
      </a>
     </div>
    </div>
    <div>
     <h4 class="text-lg font-semibold text-gray-800 mb-4">
      Categorias
     </h4>
     <ul class="space-y-2 text-gray-600">
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Mulheres
       </a>
      </li>
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Homens
       </a>
      </li>
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Acessórios
       </a>
      </li>
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Promoções
       </a>
      </li>
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Novidades
       </a>
      </li>
     </ul>
    </div>
    <div>
     <h4 class="text-lg font-semibold text-gray-800 mb-4">
      Informações
     </h4>
     <ul class="space-y-2 text-gray-600">
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Sobre Nós
       </a>
      </li>
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Política de Privacidade
       </a>
      </li>
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Termos de Uso
       </a>
      </li>
      <li>
       <a class="hover:text-red-600 transition" href="#">
        Contato
       </a>
      </li>
     </ul>
    </div>
    <div>
     <h4 class="text-lg font-semibold text-gray-800 mb-4">
      Assine nossa Newsletter
     </h4>
     <form class="flex flex-col space-y-4">
      <input aria-label="Seu email para newsletter" class="px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-red-600" placeholder="Seu email" required="" type="email"/>
      <button class="bg-red-600 text-white px-4 py-2 rounded-md font-semibold hover:bg-red-700 transition" type="submit">
       Assinar
      </button>
     </form>
    </div>
   </div>
   <div class="border-t border-gray-200 text-center py-6 text-gray-500 text-sm">
    © 2024 Nossa Escolha. Todos os direitos reservados.
   </div>
  </footer>
  <script>
   const mobileMenuButton = document.getElementById('mobile-menu-button');
    const mobileMenu = document.getElementById('mobile-menu');

    mobileMenuButton.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
 </body>
</html>
