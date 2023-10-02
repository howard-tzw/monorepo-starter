<script setup lang="ts">
import { greeting, foo } from '@monorepo/utils'
import { onMounted } from 'vue'

onMounted(() => {
	greeting()
})
</script>

<template>
	<div>Playground {{ foo }}</div>
</template>
