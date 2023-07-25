<!-- eslint-disable prettier/prettier -->
<script setup lang="ts">
import Cards from '@/components/cardComponent/CardComponent.vue';
</script>
<!-- eslint-disable prettier/prettier -->
<template>
  <main>
  <div class='header'>
    <div class="search">
      <h3>Relação de Operadoras Ativas ANS</h3>
      <input class="searchANS" placeholder="pesquisar operadoras" />
    </div>
  </div>
  <div class="main">
    <Cards />
  </div>
  </main>
</template>
<!-- eslint-disable prettier/prettier -->
<style>
  .header{
    min-height: 5rem;
    display: flex;
    width: 100%;
  }
  .search {
    width: 100%;
    display: flex;
    justify-content: center;
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

  .main {
    display: flex;
    flex-wrap: wrap;
  }
</style>
