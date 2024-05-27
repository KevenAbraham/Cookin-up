<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

export default {
  components: { Banner, ConteudoPrincipal }
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
</template>

<style scoped> /*Qualquer estilo que for colocado aqui, afetará somente a esse escopo*/
</style>