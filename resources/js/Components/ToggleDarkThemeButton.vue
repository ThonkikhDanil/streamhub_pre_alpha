<script setup>
	import { useDark, useToggle } from '@vueuse/core';

	const isDark = useDark();
	const toggleDark = useToggle(isDark);
</script>

<template>
	<button @click="toggleDark()">
		<span v-if="isDark" class="relative top-1">
			<i class="fi fi-br-brightness" />
		</span>
		<span v-else class="relative top-1">
			<i class="fi fi-br-moon-stars" />
		</span>
	</button>
</template>
