<script setup>

import { ref } from 'vue';

// const email = ref('');
// const fornavn = ref('');
// const efternavn = ref('');
// const telefon = ref('');

const navn = ref ('');
const mail = ref ('');
const telnr = ref ('');

function onSubmit() {
  alert(`navn: ${navn.value}, \nemail: ${mail.value}, \ntelefon nummer: ${telnr.value}`);
}

</script>

<template>
  <!-- <div>
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
  </div> -->

  <div>
    Form
  </div>
  <br>

  <form>
    <input v-model="navn" type="text" placeholder="Skriv navn">
    <br><br>
    <input v-model="mail" type="text" placeholder="Skriv mail">
    <br><br>
    <input v-model="telnr" type="text" placeholder="Skriv nummer">
  </form>

</template>