<script setup>
	import { Link } from '@inertiajs/vue3';
</script>

<template>
	<Link :href="route('welcome')" class="text-4xl font-semibold">
		<span class="text-[#010326] dark:text-[#D5F2F2]">Stream</span>
		<span class="text-[#116EBF]">Hub</span>
	</Link>
</template>
