<template>
    <!-- source:https://codepen.io/owaiswiz/pen/jOPvEPB -->
<form>
    <div class="min-h-screen bg-gray-100 text-gray-900 flex justify-center">
     <div class="max-w-screen-xl m-0 sm:m-10 bg-white shadow sm:rounded-lg flex justify-center flex-1">
         <div class="lg:w-1/2 xl:w-5/12 p-6 sm:p-12">
             <div>
                 <img src=""
                     class="w-32 mx-auto" />
             </div>
             <div class="mt-12 flex flex-col items-center">
                 <h1 class="text-2xl xl:text-3xl font-extrabold">
                     Inicia Sesión
                 </h1>
                 <div class="w-full flex-1 mt-8">
                     <div class="flex flex-col items-center"> 

                     </div>
 
                     <div class="mx-auto max-w-xs">
                         <input
                             class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white"
                             type="email" placeholder="Correo Electronico" />
                         <input
                             class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5"
                             type="password" placeholder="Contraseña" />
                         <input
                             class="w-full px-8 py-4 rounded-lg font-medium bg-gray-100 border border-gray-200 placeholder-gray-500 text-sm focus:outline-none focus:border-gray-400 focus:bg-white mt-5"
                             type="password" placeholder="Repetir contraseña" />
                         
                         <a href="/register">
                             <button
                             class="mt-5 tracking-wide font-semibold bg-green-500 text-gray-100 w-full py-4 rounded-lg hover:bg-green-700 transition-all duration-300 ease-in-out flex items-center justify-center focus:shadow-outline focus:outline-none">
                             <svg class="w-6 h-6 -ml-2" fill="none" stroke="currentColor" stroke-width="2"
                                 stroke-linecap="round" stroke-linejoin="round">
                                 <path d="M16 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2" />
                                 <circle cx="8.5" cy="7" r="4" />
                                 <path d="M20 8v6M23 11h-6" />
                             </svg>
                             <span class="ml-3">
                                 Registrate
                             </span>
                         </button>
                         </a>
                        
                     </div>
                 </div>
             </div>
         </div>
         
     </div>
 </div>
</form>
 </template>