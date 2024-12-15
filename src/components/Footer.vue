<template>
  <footer class="bg-green-700 text-white py-8">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex flex-col md:flex-row justify-between items-center">
        <p class="text-sm">&copy; 2024 ITGO. Todos los derechos reservados.</p>
        <div class="flex space-x-6 mt-4 md:mt-0">
          <router-link to="/" class="hover:underline">Home</router-link>
          <router-link to="/about" class="hover:underline">About</router-link>
          <router-link to="/services" class="hover:underline">Services</router-link>
          <router-link to="/contact" class="hover:underline">Contact</router-link>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>
