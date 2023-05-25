<script setup>
import Foo from './Foo.vue';
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(null)
</script>

<template>
  <Foo ref="count" :foo="count" />
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
