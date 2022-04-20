<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Cabecalho from "@/components/Cabecalho.vue";
import Rodape from "@/components/Rodape.vue";
import Principal from "@/components/Principal.vue";
export default {
  components: { MenuLateral, Principal, Rodape, Cabecalho },
};
</script>
<template>
  <MenuLateral />
  <header id="header">
    <Cabecalho />
  </header>
  <main id="content">
    <Principal />
  </main>
  <footer id="footer">
    <Rodape />
  </footer>
</template>
<style></style>
