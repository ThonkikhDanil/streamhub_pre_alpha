<script setup lang="ts">
	import NavLink from '@/Components/NavLink.vue';
</script>

<template>
	<div class="relative">
		<div class="absolute flex">
			<div class="bg-[#D5F2F2] dark:bg-[#010326] h-screen flex flex-col items-center">
				<NavLink :href="route('welcome')">Главная</NavLink>
				<NavLink :href="route('subscriptions')">Подписки</NavLink>
			</div>
		</div>
	</div>
</template>
