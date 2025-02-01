<script setup>
	import ApplicationLogo from '@/Components/ApplicationLogo.vue';
	import ToggleDarkThemeButton from '@/Components/ToggleDarkThemeButton.vue';
</script>

<template>
	<div class="bg-[#D5F2F2] dark:bg-[#010326] p-4 flex items-center">
		<div class="flex items-center justify-between w-72 text-[#010326] dark:text-[#D5F2F2] text-2xl">
			<i class="relative fi fi-br-menu-burger top-1" />
			<ToggleDarkThemeButton />
			<ApplicationLogo />
		</div>
	</div>
</template>
