<script setup lang="ts">
  import {VueTypedJs} from "vue3-typed-ts";
</script>

<template>
  <VueTypedJs
    :strings="['Hello World', 'Hello Vue3', 'Great Experience !!!!!!🐶も行けるか']"
    :typeSpeed="100"
    :backSpeed="100"
    :loop="true"
  >
    <span class="typing"></span>
  </VueTypedJs>
</template>