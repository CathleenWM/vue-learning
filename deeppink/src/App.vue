<script setup>
import { ref } from 'vue';

const vandcykle = ref('');

function onSubmit() {
  alert(vandcykle.value);
}

</script>

<template>

  <!--Two way binding-->
  <h1>Hello World</h1>
  <input type="text" v-model="vandcykle"/>
  <button v-on:click="onSubmit">
    Dette er en knap
  </button>
  {{ vandcykle }}

</template>

