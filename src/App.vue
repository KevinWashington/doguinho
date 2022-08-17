<template>
  <div id="topo">
    <Header />
    <div class="container">
      <Main />
      <Servicos />
      <Prices />
      <Faq />
      <Contact />
    </div>
    <Footer />
  </div>
</template>

<script>

import Header from "./components/header.vue";
import Main from "./components/main.vue";
import Servicos from "./components/servicos.vue";
import Prices from "./components/prices.vue";
import Faq from "./components/faq.vue";
import Contact from "./components/contact.vue";
import Footer from "./components/footer.vue";


export default {
  name: "App",
  components: {
    Header,
    Main,
    Servicos,
    Prices,
    Faq,
    Contact,
    Footer
}
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
</style>
