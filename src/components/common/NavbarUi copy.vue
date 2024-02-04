<template>
    <Disclosure as="nav" class=" max-w-7xl bg-white xl:max-w-screen-2xl " v-slot="{ open }">
      <div class="mx-auto px-2 backdrop-blur-2xl md:backdrop-blur-none w-full sm:px-6 lg:px-8 text-base md:pt-10 fixed w-full z-20 ">
        <div class="relative flex w-full  lg:w-2/4  mx-auto  h-16 items-center justify-between backdrop-blur-2xl rounded-full md:border md:border-zinc-600/25 px-16 ">
          <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
            <!-- Mobile menu button-->
            <DisclosureButton class="relative inline-flex items-center justify-center rounded-md p-2 py-1 text-gray-400 hover:bg-gray-700 hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white ">
              <span class="absolute -inset-0.5" />
              <span class="sr-only">Open main menu</span>
              <Bars3Icon v-if="!open" class="block h-6 w-6" aria-hidden="true" />
              <XMarkIcon v-else class="block h-6 w-6" aria-hidden="true" />
            </DisclosureButton>
          </div>
          <div class="flex flex-1 items-center justify-center z-20 h-full sm:items-stretch sm:justify-start">
            <div class="flex flex-shrink-0 items-center">
              <img class="h-8 w-auto" src="@/assets/images/amperechain.png" alt="Your Company" />
            </div>
            <div class="hidden sm:ml-6 sm:block mx-auto flex-1 text-center ">
              <div class="flex md:justify-center space-x-4">
                <a v-for="item in navigation" :key="item.name" :href="item.href" :class="[item.current ? 'bg-gray-900 text-white' : 'text-gray-300 hover:bg-gray-700 hover:text-white', 'rounded-full px-3 py-1 text-sm sm:text-base font-medium']" :aria-current="item.current ? 'page' : undefined">{{ item.name }}</a>
              </div>
            </div>
          </div>
         
        </div>
      </div>
  
      <DisclosurePanel class="sm:hidden backdrop-blur-2xl h-full">
        <div class="space-y-1 px-2 pb-3 pt-2">
          <DisclosureButton v-for="item in navigation" :key="item.name" as="a" :href="item.href" :class="[item.current ? 'bg-gray-900 text-white' : 'text-gray-300 hover:bg-gray-700 hover:text-white', 'block rounded-full px-3 py-1 text-base font-medium']" :aria-current="item.current ? 'page' : undefined">{{ item.name }}</DisclosureButton>
        </div>
      </DisclosurePanel>
    </Disclosure>
  </template>
  
  <script setup>
  
  import { Disclosure, DisclosureButton, DisclosurePanel, } from '@headlessui/vue'
  import { Bars3Icon,  XMarkIcon } from '@heroicons/vue/24/outline'
  
  const navigation = [
    { name: 'Home', href: '#', current: true },
    { name: 'Feature', href: '#', current: false },
    { name: 'Tokenomics', href: '#', current: false },
    { name: 'Timeline', href: '#', current: false },
  ]
  </script>

  