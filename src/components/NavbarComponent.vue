<template>
    <nav class="bg-black text-white py-4 px-8 flex justify-center items-center border">
        <ul class="flex gap-6">
            <li>
                <router-link to="/home" class="hover:underline">Home</router-link>
            </li>

            <li>
                <router-link to="/about" class="hover:underline">Sobre Mim</router-link>
            </li>

            <li>
                <router-link to="/contato" class="hover:underline">Contato</router-link>
            </li>
        </ul>
    </nav>
</template>