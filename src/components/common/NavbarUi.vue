<template>
  <nav class="backdrop-blur-xl bg-transparent md:backdrop-blur-lh">
    <div class="mx-auto md:sticky top-0 z-20 w-full  px-2 sm:px-6 lg:px-10  md:mt-10">
      <div class="relative flex  w-full md:w-max  mx-auto  h-16 items-center justify-between md:backdrop-blur-lg  rounded-full md:border md:border-zinc-600/25 px-16">
        <div class="absolute inset-y-0 left-0 flex items-center md:hidden">
          <!-- Mobile menu button-->
          <button
            @click="toggleMobileMenu"
            type="button"
            class="relative inline-flex items-center justify-center rounded-full p-2 text-gray-400 hover:bg-gray-900/25 hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
            aria-controls="mobile-menu"
            :aria-expanded="isMobileMenuOpen.toString()"
          >
            <span class="absolute -inset-0.5"></span>
            <span class="sr-only">Open main menu</span>
            <!-- Icon when menu is closed -->
            <svg
              v-if="!isMobileMenuOpen"
              class="block h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              aria-hidden="true"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
              />
            </svg>
            <!-- Icon when menu is open -->
            <svg
              v-if="isMobileMenuOpen"
              class="hidden h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              aria-hidden="true"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M6 18L18 6M6 6l12 12"
              />
            </svg>
          </button>
        </div>
        <div
          class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start"
        >
          <div class="flex flex-shrink-0 items-center">
            <img
              class="h-8 w-auto"
              src="@/assets/images/amperechain.png" 
              alt="AmpereChain"
            />
          </div>
          <div class="hidden md:ml-6 md:block">
            <div class="flex space-x-4">
            
              <a
                href="#"
                class="bg-gray-900/75 text-white rounded-full px-3 py-2 text-sm font-medium"
                aria-current="page"
                >Home </a
              >
              <a
                href="#"
                class="text-gray-300 hover:bg-gray-900/25 hover:text-white rounded-full px-3 py-2 text-sm font-medium"
                >Feature</a
              >
              <a
                href="#"
                class="text-gray-300 hover:bg-gray-900/25 hover:text-white rounded-full px-3 py-2 text-sm font-medium"
                >Tokenomics</a
              >
              <a
                href="#"
                class="text-gray-300 hover:bg-gray-900/25 hover:text-white rounded-full px-3 py-2 text-sm font-medium"
                >Ecosystem</a
              >

              <a
                href="#"
                class="text-gray-300 hover:bg-gray-900/25 hover:text-white rounded-full px-3 py-2 text-sm font-medium"
                >Timeline</a
              >

              <a
                href="#"
                class="text-gray-300 hover:bg-gray-900/25 hover:text-white rounded-full px-3 py-2 text-sm font-medium"
                >Contact</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Mobile menu, show/hide based on menu state. -->
    <div v-show="isMobileMenuOpen" class="md:hidden" id="mobile-menu">
      <div class="space-y-1 px-2 pb-3 pt-2">
        <!-- Current: "bg-gray-900/75 text-white", Default: "text-gray-300 hover:bg-gray-900/25 hover:text-white" -->
        <a
          href="#"
          class="bg-gray-900/75 text-white block rounded-full px-3 py-2 text-base font-medium"
          aria-current="page"
          >Home</a
        >
        <a
          href="#"
          class="text-gray-300 hover:bg-gray-900/25 hover:text-white block rounded-full px-3 py-2 text-base font-medium"
          >Features</a
        >
        <a
          href="#"
          class="text-gray-300 hover:bg-gray-900/25 hover:text-white block rounded-full px-3 py-2 text-base font-medium"
          >Tokenomics</a
        >
        <a
          href="#"
          class="text-gray-300 hover:bg-gray-900/25 hover:text-white block rounded-full px-3 py-2 text-base font-medium"
          >Ecosystem</a
        > <a
          href="#"
          class="text-gray-300 hover:bg-gray-900/25 hover:text-white block rounded-full px-3 py-2 text-base font-medium"
          >Timeline</a
        > <a
          href="#"
          class="text-gray-300 hover:bg-gray-900/25 hover:text-white block rounded-full px-3 py-2 text-base font-medium"
          >Contact</a
        >
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      isMobileMenuOpen: false,
    };
  },
  methods: {
    toggleMobileMenu() {
      this.isMobileMenuOpen = !this.isMobileMenuOpen;
    },
  },
};
</script>
