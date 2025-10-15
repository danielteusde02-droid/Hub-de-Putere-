<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Puterea Camionului - Invertoare & Accesorii</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons (for modern icons) -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <!-- Configure Tailwind for Inter font and theme colors -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary-dark': '#1c1917', // Very dark, almost black
                        'secondary-dark': '#292524', // Slightly lighter for cards/sections
                        'accent-color': '#f97316', // Bright orange for power/attention
                        'soft-text': '#d4d4d8', // Light gray for text
                        'light-bg': '#3f3f46', // Zinc-700
                    }
                }
            }
        }
    </script>
    <style>
        /* Apply smooth scrolling for internal links */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-primary-dark text-soft-text font-sans antialiased">

    <!-- Sticky Navigation Header -->
    <header class="sticky top-0 z-50 bg-primary-dark/95 backdrop-blur-sm shadow-xl border-b border-accent-color/50">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-extrabold tracking-wider text-accent-color">
                PUTEREA CAMIONULUI
            </a>
            <!-- Desktop Menu -->
            <nav class="hidden md:flex space-x-6">
                <a href="#produse" class="text-soft-text hover:text-accent-color transition duration-300 font-medium">Produse</a>
                <a href="#invertoare" class="text-soft-text hover:text-accent-color transition duration-300 font-medium">Invertoare</a>
                <a href="#accesorii" class="text-soft-text hover:text-accent-color transition duration-300 font-medium">Accesorii</a>
                <a href="#contact" class="px-3 py-2 bg-accent-color text-primary-dark rounded-md hover:bg-orange-500 transition duration-300 font-semibold shadow-md">Contact</a>
            </nav>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" onclick="toggleMenu()" class="md:hidden text-soft-text p-2 rounded-lg hover:bg-secondary-dark transition duration-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </div>
         <!-- Mobile Menu Drawer (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden absolute w-full bg-primary-dark shadow-lg border-t border-accent-color/30">
            <nav class="flex flex-col space-y-2 p-4">
                <a href="#produse" onclick="toggleMenu()" class="block p-2 text-soft-text hover:bg-secondary-dark rounded-md">Produse</a>
                <a href="#invertoare" onclick="toggleMenu()" class="block p-2 text-soft-text hover:bg-secondary-dark rounded-md">Invertoare</a>
                <a href="#accesorii" onclick="toggleMenu()" class="block p-2 text-soft-text hover:bg-secondary-dark rounded-md">Accesorii</a>
                <a href="#contact" onclick="toggleMenu()" class="block p-2 bg-accent-color text-primary-dark rounded-md text-center font-semibold mt-2">Contact</a>
            </nav>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="relative py-24 md:py-32 flex items-center justify-center text-center overflow-hidden">
            <!-- Background Image/Effect with subtle overlay -->
            <div class="absolute inset-0 bg-secondary-dark/60" style="background-image: url('https://placehold.co/1920x800/0c0a09/f97316?text=Camion+pe+Autostrada'); background-blend-mode: multiply; background-size: cover; background-position: center;"></div>
            <div class="relative z-10 max-w-5xl px-4">
                <span class="text-xl font-medium text-soft-text uppercase tracking-widest block mb-4">Confort și Putere, Oriunde</span>
                <h1 class="text-5xl sm:text-6xl lg:text-8xl font-black mb-6 leading-tight text-white drop-shadow-lg">
                    Transformă-ți <span class="text-accent-color">Cabina</span> în Birou și Casă
                </h1>
                <p class="text-lg sm:text-xl mb-10 text-gray-200 max-w-3xl mx-auto">
                    Oferim cele mai fiabile invertoare, de la 300W la 5000W, plus accesorii esențiale pentru orice șofer de camion profesionist.
                </p>
                <div class="space-y-4 sm:space-y-0 sm:space-x-6">
                    <a href="#invertoare" class="inline-block px-10 py-4 text-xl font-bold bg-accent-color text-primary-dark rounded-full shadow-2xl shadow-accent-color/40 hover:bg-orange-500 transition duration-300 transform hover:scale-105">
                        Descoperă Invertoarele
                    </a>
                </div>
            </div>
        </section>

        <!-- Categories / Main Products Section -->
        <section id="produse" class="py-16 md:py-24">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center mb-16 text-white">Gama Noastră Completă</h2>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

                    <!-- Category Card 1: Inverters -->
                    <a href="#invertoare" class="block group bg-secondary-dark rounded-2xl p-8 shadow-2xl border-b-8 border-accent-color hover:shadow-accent-color/50 transition duration-500 transform hover:-translate-y-2">
                        <div class="text-center">
                             <!-- Icon: FlashlightOff (Power) -->
                             <i data-lucide="zap" class="h-12 w-12 text-accent-color mx-auto mb-4 stroke-2"></i>
                            <h3 class="text-2xl font-extrabold text-white mb-2">Invertoare de Putere</h3>
                            <p class="text-soft-text text-base">Sinus Pur, Sinus Modificat, 12V/24V. Calitate superioară pentru echipamente sensibile.</p>
                            <span class="mt-4 inline-block text-accent-color group-hover:underline font-semibold text-lg">Vezi Detalii &rarr;</span>
                        </div>
                    </a>

                    <!-- Category Card 2: Lighting/LED -->
                    <a href="#iluminare" class="block group bg-secondary-dark rounded-2xl p-8 shadow-2xl border-b-8 border-light-bg hover:shadow-light-bg/50 transition duration-500 transform hover:-translate-y-2">
                        <div class="text-center">
                            <!-- Icon: Lightbulb -->
                            <i data-lucide="lightbulb" class="h-12 w-12 text-light-bg mx-auto mb-4 stroke-2"></i>
                            <h3 class="text-2xl font-extrabold text-white mb-2">Iluminare Auxiliară</h3>
                            <p class="text-soft-text text-base">Bare și faruri LED, lămpi de gabarit și semnalizare. Siguranță sporită pe timp de noapte.</p>
                            <span class="mt-4 inline-block text-light-bg group-hover:underline font-semibold text-lg">Vezi Detalii &rarr;</span>
                        </div>
                    </a>

                    <!-- Category Card 3: General Accessories -->
                    <a href="#accesorii" class="block group bg-secondary-dark rounded-2xl p-8 shadow-2xl border-b-8 border-yellow-500 hover:shadow-yellow-500/50 transition duration-500 transform hover:-translate-y-2">
                        <div class="text-center">
                            <!-- Icon: Cog (Settings) -->
                            <i data-lucide="settings" class="h-12 w-12 text-yellow-500 mx-auto mb-4 stroke-2"></i>
                            <h3 class="text-2xl font-extrabold text-white mb-2">Accesorii Utile</h3>
                            <p class="text-soft-text text-base">Cabluri de baterie, prize USB, încărcătoare inteligente și conectori durabili.</p>
                            <span class="mt-4 inline-block text-yellow-500 group-hover:underline font-semibold text-lg">Vezi Detalii &rarr;</span>
                        </div>
                    </a>
                </div>
            </div>
        </section>

        <!-- Featured Products Section (Inverters) -->
        <section id="invertoare" class="py-16 md:py-24 bg-secondary-dark/70">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center mb-16 text-white border-b-2 border-accent-color/50 pb-2 inline-block mx-auto">Top 4 Invertoare</h2>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8">
                    <!-- Product Card 1: High Power Inverter (Sinus Pur) -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-light-bg hover:border-accent-color transition duration-300 transform hover:scale-[1.02]">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Invertor+3000W+PUR" alt="Invertor Sinus Pur 3000W" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                        <span class="inline-block bg-red-600 text-white text-xs font-bold px-2 py-1 rounded-full mb-2">SINUS PUR</span>
                        <h3 class="text-xl font-semibold text-white truncate">Invertor 3000W / 24V</h3>
                        <p class="text-accent-color font-bold text-3xl my-2">2.499 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">Putere de vârf 6000W. O alegere premium pentru frigidere, espressoare și unelte profesionale.</p>
                        <button class="mt-4 w-full py-3 bg-accent-color text-primary-dark rounded-lg font-bold hover:bg-orange-500 transition duration-300 shadow-lg">
                            Cumpără Acum
                        </button>
                    </div>

                    <!-- Product Card 2: Medium Power Inverter (Sinus Modificat) -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-light-bg hover:border-accent-color transition duration-300 transform hover:scale-[1.02]">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Invertor+1500W+MOD" alt="Invertor Sinus Modificat 1500W" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                         <span class="inline-block bg-gray-600 text-white text-xs font-bold px-2 py-1 rounded-full mb-2">SINUS MODIFICAT</span>
                        <h3 class="text-xl font-semibold text-white truncate">Invertor 1500W / 24V</h3>
                        <p class="text-accent-color font-bold text-3xl my-2">599 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">O soluție economică și eficientă pentru încărcarea telefoanelor, laptopurilor și a iluminatului de bază.</p>
                        <button class="mt-4 w-full py-3 bg-accent-color text-primary-dark rounded-lg font-bold hover:bg-orange-500 transition duration-300 shadow-lg">
                            Cumpără Acum
                        </button>
                    </div>

                    <!-- Product Card 3: Compact Inverter (Brichetă) -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-light-bg hover:border-accent-color transition duration-300 transform hover:scale-[1.02]">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Invertor+300W+COMPACT" alt="Invertor Compact 300W" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                        <span class="inline-block bg-green-600 text-white text-xs font-bold px-2 py-1 rounded-full mb-2">PORTABIL</span>
                        <h3 class="text-xl font-semibold text-white truncate">Invertor Compact 300W</h3>
                        <p class="text-accent-color font-bold text-3xl my-2">249 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">Se conectează direct la mufa de brichetă. Perfect pentru încărcarea dispozitivelor mici în mers.</p>
                        <button class="mt-4 w-full py-3 bg-accent-color text-primary-dark rounded-lg font-bold hover:bg-orange-500 transition duration-300 shadow-lg">
                            Cumpără Acum
                        </button>
                    </div>

                    <!-- Product Card 4: Battery Charger (Accessory example) -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-light-bg hover:border-accent-color transition duration-300 transform hover:scale-[1.02]">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Incarcator+Baterie+24V" alt="Încărcător Inteligent Baterie" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                        <span class="inline-block bg-light-bg text-white text-xs font-bold px-2 py-1 rounded-full mb-2">ACCESORIU</span>
                        <h3 class="text-xl font-semibold text-white truncate">Încărcător Inteligent 24V</h3>
                        <p class="text-accent-color font-bold text-3xl my-2">499 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">Menține bateriile în stare optimă. Include mod de desulfatare și protecție totală.</p>
                        <button class="mt-4 w-full py-3 bg-accent-color text-primary-dark rounded-lg font-bold hover:bg-orange-500 transition duration-300 shadow-lg">
                            Cumpără Acum
                        </button>
                    </div>
                </div>

                <div class="text-center mt-16">
                    <a href="#accesorii" class="inline-block px-8 py-3 border-2 border-accent-color text-accent-color rounded-full font-bold hover:bg-accent-color hover:text-primary-dark transition duration-300 text-lg">
                        Vezi Toate Produsele <i data-lucide="arrow-right" class="inline-block h-5 w-5 ml-1"></i>
                    </a>
                </div>
            </div>
        </section>

        <!-- Trust / Benefits Section -->
        <section class="py-16 md:py-24" id="beneficii">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center mb-12 text-white">De Ce Să Alegi Puterea Camionului?</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                    <div class="p-8 bg-secondary-dark rounded-xl shadow-2xl border-t-8 border-accent-color">
                        <i data-lucide="shield-check" class="h-12 w-12 text-accent-color mx-auto mb-4 stroke-2"></i>
                        <h4 class="text-xl font-bold text-white mb-2">Garanție și Siguranță</h4>
                        <p class="text-sm text-soft-text">Toate produsele vin cu garanție extinsă și protecții integrate împotriva supratensiunii și scurtcircuitului.</p>
                    </div>
                    <div class="p-8 bg-secondary-dark rounded-xl shadow-2xl border-t-8 border-accent-color">
                         <i data-lucide="truck" class="h-12 w-12 text-accent-color mx-auto mb-4 stroke-2"></i>
                        <h4 class="text-xl font-bold text-white mb-2">Focus pe 24V</h4>
                        <p class="text-sm text-soft-text">Suntem specializați exclusiv pe sisteme de 24V, asigurând compatibilitate și performanță maximă pentru camioane.</p>
                    </div>
                    <div class="p-8 bg-secondary-dark rounded-xl shadow-2xl border-t-8 border-accent-color">
                        <i data-lucide="fast-forward" class="h-12 w-12 text-accent-color mx-auto mb-4 stroke-2"></i>
                        <h4 class="text-xl font-bold text-white mb-2">Livrare Ultra-Rapidă</h4>
                        <p class="text-sm text-soft-text">Livrare în 24-48 de ore oriunde în țară. Știm că timpul petrecut în parcare costă.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16 md:py-24 bg-primary-dark border-t border-accent-color/30">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-2xl">
                <h2 class="text-4xl font-bold text-center mb-12 text-white border-b-2 border-accent-color/50 pb-2 inline-block mx-auto">Contact Rapid</h2>
                <p class="text-center text-soft-text mb-8">
                    Pentru suport tehnic, comenzi mari sau întrebări, suntem gata să te ajutăm.
                </p>

                <div class="space-y-6 p-8 rounded-xl shadow-2xl bg-secondary-dark border border-gray-700 text-center">
                    <p class="text-lg font-medium text-white">
                        <i data-lucide="mail" class="inline-block h-5 w-5 mr-2 text-accent-color"></i> Adresa de email pentru comenzi:
                    </p>
                    <a href="mailto:comenzi@invertoare-camioane.ro" class="inline-block px-8 py-3 text-xl font-extrabold bg-accent-color text-primary-dark rounded-lg hover:bg-orange-500 transition duration-300 transform hover:scale-[1.01] shadow-xl">
                        comenzi@invertoare-camioane.ro
                    </a>
                    <p class="text-lg font-medium text-white pt-4">
                        <i data-lucide="phone" class="inline-block h-5 w-5 mr-2 text-accent-color"></i> Sau sună-ne: <span class="text-accent-color font-extrabold text-2xl">07XX XXX XXX</span>
                    </p>
                </div>

            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-primary-dark border-t border-accent-color/30 py-8">
        <div class="container mx-auto px-4 text-center text-gray-500 text-sm">
            <p>&copy; 2024 Puterea Camionului. Toate drepturile rezervate. Design creat de Gemini.</p>
            <div class="mt-4 flex justify-center space-x-6">
                <a href="#" class="hover:text-accent-color transition duration-300">Termeni și Condiții</a>
                <span class="text-gray-700">|</span>
                <a href="mailto:contact@putereacamionului.ro" class="hover:text-accent-color transition duration-300">Email Contact</a>
                <span class="text-gray-700">|</span>
                <a href="#" class="hover:text-accent-color transition duration-300">Politica de Confidențialitate</a>
            </div>
        </div>
    </footer>

    <!-- Mobile Menu Toggle Script -->
    <script>
        // Function to toggle the mobile menu visibility
        function toggleMenu() {
            const menu = document.getElementById('mobile-menu');
            const button = document.getElementById('mobile-menu-button');
            menu.classList.toggle('hidden');
            
            // Optionally change the icon based on state (Hamburger <-> Close)
            if (menu.classList.contains('hidden')) {
                button.innerHTML = '<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" /></svg>';
            } else {
                button.innerHTML = '<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" /></svg>';
            }
        }
    </script>
    <script>
        // Initialize Lucide icons after loading the script
        lucide.createIcons();
    </script>

</body>
</html>
