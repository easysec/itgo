<template>
    <section id="contact" class="py-12 bg-white">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold text-green-700">Contáctanos</h2>
        <form class="mt-6 max-w-lg mx-auto">
          <input
            type="text"
            placeholder="Tu Nombre"
            class="w-full p-3 border border-gray-300 rounded mb-4"
          />
          <input
            type="email"
            placeholder="Tu Email"
            class="w-full p-3 border border-gray-300 rounded mb-4"
          />
          <textarea
            placeholder="Tu Mensaje"
            rows="4"
            class="w-full p-3 border border-gray-300 rounded mb-4"
          ></textarea>
          <button
            type="submit"
            class="bg-green-600 text-white px-6 py-3 rounded hover:bg-green-700"
          >
            Enviar
          </button>
        </form>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: "Contact",
  };
  </script>
  