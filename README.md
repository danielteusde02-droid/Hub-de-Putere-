<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Puterea Camionului - Invertoare & Accesorii</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind for Inter font and theme colors -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary-dark': '#1c1917', // Stone-900 / Very dark, almost black
                        'secondary-dark': '#292524', // Stone-800 / Slightly lighter for cards
                        'accent-color': '#f97316', // Orange-600 / Bright orange for power/attention
                        'soft-text': '#d4d4d8', // Stone-300 / Light gray for text
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
            <nav class="hidden md:flex space-x-6">
                <a href="#produse" class="text-soft-text hover:text-accent-color transition duration-300 font-medium">Produse</a>
                <a href="#invertoare" class="text-soft-text hover:text-accent-color transition duration-300 font-medium">Invertoare</a>
                <a href="#accesorii" class="text-soft-text hover:text-accent-color transition duration-300 font-medium">Accesorii</a>
                <a href="#contact" class="px-3 py-1 bg-accent-color text-primary-dark rounded-md hover:bg-orange-500 transition duration-300 font-semibold">Contact</a>
            </nav>
            <!-- Mobile Menu Placeholder -->
            <button class="md:hidden text-soft-text p-2 rounded-lg hover:bg-secondary-dark transition duration-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="relative py-24 md:py-32 flex items-center justify-center text-center overflow-hidden">
            <div class="absolute inset-0 bg-secondary-dark/50" style="background-image: url('https://placehold.co/1920x800/0c0a09/f97316?text=Camion+pe+Autostrada'); background-blend-mode: multiply; background-size: cover; background-position: center;"></div>
            <div class="relative z-10 max-w-4xl px-4">
                <span class="text-xl font-medium text-accent-color uppercase tracking-widest block mb-4">Soluția ta completă pe șosea</span>
                <h1 class="text-5xl sm:text-6xl lg:text-7xl font-extrabold mb-6 leading-tight text-white">
                    Invertoare și <span class="text-accent-color">Echipamente Premium</span> pentru Camionul Tău
                </h1>
                <p class="text-lg sm:text-xl mb-10 text-gray-200 max-w-2xl mx-auto">
                    Transformăm puterea bateriei în confort: găsește cele mai fiabile invertoare, iluminare LED și accesorii esențiale.
                </p>
                <div class="space-y-4 sm:space-y-0 sm:space-x-6">
                    <a href="#produse" class="inline-block px-8 py-3 text-lg font-bold bg-accent-color text-primary-dark rounded-xl shadow-2xl hover:bg-orange-500 transition duration-300 transform hover:scale-105">
                        Vezi Oferta Completă
                    </a>
                </div>
            </div>
        </section>

        <!-- Categories / Main Products Section -->
        <section id="produse" class="py-16 md:py-24">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center mb-12 text-white">Gama Noastră de Produse</h2>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

                    <!-- Category Card 1: Inverters -->
                    <a href="#invertoare" class="block group bg-secondary-dark rounded-xl p-6 shadow-2xl border-b-4 border-accent-color hover:shadow-accent-color/50 transition duration-500 transform hover:-translate-y-1">
                        <div class="text-center">
                            <!-- Icon Placeholder (could be a battery/plug icon) -->
                            <svg class="h-12 w-12 text-accent-color mx-auto mb-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z" />
                            </svg>
                            <h3 class="text-2xl font-bold text-white mb-2">Invertoare de Putere</h3>
                            <p class="text-soft-text text-sm">Sinus Pur sau Sinus Modificat. Esențiale pentru laptopuri, frigidere și unelte electrice.</p>
                            <span class="mt-4 inline-block text-accent-color group-hover:underline font-semibold">Explorează &rarr;</span>
                        </div>
                    </a>

                    <!-- Category Card 2: Lighting/LED -->
                    <a href="#iluminare" class="block group bg-secondary-dark rounded-xl p-6 shadow-2xl border-b-4 border-gray-500 hover:shadow-gray-500/50 transition duration-500 transform hover:-translate-y-1">
                        <div class="text-center">
                            <!-- Icon Placeholder (could be a lightbulb icon) -->
                            <svg class="h-12 w-12 text-gray-400 mx-auto mb-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M9 19V6l12-3v14c0 1.1-1.1 2-2 2H9z" />
                            </svg>
                            <h3 class="text-2xl font-bold text-white mb-2">Iluminare și Siguranță</h3>
                            <p class="text-soft-text text-sm">Faruri auxiliare, benzi LED și lămpi de avertizare. Vizibilitate maximă în orice condiții.</p>
                            <span class="mt-4 inline-block text-gray-400 group-hover:underline font-semibold">Explorează &rarr;</span>
                        </div>
                    </a>

                    <!-- Category Card 3: General Accessories -->
                    <a href="#accesorii" class="block group bg-secondary-dark rounded-xl p-6 shadow-2xl border-b-4 border-amber-600 hover:shadow-amber-600/50 transition duration-500 transform hover:-translate-y-1">
                        <div class="text-center">
                            <!-- Icon Placeholder (could be a wrench icon) -->
                            <svg class="h-12 w-12 text-amber-600 mx-auto mb-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.942 3.33.644 2.896 2.288a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.942 1.543-.644 3.33-2.288 2.896a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.942-3.33-.644-2.896-2.288a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.942-1.543.644-3.33 2.288-2.896a1.724 1.724 0 002.572-1.065z" />
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                            </svg>
                            <h3 class="text-2xl font-bold text-white mb-2">Diverse Accesorii</h3>
                            <p class="text-soft-text text-sm">Cabluri de pornire, prize USB, sisteme de monitorizare a bateriei și piese de întreținere.</p>
                            <span class="mt-4 inline-block text-amber-600 group-hover:underline font-semibold">Explorează &rarr;</span>
                        </div>
                    </a>
                </div>
            </div>
        </section>

        <!-- Featured Products Section (Inverters) -->
        <section id="invertoare" class="py-16 md:py-24 bg-secondary-dark/50">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center mb-16 text-white border-b-2 border-accent-color/50 pb-2 inline-block mx-auto">Invertoare Recomandate</h2>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8">
                    <!-- Product Card 1: High Power Inverter -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-gray-700 hover:border-accent-color transition duration-300">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Invertor+3000W" alt="Invertor Sinus Pur 3000W" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                        <h3 class="text-xl font-semibold text-white truncate">Invertor Sinus Pur 3000W</h3>
                        <p class="text-accent-color font-bold text-2xl my-2">2.499 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">Ideal pentru aparate sensibile (laptop, TV, espressoare). Siguranță maximă.</p>
                        <button class="mt-4 w-full py-2 bg-accent-color text-primary-dark rounded-lg font-semibold hover:bg-orange-500 transition duration-300">
                            Adaugă în Coș
                        </button>
                    </div>

                    <!-- Product Card 2: Medium Power Inverter -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-gray-700 hover:border-accent-color transition duration-300">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Invertor+1500W" alt="Invertor Sinus Modificat 1500W" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                        <h3 class="text-xl font-semibold text-white truncate">Invertor Sinus Modificat 1500W</h3>
                        <p class="text-accent-color font-bold text-2xl my-2">599 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">O soluție economică pentru becuri și încărcătoare de bază.</p>
                        <button class="mt-4 w-full py-2 bg-accent-color text-primary-dark rounded-lg font-semibold hover:bg-orange-500 transition duration-300">
                            Adaugă în Coș
                        </button>
                    </div>

                    <!-- Product Card 3: Compact Inverter -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-gray-700 hover:border-accent-color transition duration-300">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Invertor+300W" alt="Invertor Compact 300W" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                        <h3 class="text-xl font-semibold text-white truncate">Invertor Compact 300W</h3>
                        <p class="text-accent-color font-bold text-2xl my-2">249 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">Mufă brichetă, perfect pentru încărcarea rapidă a dispozitivelor mobile.</p>
                        <button class="mt-4 w-full py-2 bg-accent-color text-primary-dark rounded-lg font-semibold hover:bg-orange-500 transition duration-300">
                            Adaugă în Coș
                        </button>
                    </div>

                    <!-- Product Card 4: Battery Charger (Accessory example) -->
                    <div class="bg-secondary-dark rounded-xl shadow-2xl overflow-hidden p-6 border border-gray-700 hover:border-accent-color transition duration-300">
                        <img src="https://placehold.co/400x300/1e293b/ffffff?text=Incarcator+Baterie" alt="Încărcător Inteligent Baterie" class="w-full h-auto rounded-lg mb-4 aspect-[4/3] object-cover">
                        <h3 class="text-xl font-semibold text-white truncate">Încărcător Inteligent 24V</h3>
                        <p class="text-accent-color font-bold text-2xl my-2">499 RON</p>
                        <p class="text-sm text-soft-text h-10 overflow-hidden">Menține bateria în condiții optime pe termen lung. Protecție la suprasarcină.</p>
                        <button class="mt-4 w-full py-2 bg-accent-color text-primary-dark rounded-lg font-semibold hover:bg-orange-500 transition duration-300">
                            Adaugă în Coș
                        </button>
                    </div>
                </div>

                <div class="text-center mt-12">
                    <a href="#accesorii" class="inline-block px-6 py-3 border-2 border-accent-color text-accent-color rounded-lg font-semibold hover:bg-accent-color hover:text-primary-dark transition duration-300">
                        Vezi Toate Invertoarele și Echipamentele
                    </a>
                </div>
            </div>
        </section>

        <!-- Trust / Benefits Section -->
        <section class="py-16 md:py-24">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-bold text-center mb-12 text-white">De Ce Să Alegi Puterea Camionului?</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                    <div class="p-6 bg-secondary-dark/50 rounded-xl shadow-inner border-t-4 border-accent-color">
                        <span class="text-3xl font-extrabold text-accent-color block mb-3">100%</span>
                        <h4 class="text-xl font-semibold text-white mb-2">Fiabilitate</h4>
                        <p class="text-sm text-soft-text">Produse testate pentru condiții dure, menite să reziste pe termen lung, indiferent de traseu.</p>
                    </div>
                    <div class="p-6 bg-secondary-dark/50 rounded-xl shadow-inner border-t-4 border-accent-color">
                        <span class="text-3xl font-extrabold text-accent-color block mb-3">24V</span>
                        <h4 class="text-xl font-semibold text-white mb-2">Specializare</h4>
                        <p class="text-sm text-soft-text">Ne concentrăm exclusiv pe nevoile camioanelor și șoferilor profesioniști. Știm ce îți trebuie.</p>
                    </div>
                    <div class="p-6 bg-secondary-dark/50 rounded-xl shadow-inner border-t-4 border-accent-color">
                        <span class="text-3xl font-extrabold text-accent-color block mb-3">Livrare</span>
                        <h4 class="text-xl font-semibold text-white mb-2">Rapidă</h4>
                        <p class="text-sm text-soft-text">Comenzile plasate până la ora 14:00 sunt expediate în aceeași zi. Timpul tău e valoros.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16 md:py-24 bg-secondary-dark">
            <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-2xl">
                <h2 class="text-4xl font-bold text-center mb-12 text-white border-b-2 border-accent-color/50 pb-2 inline-block mx-auto">Contact Rapid</h2>
                <p class="text-center text-soft-text mb-8">
                    Pentru întrebări despre produse, stocuri sau comenzi personalizate, te rugăm să ne contactezi.
                </p>

                <!-- Mock Contact Form -->
                <form class="space-y-6 p-8 rounded-xl shadow-2xl bg-secondary-dark/75 border border-gray-700">
                    <div>
                        <label for="nume" class="block text-sm font-medium text-soft-text mb-1">Numele Tău</label>
                        <input type="text" id="nume" name="nume" placeholder="Ex: Ion Popescu" class="w-full p-3 bg-primary-dark border border-gray-600 rounded-lg focus:ring-accent-color focus:border-accent-color transition duration-300">
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-soft-text mb-1">Email</label>
                        <input type="email" id="email" name="email" placeholder="contact@exemplu.ro" class="w-full p-3 bg-primary-dark border border-gray-600 rounded-lg focus:ring-accent-color focus:border-accent-color transition duration-300">
                    </div>
                    <div>
                        <label for="mesaj" class="block text-sm font-medium text-soft-text mb-1">Mesaj</label>
                        <textarea id="mesaj" name="mesaj" rows="4" placeholder="Întrebarea sau solicitarea ta..." class="w-full p-3 bg-primary-dark border border-gray-600 rounded-lg focus:ring-accent-color focus:border-accent-color transition duration-300"></textarea>
                    </div>
                    <button type="submit" class="w-full px-6 py-3 text-lg font-semibold bg-accent-color text-primary-dark rounded-lg hover:bg-orange-500 transition duration-300 transform hover:scale-[1.01]">
                        Trimite Mesajul
                    </button>
                    <p class="text-center text-xs text-gray-500 pt-2">
                        *Acest formular este doar un model; funcționalitatea de trimitere ar necesita cod suplimentar pe server.
                    </p>
                </form>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-primary-dark border-t border-accent-color/30 py-8">
        <div class="container mx-auto px-4 text-center text-gray-500 text-sm">
            <p>&copy; 2024 Puterea Camionului. Toate drepturile rezervate.</p>
            <div class="mt-4 flex justify-center space-x-6">
                <a href="#" class="hover:text-accent-color transition duration-300">Termeni și Condiții</a>
                <span class="text-gray-700">|</span>
                <a href="mailto:contact@putereacamionului.ro" class="hover:text-accent-color transition duration-300">Email</a>
                <span class="text-gray-700">|</span>
                <a href="#" class="hover:text-accent-color transition duration-300">Facebook</a>
            </div>
        </div>
    </footer>

</body>
</html>

