<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundación Solydar - Ayudando a la Infancia y al Planeta</title>
    
    <!-- Script de Tailwind CSS --><script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Fuente Inter de Google Fonts --><link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <style>
        /* Aplicamos la fuente Inter como fuente principal */
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Estilo para las pestañas de formulario */
        .tab-button.active {
            border-bottom-width: 3px;
            font-weight: 600;
        }
    </style>
    
    <script>
        // Configuración personalizada de Tailwind con tu paleta de colores
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'solydar-olive': '#748404', // Verde Oliva
                        'solydar-orange': '#E49212', // Naranja/Dorado del sol
                        'solydar-purple-main': '#942EB1', // Púrpura principal
                        'solydar-purple-light': '#D55AD4', // Lila/Púrpura claro
                        'solydar-purple-dark': '#831F60', // Púrpura oscuro
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white text-gray-800 antialiased">

    <!-- ===== SECCIÓN DE NAVEGACIÓN ===== --><header class="bg-white shadow-md sticky top-0 left-0 w-full z-50">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo --><a href="#" class="flex-shrink-0 flex items-center">
                    <!-- Se utiliza el logo de Solydar --><img src="LOGOSOLYDAR.png" alt="Logo de Solydar" class="h-14 w-auto"> 
                </a>
                
                <!-- Navegación de Escritorio --><div class="hidden md:flex items-center space-x-8">
                    <a href="#inicio" class="font-medium text-gray-600 hover:text-solydar-purple-main">Inicio</a>
                    <a href="#mision" class="font-medium text-gray-600 hover:text-solydar-purple-main">Nuestra Misión</a>
                    <a href="#modelo" class="font-medium text-gray-600 hover:text-solydar-purple-main">Nuestro Modelo</a>
                    <a href="#condiciones" class="font-medium text-gray-600 hover:text-solydar-purple-main">Condiciones</a>
                    <a href="#formularios" class="font-medium text-gray-600 hover:text-solydar-purple-main">Formularios</a>
                    <a href="#contacto" class="font-medium text-gray-600 hover:text-solydar-purple-main">Contacto</a>
                </div>
                
                <!-- Botón CTA (Llamado a la Acción) de Escritorio --><div class="hidden md:block">
                    <a href="#formularios" class="inline-block bg-solydar-orange text-white font-bold py-2 px-5 rounded-full hover:bg-solydar-orange-600 transition duration-300">
                        Donar/Recibir
                    </a>
                </div>

                <!-- Botón de Menú Móvil --><div class="md:hidden flex items-center">
                    <button id="menu-btn" class="text-gray-700 hover:text-solydar-purple-main focus:outline-none">
                        <svg id="menu-icon" class="h-8 w-8" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                        </svg>
                        <svg id="close-icon" class="h-8 w-8 hidden" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </button>
                </div>
            </div>
        </nav>

        <!-- Menú Móvil (oculto por defecto) --><div id="mobile-menu" class="md:hidden hidden bg-white shadow-lg absolute w-full z-40">
            <div class="px-2 pt-2 pb-4 space-y-2 sm:px-3 text-center">
                <a href="#inicio" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-100">Inicio</a>
                <a href="#mision" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-100">Nuestra Misión</a>
                <a href="#modelo" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-100">Nuestro Modelo</a>
                <a href="#condiciones" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-100">Condiciones</a>
                <a href="#formularios" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-100">Formularios</a>
                <a href="#contacto" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-100">Contacto</a>
                <a href="#formularios" class="block w-3/4 mx-auto mt-4 bg-solydar-orange text-white font-bold py-2 px-5 rounded-full hover:bg-solydar-orange-600 transition duration-300">
                    Donar/Recibir
                </a>
            </div>
        </div>
    </header>

    <!-- ===== SECCIÓN HERO (INICIO) ===== --><main>
        <section id="inicio" class="bg-gray-50">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 md:py-32">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                    <!-- Contenido de Texto --><div>
                        <span class="inline-block bg-solydar-purple-light text-white font-semibold px-4 py-1 rounded-full text-sm">
                            Infancia y Medio Ambiente
                        </span>
                        <h1 class="mt-4 text-4xl lg:text-5xl font-extrabold text-gray-900 leading-tight">
                            Una segunda oportunidad para la ropa.
                            <span class="block text-solydar-purple-main">Un futuro verde para la infancia.</span>
                        </h1>
                        <p class="mt-6 text-lg text-gray-600">
                            En Solydar creamos un ciclo de solidaridad: recolectamos donaciones para la primera infancia y, junto a las familias beneficiadas, cuidamos nuestro planeta.
                        </p>
                        <div class="mt-10 flex flex-wrap gap-4">
                            <a href="#formularios" class="inline-block bg-solydar-olive text-white font-bold py-3 px-8 rounded-full text-lg hover:bg-solydar-olive-darker transition duration-300">
                                Quiero Donar
                            </a>
                            <a href="#modelo" class="inline-block bg-gray-200 text-gray-800 font-bold py-3 px-8 rounded-full text-lg hover:bg-gray-300 transition duration-300">
                                Conocer Más
                            </a>
                        </div>
                    </div>
                    <!-- Imagen (ACTUALIZADA con la imagen del bebé y artículos) --><div class="hidden md:block">
                        <img src="Captura de pantalla 2025-11-07 125013.png" 
                             alt="Bebé rodeado de ropa y accesorios de primera infancia, representando las donaciones de Solydar." 
                             class="rounded-xl shadow-2xl object-cover w-full h-full max-h-[500px]">
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== SECCIÓN MISIÓN (QUIÉNES SOMOS) ===== --><section id="mision" class="py-20 md:py-32 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <span class="font-semibold text-solydar-purple-main uppercase">Nuestra Misión</span>
                <h2 class="mt-2 text-3xl md:text-4xl font-extrabold text-gray-900">
                    Creemos en un mundo solidario
                </h2>
                <p class="mt-6 text-lg text-gray-600 max-w-3xl mx-auto">
                    Solydar nace de la convicción de que podemos brindar apoyo vital a la primera infancia en situación de vulnerabilidad, al mismo tiempo que fomentamos una cultura de responsabilidad ambiental. No solo damos, creamos comunidad y conciencia.
                </p>
            </div>
        </section>

        <!-- ===== SECCIÓN MODELO (NUESTRO CÍRCULO VIRTUOSO) ===== --><section id="modelo" class="py-20 md:py-32 bg-solydar-purple-light bg-opacity-10"> <!-- Fondo púrpura claro suave --><div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16">
                    <span class="font-semibold text-solydar-purple-main uppercase">Nuestro Modelo</span>
                    <h2 class="mt-2 text-3xl md:text-4xl font-extrabold text-gray-900">
                        El Círculo Virtuoso de Solydar
                    </h2>
                    <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">
                        Así es como tu ayuda se transforma en un doble impacto.
                    </p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Tarjeta 1 --><div class="bg-white p-8 rounded-xl shadow-lg text-center transition-all duration-300 hover:shadow-2xl hover:-translate-y-2">
                        <div class="flex justify-center items-center mb-6">
                            <span class="flex items-center justify-center bg-solydar-purple-light bg-opacity-30 rounded-full h-16 w-16">
                                <!-- Icono SVG de Donación --><svg class="h-8 w-8 text-solydar-purple-main" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M20.573 4.227a1.002 1.002 0 0 0-.964-.322l-6.22 1.391a.998.998 0 0 0-.389 0l-6.22-1.391a1 1 0 0 0-.964.322c-.22.22-.322.522-.29.816l.721 6.491a1 1 0 0 0 .97.866h1.298c.287 4.908 4.314 8.6 9.282 8.6s9.004-3.692 9.282-8.6h1.298a1 1 0 0 0 .97-.866l.721-6.491c.032-.294-.07-.596-.29-.816ZM12 19.999c-3.859 0-7.03-2.83-7.35-6.6h14.7c-.32 3.77-3.491 6.6-7.35 6.6Z"/></svg>
                            </span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-900">1. Recolectamos</h3>
                        <p class="mt-3 text-gray-600">
                            Recibimos ropa, juguetes y artículos de segunda mano en excelente estado. Lo que tú ya no usas, alguien más lo necesita.
                        </p>
                    </div>
                    
                    <!-- Tarjeta 2 --><div class="bg-white p-8 rounded-xl shadow-lg text-center transition-all duration-300 hover:shadow-2xl hover:-translate-y-2">
                        <div class="flex justify-center items-center mb-6">
                            <span class="flex items-center justify-center bg-solydar-purple-light bg-opacity-30 rounded-full h-16 w-16">
                                <!-- Icono SVG de Apoyo --><svg class="h-8 w-8 text-solydar-purple-main" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M12.781 2.375c-.383-.474-1.18-.474-1.562 0l-3.375 4.17C4.625 10.625.5 13.375.5 17.5 1 20 3 21.5 5.25 21.5c2.313 0 4.094-1.531 5.25-3C11.5 19.469 12 20 12.75 20c.75 0 1.25-.531 1.5-1.5 1.156 1.469 2.938 3 5.25 3C21 21.5 23 20 23.5 17.5c0-4.125-4.125-6.875-7.344-11.031l-3.375-4.094Z"/></svg>
                            </span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-900">2. Donamos</h3>
                        <p class="mt-3 text-gray-600">
                            Clasificamos y entregamos las donaciones directamente a familias vulnerables, asegurando que lleguen a quienes más lo necesitan.
                        </p>
                    </div>

                    <!-- Tarjeta 3 --><div class="bg-white p-8 rounded-xl shadow-lg text-center transition-all duration-300 hover:shadow-2xl hover:-translate-y-2">
                        <div class="flex justify-center items-center mb-6">
                            <span class="flex items-center justify-center bg-solydar-purple-light bg-opacity-30 rounded-full h-16 w-16">
                                <!-- Icono SVG de Medio Ambiente --><svg class="h-8 w-8 text-solydar-purple-main" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2ZM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8Zm-.21-12.04c-.18-.14-.44-.13-.61.03-.17.16-.22.42-.11.63L13 12.1V16c0 .28.22.5.5.5s.5-.22.5-.5v-4.21c0-.21-.08-.4-.22-.55l-1.98-1.61Z"/></svg>
                            </span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-900">3. Retribuimos</h3>
                        <p class="mt-3 text-gray-600">
                            Las familias beneficiadas se unen a nosotros en jornadas de siembra de árboles y programas de reciclaje, cuidando el planeta juntos.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== SECCIÓN CONDICIONES DE ARTÍCULOS ===== --><section id="condiciones" class="py-20 md:py-32 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16">
                    <span class="font-semibold text-solydar-purple-main uppercase">Donaciones Inteligentes</span>
                    <h2 class="mt-2 text-3xl md:text-4xl font-extrabold text-gray-900">
                        Qué Artículos Recibimos
                    </h2>
                    <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">
                        Ayúdanos a asegurar que lo que donas es lo que la primera infancia realmente necesita.
                    </p>
                </div>
                
                <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                    <!-- Artículos: ROPA --><div class="group bg-gray-50 p-6 rounded-xl shadow-md border-t-4 border-solydar-purple-main hover:bg-solydar-purple-light hover:text-white transition duration-300 transform hover:scale-[1.02]">
                        <div class="flex justify-center mb-4">
                            <!-- Icono de Ropa --><svg class="h-10 w-10 text-solydar-purple-main group-hover:text-white transition duration-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M12 3a2.5 2.5 0 0 1 2.5 2.5v2.5H16a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h1.5V5.5A2.5 2.5 0 0 1 12 3m0 2.5c-.28 0-.5.22-.5.5v2.5h1V6c0-.28-.22-.5-.5-.5Zm1 5H11v8h2v-8Z"/></svg>
                        </div>
                        <h3 class="text-lg font-bold text-center mb-2">ROPA</h3>
                        <p class="text-sm text-gray-600 group-hover:text-gray-100 text-center">
                            Ropa y pijamas de **recién nacido hasta 5T**, en perfecto estado y limpias.
                        </p>
                    </div>

                    <!-- Artículos: JUGUETES --><div class="group bg-gray-50 p-6 rounded-xl shadow-md border-t-4 border-solydar-olive hover:bg-solydar-olive hover:text-white transition duration-300 transform hover:scale-[1.02]">
                        <div class="flex justify-center mb-4">
                            <!-- Icono de Juguete --><svg class="h-10 w-10 text-solydar-olive group-hover:text-white transition duration-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2a10 10 0 1 0 0 20 10 10 0 0 0 0-20Zm0 18a8 8 0 1 1 0-16 8 8 0 0 1 0 16ZM12 7c-1.38 0-2.5 1.12-2.5 2.5S10.62 12 12 12s2.5-1.12 2.5-2.5S13.38 7 12 7Zm0 3.5c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1Zm-5.5 1.5A.5.5 0 0 1 7 13v.5a.5.5 0 0 1-1 0V13a.5.5 0 0 1 .5-.5ZM17 12.5a.5.5 0 0 1 .5-.5h.5a.5.5 0 0 1 0 1h-.5a.5.5 0 0 1-.5-.5Z"/></svg>
                        </div>
                        <h3 class="text-lg font-bold text-center mb-2">JUGUETES</h3>
                        <p class="text-sm text-gray-600 group-hover:text-gray-100 text-center">
                            Apropiados para niños hasta los **5 años**. No deben estar rotos ni descompuestos.
                        </p>
                    </div>
                    
                    <!-- Artículos: EQUIPOS --><div class="group bg-gray-50 p-6 rounded-xl shadow-md border-t-4 border-solydar-orange hover:bg-solydar-orange hover:text-white transition duration-300 transform hover:scale-[1.02]">
                        <div class="flex justify-center mb-4">
                            <!-- Icono de Equipo/Coche --><svg class="h-10 w-10 text-solydar-orange group-hover:text-white transition duration-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M18 10h-2V7h-3v3H9V7H6v3H4c-.55 0-1 .45-1 1v1.5c0 .35.18.66.45.85L5 15h11c.28 0 .54-.12.73-.32.19-.2.27-.47.27-.78V11c0-.55-.45-1-1-1ZM5 12.5V12h11v.5c0 .28-.22.5-.5.5H5.5c-.28 0-.5-.22-.5-.5ZM17 18c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2Zm-12 0c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2Z"/></svg>
                        </div>
                        <h3 class="text-lg font-bold text-center mb-2">EQUIPOS</h3>
                        <p class="text-sm text-gray-600 group-hover:text-gray-100 text-center">
                            Coches, mecedoras, colechos, sillas para comer, cobijas, maletas, pañaleras, cambiadores.
                        </p>
                    </div>

                    <!-- Artículos: ACCESORIOS --><div class="group bg-gray-50 p-6 rounded-xl shadow-md border-t-4 border-solydar-purple-dark hover:bg-solydar-purple-dark hover:text-white transition duration-300 transform hover:scale-[1.02]">
                        <div class="flex justify-center mb-4">
                            <!-- Icono de Biberón/Accesorio --><svg class="h-10 w-10 text-solydar-purple-dark group-hover:text-white transition duration-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2a4 4 0 0 1 4 4v2.5H8V6a4 4 0 0 1 4-4m-1 7h2v11a1 1 0 0 1-1 1 1 1 0 0 1-1-1V9Z"/></svg>
                        </div>
                        <h3 class="text-lg font-bold text-center mb-2">ACCESORIOS</h3>
                        <p class="text-sm text-gray-600 group-hover:text-gray-100 text-center">
                            Suministros de alimentación, ropa de cama (sábanas), artículos de seguridad y más.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== SECCIÓN FORMULARIOS (DONAR / RECIBIR) ===== --><section id="formularios" class="py-20 md:py-32 bg-gray-50">
            <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="bg-white rounded-xl shadow-2xl p-8 md:p-12">
                    <div class="text-center mb-8">
                        <span class="font-semibold text-solydar-orange uppercase">¡Queremos conocerte!</span>
                        <h2 class="mt-2 text-3xl font-extrabold text-gray-900">
                            Sé parte del ciclo Solydar
                        </h2>
                    </div>

                    <!-- Pestañas de Navegación del Formulario --><div class="flex border-b border-gray-200 mb-8">
                        <button id="tab-donor-btn" data-form="donor" class="tab-button active flex-1 text-center py-4 text-gray-700 border-solydar-purple-main hover:bg-gray-50 transition duration-300">
                            Quiero Donar
                        </button>
                        <button id="tab-recipient-btn" data-form="recipient" class="tab-button flex-1 text-center py-4 text-gray-700 border-solydar-purple-main hover:bg-gray-50 transition duration-300">
                            Necesito la Donación
                        </button>
                    </div>

                    <!-- Contenedor del Formulario de DONANTE --><div id="donor-form-container">
                        <form id="donor-form" class="space-y-6">
                            <p class="text-gray-600 text-sm">Usa este formulario para ofrecernos artículos. ¡Gracias por tu generosidad!</p>
                            
                            <div>
                                <label for="donor_name" class="block text-sm font-medium text-gray-700">Nombre Completo</label>
                                <input type="text" id="donor_name" name="donor_name" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label for="donor_email" class="block text-sm font-medium text-gray-700">Correo Electrónico</label>
                                    <input type="email" id="donor_email" name="donor_email" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                                </div>
                                <div>
                                    <label for="donor_phone" class="block text-sm font-medium text-gray-700">Teléfono (WhatsApp)</label>
                                    <input type="tel" id="donor_phone" name="donor_phone" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                                </div>
                            </div>
                            
                            <div>
                                <label for="donor_city" class="block text-sm font-medium text-gray-700">Ciudad donde Vives</label>
                                <input type="text" id="donor_city" name="donor_city" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                            </div>

                            <div>
                                <label for="donor_article" class="block text-sm font-medium text-gray-700">¿Qué artículo deseas donar?</label>
                                <textarea id="donor_article" name="donor_article" rows="3" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main"></textarea>
                                <p class="mt-1 text-xs text-gray-500">Ejemplo: Coche para bebé, 5 camisetas 2T, un lote de juguetes, etc.</p>
                            </div>

                            <div id="donor-message" class="hidden p-3 rounded-md text-sm"></div>

                            <button type="submit" id="donor-submit-btn" class="w-full bg-solydar-olive text-white font-bold py-3 rounded-full hover:bg-solydar-purple-main transition duration-300 flex items-center justify-center">
                                Enviar Oferta de Donación
                            </button>
                        </form>
                    </div>

                    <!-- Contenedor del Formulario de RECEPTOR (Oculto por defecto) --><div id="recipient-form-container" class="hidden">
                        <form id="recipient-form" class="space-y-6">
                            <p class="text-gray-600 text-sm">Usa este formulario si necesitas recibir donaciones para tus hijos o beneficiarios.</p>
                            
                            <div>
                                <label for="recipient_name" class="block text-sm font-medium text-gray-700">Nombre del Padre/Madre/Tutor</label>
                                <input type="text" id="recipient_name" name="recipient_name" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label for="recipient_email" class="block text-sm font-medium text-gray-700">Correo Electrónico</label>
                                    <input type="email" id="recipient_email" name="recipient_email" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                                </div>
                                <div>
                                    <label for="recipient_phone" class="block text-sm font-medium text-gray-700">Teléfono (WhatsApp)</label>
                                    <input type="tel" id="recipient_phone" name="recipient_phone" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                                </div>
                            </div>

                            <div>
                                <label for="recipient_city" class="block text-sm font-medium text-gray-700">Ciudad donde Vives</label>
                                <input type="text" id="recipient_city" name="recipient_city" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                                <div>
                                    <label for="recipient_child_count" class="block text-sm font-medium text-gray-700">Cantidad de Hijos (0-5 años)</label>
                                    <input type="number" id="recipient_child_count" name="recipient_child_count" min="1" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                                </div>
                                <div>
                                    <label for="recipient_child_name" class="block text-sm font-medium text-gray-700">Nombre del Hijo/a a Beneficiar</label>
                                    <input type="text" id="recipient_child_name" name="recipient_child_name" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                                </div>
                                <div>
                                    <label for="recipient_child_age" class="block text-sm font-medium text-gray-700">Edad del Niño/a (en años)</label>
                                    <input type="number" id="recipient_child_age" name="recipient_child_age" min="0" max="5" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:border-solydar-purple-main focus:ring-solydar-purple-main">
                                </div>
                            </div>
                            
                            <div id="recipient-message" class="hidden p-3 rounded-md text-sm"></div>

                            <button type="submit" id="recipient-submit-btn" class="w-full bg-solydar-purple-main text-white font-bold py-3 rounded-full hover:bg-solydar-olive transition duration-300 flex items-center justify-center">
                                Enviar Solicitud de Ayuda
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>


        <!-- ===== SECCIÓN CÓMO AYUDAR (Se mantiene para voluntarios/acopio) ===== --><section id="ayudar" class="py-20 md:py-32 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16">
                    <span class="font-semibold text-solydar-purple-main uppercase">Únete al Movimiento</span>
                    <h2 class="mt-2 text-3xl md:text-4xl font-extrabold text-gray-900">
                        Tu tiempo y apoyo son vitales
                    </h2>
                    <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">
                        Hay muchas formas de ser parte de Solydar y generar un cambio real.
                    </p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Ayuda 1: Donar Artículos (Lleva al formulario) --><div class="border border-gray-200 rounded-xl p-8 shadow-sm hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-2xl font-bold text-gray-900">Dona Artículos</h3>
                        <p class="mt-3 text-gray-600 mb-6">
                            ¿Tienes ropa, juguetes o equipos en buen estado? Inscríbelos a través del formulario.
                        </p>
                        <a href="#formularios" class="font-bold text-solydar-purple-main hover:text-solydar-purple-dark">
                            Ir al Formulario &rarr;
                        </a>
                    </div>
                    <!-- Ayuda 2: Donar Dinero --><div class="border border-gray-200 rounded-xl p-8 shadow-sm hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-2xl font-bold text-gray-900">Dona Dinero</h3>
                        <p class="mt-3 text-gray-600 mb-6">
                            Tu aporte financia la logística, el transporte y la compra de árboles para nuestras jornadas.
                        </p>
                        <a href="#" class="font-bold text-solydar-purple-main hover:text-solydar-purple-dark">
                            Hacer Donación Monetaria &rarr;
                        </a>
                    </div>
                    <!-- Ayuda 3: Ser Voluntario --><div class="border border-gray-200 rounded-xl p-8 shadow-sm hover:shadow-lg transition-shadow duration-300">
                        <h3 class="text-2xl font-bold text-gray-900">Sé Voluntario</h3>
                        <p class="mt-3 text-gray-600 mb-6">
                            Tu tiempo es valioso. Ayúdanos a clasificar, organizar o en las jornadas ambientales.
                        </p>
                        <a href="#contacto" class="font-bold text-solydar-purple-main hover:text-solydar-purple-dark">
                            Quiero ser Voluntario &rarr;
                        </a>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ===== SECCIÓN FOOTER (PIE DE PÁGINA) ===== --><footer id="contacto" class="bg-solydar-purple-dark text-gray-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-12">
                <!-- Col 1: Logo y Redes --><div class="md:col-span-1">
                    <!-- Se utiliza el logo de Solydar --><img src="LOGOSOLYDAR.png" alt="Logo de Solydar" class="h-14 w-auto mb-4">
                    <p class="mt-4 text-sm">
                        Cambiando vidas, un niño y un árbol a la vez.
                    </p>
                    <div class="flex space-x-5 mt-6">
                        <a href="https://www.facebook.com/solydarfundacion/" target="_blank" class="hover:text-white" aria-label="Facebook">
                            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M22.46 6c-.77.35-1.6.58-2.46.67.88-.53 1.56-1.37 1.88-2.38-.83.49-1.74.85-2.7 1.04C18.4 4.5 17.27 4 16 4c-2.35 0-4.27 1.92-4.27 4.29 0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15 0 1.49.76 2.8 1.9 3.57-.7-.02-1.36-.21-1.94-.53v.05c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 0 1-1.93.07 4.28 4.28 0 0 0 4 2.98 8.52 8.52 0 0 1-5.33 1.84c-.35 0-.69-.02-1.03-.06C3.4 19.25 5.9 20 8.68 20c7.88 0 12.21-6.54 12.21-12.21 0-.19 0-.37-.01-.56.84-.6 1.56-1.36 2.14-2.23Z"/></svg>
                        </a>
                        <a href="https://wa.me/573209360634" target="_blank" class="hover:text-white" aria-label="WhatsApp">
                            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12.01 2c-5.52 0-10 4.48-10 10 0 1.95.56 3.83 1.6 5.46L2 22l4.54-1.6C7.97 21.43 9.94 22 12.01 22c5.52 0 10-4.48 10-10S17.53 2 12.01 2Zm3.17 14.86c-.19.34-.66.42-.98.22-.52-.33-1.46-.95-1.93-1.12-.46-.17-.8-.26-1.14.22-.33.48-.68 1.1-.96 1.25-.28.15-.55.15-1.03-.09-1.57-.78-3.08-2.61-3.85-4.32-.23-.52-.01-.8.21-.99.19-.18.42-.32.6-.53.19-.21.25-.36.37-.58.12-.22.06-.41-.03-.58-.09-.17-.79-1.91-1.08-2.6-.26-.64-.52-.55-.71-.56-.17 0-.36 0-.54.03-.18.03-.47.16-.72.41-.26.25-.78.76-.78 1.87 0 1.11.8 2.16 1.15 2.59.34.44 1.57 2.45 3.8 3.39 2.23.94 2.68.79 3.19.74.51-.05 1.63-.67 1.86-1.37.23-.7-.01-1.3-.09-1.45-.09-.14-.23-.23-.48-.36Z"/></svg>
                        </a>
                        <!-- Puedes añadir más redes como Instagram o LinkedIn si las tienes -->
                    </div>
                </div>

                <!-- Col 2: Links Rápidos --><div>
                    <h4 class="text-sm font-semibold text-gray-100 uppercase tracking-wider">Links Rápidos</h4>
                    <ul class="mt-4 space-y-3">
                        <li><a href="#mision" class="hover:text-white">Nuestra Misión</a></li>
                        <li><a href="#modelo" class="hover:text-white">Nuestro Modelo</a></li>
                        <li><a href="#condiciones" class="hover:text-white">Qué Donar</a></li>
                        <li><a href="#formularios" class="hover:text-white">Donar/Recibir</a></li>
                    </ul>
                </div>
                
                <!-- Col 3: Contacto --><div>
                    <h4 class="text-sm font-semibold text-gray-100 uppercase tracking-wider">Contacto</h4>
                    <ul class="mt-4 space-y-3">
                        <li><a href="mailto:info@solydar.org" class="hover:text-white">info@solydar.org</a></li>
                        <li><a href="https://wa.me/573209360634" target="_blank" class="hover:text-white">+57 (320) 936-0634 (WhatsApp)</a></li>
                        <li><span class="text-gray-400">Dirección Sede:</span></li>
                        <li><span class="hover:text-white">Carrera 15 # 16a-14 oficina 708</span></li>
                        <li><span class="hover:text-white">Duitama Boyacá</span></li>
                    </ul>
                </div>

                <!-- Col 4: Legal --><div>
                    <h4 class="text-sm font-semibold text-gray-100 uppercase tracking-wider">Legal</h4>
                    <ul class="mt-4 space-y-3">
                        <li><a href="#" class="hover:text-white">Política de Privacidad</a></li>
                        <li><a href="#" class="hover:text-white">Términos de Uso</a></li>
                    </ul>
                </div>
            </div>

            <!-- Copyright --><div class="mt-12 border-t border-gray-700 pt-8 text-center">
                <p class="text-sm">&copy; 2025 Fundación Solydar. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>


    <!-- ===== SCRIPT DE JAVASCRIPT Y FIREBASE ===== --><script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, collection, addDoc, doc, setLogLevel } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // Usamos setLogLevel para ver logs de Firebase en consola
        setLogLevel('Debug');

        // --- 1. SETUP DE FIREBASE ---
        const appId = typeof __app_id !== 'undefined' ? __app_id : 'default-solydar-app-id';
        const firebaseConfig = typeof __firebase_config !== 'undefined' ? JSON.parse(__firebase_config) : {};
        const authToken = typeof __initial_auth_token !== 'undefined' ? __initial_auth_token : null;

        let db, auth;

        async function initializeFirebase() {
            try {
                const app = initializeApp(firebaseConfig);
                db = getFirestore(app);
                auth = getAuth(app);

                if (authToken) {
                    await signInWithCustomToken(auth, authToken);
                    console.log("Firebase signed in with custom token.");
                } else {
                    await signInAnonymously(auth);
                    console.log("Firebase signed in anonymously.");
                }

                // Definición de las colecciones públicas (todos pueden donar/solicitar)
                window.DONORS_COLLECTION = `artifacts/${appId}/public/data/donations_solydar`;
                window.RECIPIENTS_COLLECTION = `artifacts/${appId}/public/data/recipients_solydar`;

            } catch (error) {
                console.error("Error al inicializar Firebase o autenticar:", error);
            }
        }
        
        initializeFirebase();

        // --- 2. LÓGICA DE FORMULARIOS ---

        const donorForm = document.getElementById('donor-form');
        const recipientForm = document.getElementById('recipient-form');
        const donorMessage = document.getElementById('donor-message');
        const recipientMessage = document.getElementById('recipient-message');
        const donorSubmitBtn = document.getElementById('donor-submit-btn');
        const recipientSubmitBtn = document.getElementById('recipient-submit-btn');


        async function handleFormSubmit(event, formType) {
            event.preventDefault();

            const form = event.target;
            const submitBtn = formType === 'donor' ? donorSubmitBtn : recipientSubmitBtn;
            const messageElement = formType === 'donor' ? donorMessage : recipientMessage;
            const collectionPath = formType === 'donor' ? window.DONORS_COLLECTION : window.RECIPIENTS_COLLECTION;
            
            submitBtn.disabled = true;
            submitBtn.textContent = "Enviando...";
            messageElement.classList.add('hidden');

            const formData = {};
            new FormData(form).forEach((value, key) => {
                formData[key] = value;
            });

            // Añadir metadatos
            formData.submittedAt = new Date().toISOString();
            formData.userId = auth.currentUser ? auth.currentUser.uid : 'anonymous';

            // Adaptar los nombres de campos para un formato más limpio en Firestore
            let dataToSave = {};

            if (formType === 'donor') {
                dataToSave = {
                    nombre_donante: formData.donor_name,
                    email: formData.donor_email,
                    telefono: formData.donor_phone,
                    ciudad: formData.donor_city,
                    articulo_a_donar: formData.donor_article,
                    fecha_registro: formData.submittedAt,
                    userId: formData.userId
                };
            } else {
                dataToSave = {
                    nombre_padre_tutor: formData.recipient_name,
                    email: formData.recipient_email,
                    telefono: formData.recipient_phone,
                    ciudad: formData.recipient_city,
                    cantidad_hijos_0a5: parseInt(formData.recipient_child_count, 10),
                    nombre_hijo: formData.recipient_child_name,
                    edad_hijo: parseInt(formData.recipient_child_age, 10),
                    fecha_registro: formData.submittedAt,
                    userId: formData.userId
                };
            }

            try {
                // Si la DB no está lista, intentamos inicializarla de nuevo (seguro)
                if (!db) {
                    await initializeFirebase();
                }

                await addDoc(collection(db, collectionPath), dataToSave);

                messageElement.textContent = "¡Gracias! Tu solicitud ha sido enviada con éxito. Nos pondremos en contacto pronto.";
                messageElement.classList.remove('hidden', 'bg-red-100', 'text-red-700');
                messageElement.classList.add('bg-green-100', 'text-green-700');
                form.reset();

            } catch (e) {
                console.error("Error adding document: ", e);
                messageElement.textContent = "Error al enviar la solicitud. Por favor, revisa tu conexión o intenta más tarde. Detalle: " + e.message;
                messageElement.classList.remove('hidden', 'bg-green-100', 'text-green-700');
                messageElement.classList.add('bg-red-100', 'text-red-700');

            } finally {
                submitBtn.disabled = false;
                submitBtn.textContent = formType === 'donor' ? "Enviar Oferta de Donación" : "Enviar Solicitud de Ayuda";
            }
        }

        if (donorForm) donorForm.addEventListener('submit', (e) => handleFormSubmit(e, 'donor'));
        if (recipientForm) recipientForm.addEventListener('submit', (e) => handleFormSubmit(e, 'recipient'));


        // --- 3. LÓGICA DE PESTAÑAS (TABS) ---

        const tabButtons = document.querySelectorAll('.tab-button');
        const donorContainer = document.getElementById('donor-form-container');
        const recipientContainer = document.getElementById('recipient-form-container');

        tabButtons.forEach(button => {
            button.addEventListener('click', () => {
                const targetForm = button.getAttribute('data-form');

                // Quita la clase 'active' de todos los botones
                tabButtons.forEach(btn => btn.classList.remove('active'));
                
                // Añade la clase 'active' al botón clickeado
                button.classList.add('active');

                // Muestra u oculta los contenedores de formulario
                if (targetForm === 'donor') {
                    donorContainer.classList.remove('hidden');
                    recipientContainer.classList.add('hidden');
                } else {
                    donorContainer.classList.add('hidden');
                    recipientContainer.classList.remove('hidden');
                }
            });
        });


        // --- 4. LÓGICA DE NAVEGACIÓN MÓVIL (Existente, se mantiene) ---
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const menuIcon = document.getElementById('menu-icon');
        const closeIcon = document.getElementById('close-icon');

        if(menuBtn) {
             menuBtn.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
                menuIcon.classList.toggle('hidden');
                closeIcon.classList.toggle('hidden');
            });
        }
       

        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuIcon.classList.remove('hidden');
                closeIcon.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
