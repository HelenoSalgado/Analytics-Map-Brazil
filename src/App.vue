<script setup lang="ts">
import MapBrazil from './components/MapBrazil.vue';

const states = [
  {
    uf: 'DF',
    value: 43,
  },
  {
    uf: 'MG',
    value: 33,
  },
  {
    uf: 'RS',
    value: 33,
  },
  {
    uf: 'SC',
    value: 33,
  },
  {
    uf: 'MA',
    value: 3,
  },
  {
    uf: 'AM',
    value: 60,
  },
  {
    uf: 'RR',
    value: 21,
  },
  {
    uf: 'TO',
    value: 33,
  },
  {
    uf: 'GO',
    value: 45,
  },
  {
    uf: 'BA',
    value: 25,
  },
  {
    uf: 'SP',
    value: 23,
  },
  {
    uf: 'RN',
    value: 77,
  },
  {
    uf: 'MS',
    value: 12,
  },
  {
    uf: 'RJ',
    value: 100,
  },
  {
    uf: 'PR',
    value: 23,
  },
  {
    uf: 'CE',
    value: 6,
  },
  {
    uf: 'SE',
    value: 5,
  },
  {
    uf: 'PA',
    value: 21,
  },
  {
    uf: 'ES',
    value: 55,
  },
  {
    uf: 'AL',
    value: 45,
  },
  {
    uf: 'PI',
    value: 25,
  },
  {
    uf: 'PE',
    value: 55,
  },
  {
    uf: 'MT',
    value: 88,
  },
  {
    uf: 'AP',
    value: 5,
  },
  {
    uf: 'AC',
    value: 18,
  },
  {
    uf: 'RO',
    value: 2000,
  },
  {
    uf: 'PR',
    value: 5,
  },
];
</script>

<template>
  <MapBrazil :states="states"/>
</template>

<style scoped>
</style>
