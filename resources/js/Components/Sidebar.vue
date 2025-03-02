<script setup lang="ts">
	import NavLink from '@/Components/NavLink.vue';
</script>

<template>
	<div class="relative">
		<div class="absolute flex">
			<div class="bg-[#D5F2F2] dark:bg-[#010326] h-screen flex flex-col">
				<NavLink :href="route('welcome')" :active="route().current('welcome')" class="mt-0">
					<div class="mr-3">
						<i class="fi fi-br-home" />
					</div>
					<div>Главная</div>
				</NavLink>
				<NavLink :href="route('subscriptions')" :active="route().current('subscriptions')">
					<div class="mr-3">
						<i class="fi fi-br-folder" />
					</div>
					<div>Подписки</div>
				</NavLink>
			</div>
		</div>
	</div>
</template>
