<script setup>
	import { useDark, useToggle } from '@vueuse/core';

	const isDark = useDark();
	const toggleDark = useToggle(isDark);
</script>

<template>
	<button @click="toggleDark()">
		<span v-if="isDark">
			<i class="relative fi fi-br-brightness top-1" />
		</span>
		<span v-else>
			<i class="relative fi fi-br-moon-stars top-1"></i>
		</span>
	</button>
</template>
