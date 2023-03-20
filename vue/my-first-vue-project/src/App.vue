<script setup>

import { ref } from 'vue';
const email = ref('');
const fornavn = ref('');
const efternavn = ref('');
const telefon = ref('');

</script>

<template>
  <div>
    Hejsa
  </div>

  <div>
    <p>Email: {{ email }}</p>
    <input v-model="email" placeholder="Skriv din email">

    <p>Fornavn: {{ fornavn }}</p>
    <input v-model="fornavn" placeholder="Skriv dit fornavn">

    <p>Efternavn: {{ efternavn }}</p>
    <input v-model="efternavn" placeholder="Skriv dit efternavn">

    <p>Telefon Nummer: {{ telefon }}</p>
    <input v-model="telefon" placeholder="Skriv dit telefon nummer">
  </div>

</template>