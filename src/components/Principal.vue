<script>
import NovoComponente from "@/components/NovoComponente.vue";
export default {
  components: { NovoComponente },
};
</script>
<template>
  <main id="content">
    <NovoComponente class="componentNew" />
    <NovoComponente class="componentNew" />
    <NovoComponente class="componentNew" />
    <NovoComponente class="componentNew" />
    <NovoComponente class="componentNew" />
    <NovoComponente class="componentNew" />
  </main>
</template>
<style>
.componentNew {
  background-color: aqua;
}
</style>
