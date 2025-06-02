<template> 
    <nav class="bg-violet-600 border-pink-400 p-4">
        <div class="max-w-screen-xl flex items-center justify-between mx-auto">
            <a href="" class="text-white font-bold px-12 text-3xl">VueStore</a>
            <button data-collapse-toggle="navbar-dropdown" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-white rounded-lg md:hidden hover:bg-white focus:outline-none focus:ring-2 focus:ring-white dark:text-white dark:hover:bg-violet-600 dark:focus:ring-white" aria-controls="navbar-dropdown" aria-expanded="false">
                <span class="sr-only">Menu</span>
                <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
                </svg>
            </button>
            <div class="hidden w-full md:block md:w-auto" id="navbar-dropdown">
                <ul class="flex flex-col font-medium p-4 md:p-0 mt-4 border border-white rounded-lg bg-white md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0 md:bg-white dark:bg-white md:dark:bg-violet-600 dark:border-white">
                    <li>
                    <router-link to="/home" class="no-underline text-white font-bold">Produtos</router-link>
                    </li>
                    <li>
                        <button id="dropdownNavbarLink" data-dropdown-toggle="dropdownNavbar" class="flex items-center justify-between w-full py-2 px-3 text-white rounded-sm hover:bg-white md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 md:w-auto dark:text-white md:dark:hover:text-blue-500 dark:focus:text-white dark:border-gray-700 dark:hover:bg-gray-700 md:dark:hover:bg-transparent">Categorias <svg class="w-2.5 h-2.5 ms-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
                            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 4 4 4-4"/>
                            </svg>
                        </button>

                        <div id="dropdownNavbar" class="z-10 hidden font-normal bg-white divide-y divide-gray-100 rounded-lg shadow-sm w-44 dark:bg-gray-700 dark:divide-gray-600">
                            <ul class="py-2 text-sm text-black dark:text-violet-400" aria-labelledby="dropdownLargeButton">
                                <li>
                                    Frutas
                                </li>
                                <li>
                                    Carros
                                </li>
                                <li>
                                    Eletrodomesticos
                                </li>
                                <li>
                                    blabla
                                </li>
                            </ul>
                        </div>

                    </li>
                </ul>
            </div>

            <label for="default-search" class="mb-2 text-sm font-medium text-black sr-only">Buscar</label>
            <div class="relative">
                <div class="absolute flex items-center inset-y-0 start-0 ps-3 pointer-events-none">
                    <svg class="w-4 h-4 text-black" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z"/>
                    </svg>
                </div>
                <input type="search" id="default-search" class="rounded block w-full p-2 ps-10 text-black" placeholder="Buscar"/>
            </div>

        </div>       
    </nav>
</template>