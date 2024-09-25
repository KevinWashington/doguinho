<template>
  <div id="topo">
    <Header />
    <div class="container px-3">
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
.nav-item .nav-link{
    color: #8F61E8 !important;
}
.nav-link.active{
  background-color: #fff !important;
  border: 1px solid #8F61E8;
}

.btn{
  background-color: #8F61E8 !important;
  border: none;
}

.border-primary{
  border: 1px solid #8F61E8 !important;
}

.card-header{
  background-color: #8F61E8 !important;
}
</style>
