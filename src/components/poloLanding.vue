<template>
    <section class="relative min-h-screen bg-[#e7e3db] flex items-center justify-center px-4 overflow-hidden">

        <!-- Header con logo -->
        <!-- Header centrado con logo -->
        <header class="absolute top-0 left-0 w-full flex justify-center py-6 z-20">
            <img src="../assets/img-logo.png" alt="Los Testers Logo" class="h-24 w-auto" />
        </header>


        <!-- Letras gigantes tipo V I S I O N -->
        <h1 class="absolute text-[14vw] font-semibold text-[#3d352c] opacity-20 tracking-[0.3em] select-none">
            404
        </h1>

        <!-- Imagen flotando -->
        <div class="relative z-10 w-full max-w-[500px]">
            <img src="../assets/img-polo-2.png" alt="Polo 404" class="mx-auto w-full object-contain" />
            <p class="text-center font-light text-sm">Precio: S/ 50</p>

        </div>

        <!-- Textos flotantes -->
        <div class="absolute left-6 top-40 md:left-10 md:top-1/3 space-y-2 text-sm text-[#3d352c] font-light">
            <p>- 100% algodón</p>
            <p>- Boxy Fit</p>
        </div>


        <div
            class="absolute right-6 top-40 md:right-10 md:top-1/3 space-y-2 text-sm text-[#3d352c] font-light text-right">
            <p>404 NOT FOUND COLLECTION</p>
            <p>STOCK: 12</p>
            <p>&lt;LT/&gt;</p>
        </div>

        <!-- Botón de WhatsApp -->
        <a href="https://wa.me/51TUNUMERO?text=Hola,%20quiero%20comprar%20el%20polo%20404" target="_blank"
            class="absolute bottom-10 md:right-10 bg-[#1f1f1f] text-white px-6 py-3 rounded-full flex items-center gap-2 hover:bg-black transition z-10">
            <i class="bi bi-whatsapp"></i>
            COMPRAR EN WHATSAPP
        </a>
    </section>
</template>

<script setup lang="ts">
// sin lógica aún
</script>