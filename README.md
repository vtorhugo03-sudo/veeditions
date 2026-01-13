# veeditions
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SportArt - Galeria de Artes Esportivas</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body class="bg-gray-50 font-sans text-gray-900">

    <nav class="bg-black text-white p-4 sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold tracking-tighter italic underline decoration-red-600">SPORTART</h1>
            <div class="space-x-6">
                <a href="#" class="hover:text-red-500">Galeria</a>
                <a href="#" class="hover:text-red-500">Sobre</a>
                <a href="#" class="relative">
                    <i class="fa-solid fa-cart-shopping"></i>
                    <span class="absolute -top-2 -right-2 bg-red-600 text-xs rounded-full px-1">0</span>
                </a>
            </div>
        </div>
    </nav>

    <header class="bg-gray-900 text-white py-20 text-center bg-cover bg-center" style="background-image: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1540747913346-19e32dc3e97e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');">
        <h2 class="text-5xl font-extrabold mb-4 uppercase">A Emoção do Esporte em Papel</h2>
        <p class="text-xl mb-8">Pôsteres e artes digitais exclusivas dos seus ídolos favoritos.</p>
        <a href="#loja" class="bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-8 rounded-full transition duration-300">Ver Coleção</a>
    </header>

    <main id="loja" class="container mx-auto py-16 px-4">
        <h3 class="text-3xl font-bold mb-10 text-center border-b-4 border-red-600 w-fit mx-auto">Novidades</h3>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <div class="bg-white rounded-lg shadow-lg overflow-hidden group">
                <div class="h-80 bg-gray-200 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1518063319789-7217e6706b04?auto=format&fit=crop&w=500&q=80" alt="Arte de Futebol" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                </div>
                <div class="p-6">
                    <span class="text-red-600 font-bold text-xs uppercase tracking-widest">Futebol</span>
                    <h4 class="text-xl font-bold mt-2">Pôster Minimalista: O Gol</h4>
                    <p class="text-gray-600 mt-2">Impressão em papel fotográfico A3 de alta qualidade.</p>
                    <div class="flex justify-between items-center mt-6">
                        <span class="text-2xl font-bold text-gray-900">R$ 89,90</span>
                        <button class="bg-black text-white px-4 py-2 rounded hover:bg-gray-800">Adicionar ao Carrinho</button>
                    </div>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-lg overflow-hidden group">
                <div class="h-80 bg-gray-200 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1546519638-68e109498ffc?auto=format&fit=crop&w=500&q=80" alt="Arte de Basquete" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                </div>
                <div class="p-6">
                    <span class="text-blue-600 font-bold text-xs uppercase tracking-widest">Basquete</span>
                    <h4 class="text-xl font-bold mt-2">Dunk Legends - Digital</h4>
                    <p class="text-gray-600 mt-2">Arquivo em alta resolução para download imediato.</p>
                    <div class="flex justify-between items-center mt-6">
                        <span class="text-2xl font-bold text-gray-900">R$ 45,00</span>
                        <button class="bg-black text-white px-4 py-2 rounded hover:bg-gray-800">Adicionar ao Carrinho</button>
                    </div>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-lg overflow-hidden group">
                <div class="h-80 bg-gray-200 overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1533560235479-59fcf0e49424?auto=format&fit=crop&w=500&q=80" alt="Arte de Tênis" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                </div>
                <div class="p-6">
                    <span class="text-green-600 font-bold text-xs uppercase tracking-widest">Tênis</span>
                    <h4 class="text-xl font-bold mt-2">Grand Slam Final</h4>
                    <p class="text-gray-600 mt-2">Arte em estilo aquarela feita à mão.</p>
                    <div class="flex justify-between items-center mt-6">
                        <span class="text-2xl font-bold text-gray-900">R$ 120,00</span>
                        <button class="bg-black text-white px-4 py-2 rounded hover:bg-gray-800">Adicionar ao Carrinho</button>
                    </div>
                </div>
            </div>

        </div>
    </main>

    <footer class="bg-black text-white py-12 px-4">
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 text-center md:text-left">
            <div>
                <h5 class="text-xl font-bold mb-4">SportArt</h5>
                <p class="text-gray-400">Transformando sua paixão esportiva em decoração de alto nível.</p>
            </div>
            <div>
                <h5 class="text-xl font-bold mb-4">Links Rápidos</h5>
                <ul class="text-gray-400 space-y-2">
                    <li><a href="#" class="hover:text-white">Envio e Entregas</a></li>
                    <li><a href="#" class="hover:text-white">Termos de Uso</a></li>
                    <li><a href="#" class="hover:text-white">Contato</a></li>
                </ul>
            </div>
            <div>
                <h5 class="text-xl font-bold mb-4">Siga-nos</h5>
                <div class="flex justify-center md:justify-start space-x-4">
                    <a href="#" class="text-2xl hover:text-red-500"><i class="fa-brands fa-instagram"></i></a>
                    <a href="#" class="text-2xl hover:text-red-500"><i class="fa-brands fa-twitter"></i></a>
                </div>
            </div>
        </div>
        <div class="mt-10 text-center text-gray-500 border-t border-gray-800 pt-6">
            © 2026 SportArt Store. Todos os direitos reservados.
        </div>
    </footer>

</body>
</html>
