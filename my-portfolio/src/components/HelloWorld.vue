<template>
<nav>
  <div>
    <a href=""> <li></li> </a>
  </div>
</nav>

</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>

</style>