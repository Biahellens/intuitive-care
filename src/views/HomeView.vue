<script setup lang="ts">
import Cards from '@/components/Cards.vue';
</script>

<template>
  <main>
    <div class="search">
      <h3>Relação de Operadoras Ativas ANS</h3>
      <input class="searchANS" placeholder="pesquisar operadoras" />
    </div>
    <Cards />
  </main>
</template>
<style>
  .search {
    min-height: 5rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .searchANS {
    height: 2rem;
    width: 20rem;
    border-radius: 0.5rem;
    text-align: center;
  }

  h3 {
    color: #4682b4;
  }
</style>
