<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jakiba Impresiones - Estampados y papelería creativa</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Pacifico&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .handwritten {
            font-family: 'Pacifico', cursive;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header/Navigation -->
    <header class="shadow-md bg-white sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-indigo-600 handwritten" style="outline: rgb(0, 0, 0) dotted 3px; outline-offset: 1px;">Jakiba Impresiones</div>
            <div class="hidden md:flex space-x-8 items-center">
                <a href="#home" class="text-gray-700 hover:text-indigo-600">Inicio</a>
                <a href="#products" class="text-gray-700 hover:text-indigo-600">Productos</a>
                <a href="#services" class="text-gray-700 hover:text-indigo-600">Servicios</a>
                <a href="#gallery" class="text-gray-700 hover:text-indigo-600">Galería</a>
                <a href="#contact" class="text-gray-700 hover:text-indigo-600">Contacto</a>
                <button id="cart-button" class="relative text-gray-700 hover:text-indigo-600">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                    </svg>
                    <span id="cart-count" class="absolute -top-2 -right-2 bg-indigo-600 text-white text-xs rounded-full h-5 w-5 flex items-center justify-center">0</span>
                </button>
            </div>
            <button class="md:hidden focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-6xl font-bold mb-6">Diseña tu estilo con nosotros</h1>
                <p class="text-xl mb-8">Creaciones únicas en papelería y estampados para expresar tu personalidad</p>
                <a href="#products" class="bg-white text-indigo-600 px-8 py-3 rounded-full font-semibold hover:bg-gray-100 transition duration-300 inline-block">Ver productos</a>
            </div>
            <div class="md:w-1/2">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/03dd5d64-1334-43b2-aa2c-f5bd2f442fae.png" alt="Estudio de diseño creativo con diversas piezas de papelería, cuadernos y camisetas con estampados artísticos organizados sobre una mesa de madera clara" class="rounded-lg shadow-xl" />
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-16">Nuestros Productos</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition duration-300">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/0cc000c0-edfc-4410-9168-57941478a5d1.png" alt="Cuadernos artesanales con diferentes diseños de estampados, colores vibrantes y texturas variadas" class="w-full h-64 object-cover" />
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Cuadernos Personalizados</h3>
                        <p class="text-gray-600 mb-4">Diseña el cuaderno ideal para tus ideas con nuestros exclusivos estampados.</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-indigo-600">Desde $12.990</span>
                            <button class="bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 transition duration-300">Ver más</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition duration-300">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d627b98c-51fe-4896-aae1-2a1a5c0a1f52.png" alt="Set de stickers y pegatinas creativas con diferentes temáticas y diseños modernos" class="w-full h-64 object-cover" />
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Stickers Creativos</h3>
                        <p class="text-gray-600 mb-4">Decora tus cosas con nuestros stickers exclusivos en diferentes tamaños y formas.</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-indigo-600">Desde $3.990</span>
                            <button class="bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 transition duration-300">Ver más</button>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition duration-300">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d72511f6-9a83-4eb4-b40c-036c939c218a.png" alt="Tazas de cerámica con diseños de estampados coloridos y frases motivacionales" class="w-full h-64 object-cover" />
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Tazas Estampadas</h3>
                        <p class="text-gray-600 mb-4">Personaliza tu taza con los diseños más originales para tus bebidas favoritas.</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-indigo-600">Desde $8.990</span>
                            <button class="bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 transition duration-300">Ver más</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-16">Nuestros Servicios</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
                <div class="flex items-start">
                    <div class="bg-indigo-100 p-4 rounded-full mr-6">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z"></path>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-3">Diseño Personalizado</h3>
                        <p class="text-gray-600">Creamos diseños únicos según tus ideas y personalidad. Trabajamos contigo para desarrollar el concepto perfecto para tus productos.</p>
                    </div>
                </div>
                <div class="flex items-start">
                    <div class="bg-indigo-100 p-4 rounded-full mr-6">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-3">Estampados Textiles</h3>
                        <p class="text-gray-600">Personalizamos camisetas, sudaderas, bolsas y más con técnicas de estampado de alta calidad que duran lavada tras lavada.</p>
                    </div>
                </div>
                <div class="flex items-start">
                    <div class="bg-indigo-100 p-4 rounded-full mr-6">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"></path>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-3">Papelería Corporativa</h3>
                        <p class="text-gray-600">Diseñamos papelería profesional para empresas: tarjetas de presentación, carpetas, blocks de notas y más con tu marca.</p>
                    </div>
                </div>
                <div class="flex items-start">
                    <div class="bg-indigo-100 p-4 rounded-full mr-6">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z"></path>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-3">Eventos Especiales</h3>
                        <p class="text-gray-600">Todo lo necesario para tus eventos: invitaciones, souvenirs y decoración personalizada para bodas, cumpleaños y más.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-16">Galería de Trabajos</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/9df08e85-ba7a-4e8c-a2c6-0351163de64e.png" alt="Camiseta con estampado abstracto en tonos azules y verdes con diseño geométrico" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/a1902048-f6da-46b8-b67c-9b5e3f967739.png" alt="Cuaderno artesanal con portada de cuero y grabado floral en relieve" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/4f91414a-af8a-462b-8de9-ef3959ee04a6.png" alt="Set de tarjetas de presentación con diseño minimalista y tipografía elegante" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ee65ec90-4f96-4459-b002-fda291268b01.png" alt="Bolsa de tela con estampado de ilustración de ciudad futurista" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/c7dc8dd5-12a9-4a6b-84ae-537e23e7304c.png" alt="Stickers de animales en estilo ilustración con colores pastel" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/0a070f27-d817-4fcc-86f0-92358390128d.png" alt="Invitaciones de boda con caligrafía dorada y diseño floral vintage" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/e74b88c0-f536-4ae4-9811-facafb9d3441.png" alt="Taza con foto personalizada y mensaje motivacional en tipografía manuscrita" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/653d607e-b34e-4be5-a312-8ce5e0a076ac.png" alt="Carpeta ejecutiva con grabado láser del logo de la empresa" class="w-full h-48 object-cover rounded-lg shadow hover:scale-105 transition duration-300" />
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 gradient-bg text-white">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <h2 class="text-3xl font-bold mb-6">Contáctanos</h2>
                    <p class="mb-6">Estamos aquí para ayudarte a crear productos únicos y personalizados. Visítanos en nuestro local o envíanos un mensaje.</p>
                    <div class="mb-6">
                        <h3 class="text-xl font-bold mb-2">Horario de Atención</h3>
                        <p>Lunes a Viernes: 9:00 - 19:00 hrs</p>
                        <p>Sábados: 10:00 - 14:00 hrs</p>
                    </div>
                    <div class="mb-6">
                        <h3 class="text-xl font-bold mb-2">Ubicación</h3>
                        <p>Calle Creativa 123, Local 45</p>
                        <p>Barrio Artístico</p>
                    </div>
                    <div class="mb-6">
                        <h3 class="text-xl font-bold mb-2">Teléfono</h3>
                        <p>+56 9 1234 5678</p>
                    </div>
                </div>
                <div class="md:w-1/2 bg-white rounded-lg shadow-xl p-8">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">Envía un Mensaje</h3>
                    <form>
                        <div class="mb-4">
                            <label for="name" class="block text-gray-700 mb-2">Nombre</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 text-gray-700" placeholder="Tu nombre">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="block text-gray-700 mb-2">Correo Electrónico</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 text-gray-700" placeholder="tu@email.com">
                        </div>
                        <div class="mb-4">
                            <label for="phone" class="block text-gray-700 mb-2">Teléfono (opcional)</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 text-gray-700" placeholder="+56 9 1234 5678">
                        </div>
                        <div class="mb-4">
                            <label for="message" class="block text-gray-700 mb-2">Mensaje</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500 text-gray-700" placeholder="Cuéntanos sobre tu proyecto..."></textarea>
                        </div>
                        <button type="submit" class="bg-indigo-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-indigo-700 transition duration-300 w-full">Enviar Mensaje</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-10">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <div class="text-2xl font-bold text-white handwritten mb-4">Jakiba Impresiones</div>
                    <p class="text-gray-400">Diseño y creatividad para expresarte</p>
                </div>
                <div class="flex space-x-6">
                    <a href="https://www.facebook.com/jakelinebarraza" target="_blank" class="text-gray-400 hover:text-white transition duration-300">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/>
                        </svg>
                    </a>
                    <a href="https://www.instagram.com/jakibaimpresiones/" target="_blank" class="text-gray-400 hover:text-white transition duration-300">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"/>
                        </svg>
                    </a>
                    <a href="https://www.facebook.com/groups/jakibaimpresiones" target="_blank" class="text-gray-400 hover:text-white transition duration-300">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.13 11.854v-8.385H7.078v-3.47h3.04V9.43c0-2.997 1.9-4.735 4.775-4.735 1.383 0 2.829.246 2.829.246v3.11h-1.595c-1.57 0-2.06.975-2.06 1.975v2.37h3.478l-.556 3.47h-2.923v8.385C19.612 23.027 24 18.063 24 12.073z"/>
                        </svg>
                    </a>
                    <a href="https://www.tiktok.com/@jacquelinebarraza52?is_from_webapp=1&sender_device=pc" target="_blank" class="text-gray-400 hover:text-white transition duration-300">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.35 2.79-.76 4.1-1.29 3.77-4.95 6.68-8.94 6.76-1.31.02-2.61-.13-3.87-.41-2.87-.7-5.33-2.68-6.5-5.41-.52-1.18-.8-2.42-.8-3.67 0-1.09.22-2.17.66-3.17 1.11-2.69 3.67-4.65 6.61-4.97.63-.06 1.26-.01 1.88.07.03-1.31-.07-2.62-.2-3.93h-1.68v-3.51c1.6.03 3.19.13 4.77.31z"/>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400 text-sm">
                <p>© 2023 Jakiba Impresiones. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const menuButton = document.querySelector('button[class*="md:hidden"]');
        const menu = document.querySelector('nav div[class*="md:flex"]');
        
        menuButton.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
    
    <!-- Shopping Cart Sidebar -->
    <div id="cart-sidebar" class="fixed inset-y-0 right-0 w-full md:w-96 bg-white shadow-xl transform translate-x-full transition-transform duration-300 ease-in-out z-50">
        <div class="p-6">
            <div class="flex justify-between items-center mb-6">
                <h2 class="text-2xl font-bold">Tu Carrito</h2>
                <button id="close-cart" class="text-gray-500 hover:text-gray-700">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                    </svg>
                </button>
            </div>
            <div id="cart-items" class="mb-6 space-y-4">
                <!-- Cart items will be added here dynamically -->
                <p class="text-gray-500 text-center py-8">Tu carrito está vacío</p>
            </div>
            <div class="border-t pt-4">
                <div class="flex justify-between font-bold text-lg mb-4">
                    <span>Total:</span>
                    <span id="cart-total">$0</span>
                </div>
                <button class="w-full bg-indigo-600 text-white py-3 rounded-lg font-semibold hover:bg-indigo-700 transition duration-300 mb-2">
                    Ir a pagar
                </button>
                <div class="flex justify-center space-x-4 mt-4">
                    <div class="text-center">
                        <img src="https://placehold.co/40x25?text=VISA" alt="Visa" class="mx-auto">
                        <span class="text-xs block mt-1">Visa</span>
                    </div>
                    <div class="text-center">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/27f570a7-4e04-41b6-a429-0cf97ce39891.png" alt="Mastercard" class="mx-auto">
                        <span class="text-xs block mt-1">Mastercard</span>
                    </div>
                    <div class="text-center">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/3d76d46b-62f7-40e4-b1c6-f57dffb6f0a0.png" alt="Transferencia" class="mx-auto">
                        <span class="text-xs block mt-1">Transferencia</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="cart-overlay" class="fixed inset-0 bg-black bg-opacity-50 z-40 hidden"></div>

    <script>
        // Cart functionality
        const cartButton = document.getElementById('cart-button');
        const closeCart = document.getElementById('close-cart');
        const cartSidebar = document.getElementById('cart-sidebar');
        const cartOverlay = document.getElementById('cart-overlay');
        const cartCount = document.getElementById('cart-count');
        const cartItems = document.getElementById('cart-items');
        const cartTotal = document.getElementById('cart-total');

        let cart = [];

        // Toggle cart visibility
        cartButton.addEventListener('click', () => {
            cartSidebar.classList.remove('translate-x-full');
            cartOverlay.classList.remove('hidden');
        });

        closeCart.addEventListener('click', () => {
            cartSidebar.classList.add('translate-x-full');
            cartOverlay.classList.add('hidden');
        });

        cartOverlay.addEventListener('click', () => {
            cartSidebar.classList.add('translate-x-full');
            cartOverlay.classList.add('hidden');
        });

        // Add to cart functionality (you'll need to add this to your product buttons)
        function addToCart(product) {
            cart.push(product);
            updateCart();
        }

        function updateCart() {
            cartCount.textContent = cart.length;
            
            if (cart.length > 0) {
                cartItems.innerHTML = '';
                let total = 0;
                
                cart.forEach((item, index) => {
                    total += item.price;
                    cartItems.innerHTML += `
                        <div class="flex items-center justify-between border-b pb-4">
                            <div class="flex items-center space-x-4">
                                <img src="${item.image}" alt="${item.name}" class="w-16 h-16 object-cover rounded">
                                <div>
                                    <h3 class="font-medium">${item.name}</h3>
                                    <p class="text-gray-500 text-sm">${item.price}</p>
                                </div>
                            </div>
                            <button class="text-red-500" onclick="removeFromCart(${index})">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16" />
                                </svg>
                            </button>
                        </div>
                    `;
                });
                
                cartTotal.textContent = `${total.toLocaleString()}`;
            } else {
                cartItems.innerHTML = '<p class="text-gray-500 text-center py-8">Tu carrito está vacío</p>';
                cartTotal.textContent = '$0';
            }
        }

        function removeFromCart(index) {
            cart.splice(index, 1);
            updateCart();
        }

        // Example of how to add products to cart (you'll need to implement this on your product buttons)
        // document.querySelectorAll('.add-to-cart').forEach(button => {
        //     button.addEventListener('click', () => {
        //         const product = {
        //             name: button.dataset.name,
        //             price: parseFloat(button.dataset.price),
        //             image: button.dataset.image
        //         };
        //         addToCart(product);
        //     });
        // });
    </script>
</body>
</html>

