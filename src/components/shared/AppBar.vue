<template>
  <div class="">
    <nav
      class="relative flex items-center justify-between sm:h-8 lg:justify-start"
    >
      <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-1">
        <div class="flex items-center justify-between w-full md:w-auto">
          <a href="#" aria-label="Home">
            <img
              class="h-5 w-auto sm:h-12"
              src="http://portal.unemat.br/imagens/logo-unemat-maldonado.png"
              alt="Logo"
            />
          </a>
          <div class="-mr-2 flex items-center md:hidden">
            <button
              type="button"
              class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 focus:text-gray-500 transition duration-150 ease-in-out"
              id="main-menu"
              aria-label="Main menu"
              aria-haspopup="true"
            >
              <svg
                class="h-6 w-6"
                stroke="currentColor"
                fill="none"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M4 6h16M4 12h16M4 18h16"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
      <div class="hidden md:block md:ml-10 md:pr-2">
        <a
          href="#"
          class="font-medium text-gray-500 hover:text-gray-900 transition duration-150 ease-in-out"
          >UNEMAT</a
        >
        <a
          href="#"
          class="ml-8 font-medium text-gray-500 hover:text-gray-900 transition duration-150 ease-in-out"
          >UNEMAT ADMIN</a
        >

        <a
          href="#"
          class="ml-8 font-medium text-gray-500 hover:text-gray-900 transition duration-150 ease-in-out"
          >E-mail UNEMAT</a
        >
        <a
          href="#"
          class="ml-8 font-medium text-indigo-600 hover:text-indigo-900 transition duration-150 ease-in-out"
          >Login</a
        >
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
