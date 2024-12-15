<template>
    <nav class="bg-gradient-to-r from-green-500 via-green-600 to-green-700 text-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex items-center justify-between h-16">
          <!-- Logo -->
          <div class="flex items-center space-x-2">
            <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M9.75 17h4.5M2.25 13.5v-7.5h19.5v7.5M3 17.25h18a.75.75 0 01.75.75v1.5a.75.75 0 01-.75.75H3a.75.75 0 01-.75-.75v-1.5a.75.75 0 01.75-.75z"
              />
            </svg>
            <router-link to="/" class="text-xl font-bold">ITGO</router-link>
          </div>
          <!-- Menu -->
          <div class="hidden md:flex space-x-6">
            <router-link to="/" class="hover:bg-green-800 px-3 py-2 rounded">Home</router-link>
            <router-link to="/about" class="hover:bg-green-800 px-3 py-2 rounded">About</router-link>
            <router-link to="/services" class="hover:bg-green-800 px-3 py-2 rounded">Services</router-link>
            <router-link to="/contact" class="hover:bg-green-800 px-3 py-2 rounded">Contact</router-link>
          </div>
          <!-- Mobile Menu Button -->
          <div class="md:hidden">
            <button @click="toggleMobileMenu" class="focus:outline-none">
              <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
              </svg>
            </button>
          </div>
        </div>
      </div>
      <!-- Mobile Menu -->
      <div v-show="isMobileMenuOpen" class="md:hidden bg-gradient-to-b from-green-500 via-green-600 to-green-700 text-white">
        <router-link to="/" class="block px-4 py-2 hover:bg-green-800">Home</router-link>
        <router-link to="/about" class="block px-4 py-2 hover:bg-green-800">About</router-link>
        <router-link to="/services" class="block px-4 py-2 hover:bg-green-800">Services</router-link>
        <router-link to="/contact" class="block px-4 py-2 hover:bg-green-800">Contact</router-link>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
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
  
  <style scoped>
  /* Opcional para animación */
  </style>
  