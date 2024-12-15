<template>
  <div class="bg-gray-50 text-gray-900">
    <AppHeader />
    <main class="container mx-auto p-6">
      <AboutUs />
      <Services />
      <Contact />
      <Tickets />
    </main>
    <Footer />
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
import AboutUs from "@/views/AboutUs.vue";
import Services from "@/views/Services.vue";
import Contact from "@/views/Contact.vue";
import Tickets from "@/views/Tickets.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AboutUs,
    Services,
    Contact,
    Tickets,
    Footer,
  },
};
</script>
