<script setup lang="ts">
defineProps<{ link: string }>();
</script>

<template>
	<NuxtLink
		:to="link"
		target="_blank"
		class="hover:scale-110 duration-300 transition-all"
	>
		<slot />
	</NuxtLink>
</template>
