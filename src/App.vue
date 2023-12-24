<script setup lang="ts">
import { Toggle } from '@/components/ui/toggle'
import IconUsers from './IconUsers.vue'
import { ref } from 'vue'

const toggleState = ref(true)
</script>

<template>
  <Toggle variant="outline" size="lg" v-model:pressed="toggleState">
    <IconUsers class="w-6 h-6"/>
  </Toggle>
</template>
