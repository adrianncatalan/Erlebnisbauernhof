<template>
    <!-- This example requires Tailwind CSS v2.0+ -->
    <div class="bg-white">
        <!-- Header -->
        <div class="relative pb-32 bg-gray-800">
            <div class="absolute inset-0">
                <img class="w-full h-full object-cover" src="https://i.postimg.cc/mZJ0xQRy/gemunden.jpg"
                    alt="Landscape">
                <div class="absolute inset-0 bg-gray-400 mix-blend-multiply" aria-hidden="true"></div>
            </div>
            <div class="relative max-w-7xl mx-auto py-24 px-4 sm:py-32 sm:px-6 lg:px-8">
                <h1 class="text-4xl font-extrabold tracking-tight text-white md:text-5xl lg:text-6xl">Kontakt</h1>
            </div>
        </div>

        <!-- Overlapping cards -->
        <section class="-mt-32 max-w-7xl mx-auto relative z-10 pb-32 px-4 sm:px-6 lg:px-8"
            aria-labelledby="contact-heading">
            <h2 class="sr-only" id="contact-heading">Kontakt</h2>
            <div class="grid grid-cols-1 gap-y-20 lg:grid-cols-3 lg:gap-y-0 lg:gap-x-8">
                <div class="flex flex-col bg-white rounded-2xl shadow-xl">
                    <div class="flex-1 relative pt-16 px-6 pb-8 md:px-8">
                        <div
                            class="absolute top-0 p-5 inline-block bg-gray-200 rounded-xl shadow-lg transform -translate-y-1/2">
                            <!-- Replaced icon with text for "Address" -->
                            <span class="h-10 w-10 text-white">🏠</span>
                        </div>
                        <h3 class="text-xl font-medium text-gray-900">Adresse</h3>
                        <p class="mt-4 text-base text-gray-500">Aschenroth 31 97737 Gemünden</p>
                    </div>
                </div>
                <div class="flex flex-col bg-white rounded-2xl shadow-xl">
                    <div class="flex-1 relative pt-16 px-6 pb-8 md:px-8">
                        <div
                            class="absolute top-0 p-5 inline-block bg-gray-200 rounded-xl shadow-lg transform -translate-y-1/2">
                            <!-- Replaced icon with text for "Email" -->
                            <span class="h-10 w-10 text-white">📧</span>
                        </div>
                        <h3 class="text-xl font-medium text-gray-900">E-Mail</h3>
                        <p class="mt-4 text-base text-gray-500">hubert.froehlich.gmx.de</p>
                    </div>
                </div>

                <div class="flex flex-col bg-white rounded-2xl shadow-xl">
                    <div class="flex-1 relative pt-16 px-6 pb-8 md:px-8">
                        <div
                            class="absolute top-0 p-5 inline-block bg-gray-200 rounded-xl shadow-lg transform -translate-y-1/2">
                            <!-- Replaced icon with text for "Phone" -->
                            <span class="h-10 w-10 text-white">📞</span>
                        </div>
                        <h3 class="text-xl font-medium text-gray-900">Telefon</h3>
                        <p class="mt-4 text-base text-gray-500">0172/8484629</p>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>
