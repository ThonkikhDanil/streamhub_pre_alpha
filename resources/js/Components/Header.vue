<script setup>
	import { Link } from '@inertiajs/vue3';
</script>

<template>
	<div class="bg-[#D5F2F2] dark:bg-[#010326] p-4 flex items-center">
		<div class="flex items-center justify-between w-72 text-[#010326] dark:text-[#D5F2F2] text-2xl">
			<i class="relative fi fi-br-menu-burger top-1" />
			<i class="relative fi fi-br-brightness top-1" />
			<Link :href="route('welcome')" class="text-[#010326] dark:text-[#D5F2F2] font-semibold text-4xl">Stream<span class="text-[#116EBF]">Hub</span></Link>
		</div>
	</div>
</template>
