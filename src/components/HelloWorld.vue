<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  
<nav class="px-2 bg-white border-gray-200 dark:bg-gray-900 dark:border-gray-700">
  <div class="container flex flex-wrap items-center justify-between mx-auto">
    <a href="#" class="flex items-center">
        <img src="@/assets/logotecmotul.png" class="w-30 h-20" alt="logotecmotul" />
        <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white"></span>
    </a>
     <button data-collapse-toggle="navbar-dropdown" type="button" class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600">
    </button>
    <div class="hidden w-full md:block md:w-auto" id="navbar-dropdown">
      <ul class="flex flex-col p-4 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
        <li>
          <img src="@/assets/logoisclab.png" class="h-6 mr-3 sm:h-10 " alt="logoisclab"  />
          <a href="#" class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-white dark:bg-blue-600 md:dark:bg-transparent" aria-current="page">contacto@isclab.com.mx</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

</template>