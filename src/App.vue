<script setup>

import { ref } from "vue";
const message = ref('Ciao Mondo!')
const count = ref(0)

</script>

<template>
  <h1 align="center"> {{ message }} </h1>
  <br/>
  <button @click="count++">Clicca qui {{ count }}</button>
</template>