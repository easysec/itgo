<template>
  <section id="contact" class="bg-gray-100 py-16">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-3xl font-bold text-green-600">Contáctanos</h2>
      <p class="mt-4 text-gray-700">
        ¿Tienes alguna pregunta o proyecto en mente? Escríbenos, ¡nos encantaría ayudarte!
      </p>
      <form action="#" method="POST" class="mt-8 max-w-lg mx-auto">
        <div class="mb-4">
          <input
            type="text"
            name="name"
            placeholder="Tu Nombre"
            class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring focus:ring-green-600"
          />
        </div>
        <div class="mb-4">
          <input
            type="email"
            name="email"
            placeholder="Tu Correo Electrónico"
            class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring focus:ring-green-600"
          />
        </div>
        <div class="mb-4">
          <textarea
            name="message"
            rows="4"
            placeholder="Tu Mensaje"
            class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring focus:ring-green-600"
          ></textarea>
        </div>
        <button
          type="submit"
          class="px-6 py-3 bg-green-600 text-white rounded-lg shadow-md hover:bg-green-700"
        >
          Enviar Mensaje
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

<style scoped>
/* Estilos adicionales si los necesitas */
</style>
