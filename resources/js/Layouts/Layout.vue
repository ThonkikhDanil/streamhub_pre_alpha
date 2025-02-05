<script setup lang="ts">
	import Header from '@/Components/Header.vue';
	import Sidebar from '@/Components/Sidebar.vue';
</script>

<template>
	<Header />
	<Sidebar />
	<slot />
</template>
