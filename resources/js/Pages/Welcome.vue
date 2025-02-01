<script setup>
	import Layout from '@/Layouts/Layout.vue';
	import { Head } from '@inertiajs/vue3';

	const props = defineProps({
		title: {
			type: String,
		},
	})
</script>

<template>
	<Head :title="title" />
	<Layout>
		<p class="m-4">Hello World!</p>
	</Layout>
</template>
