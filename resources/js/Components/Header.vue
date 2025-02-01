<script setup>
	import ApplicationLogo from '@/Components/ApplicationLogo.vue';
	import ToggleDarkThemeButton from '@/Components/ToggleDarkThemeButton.vue';
	import SearchRow from '@/Components/SearchRow.vue';
</script>

<template>
	<div class="bg-[#D5F2F2] dark:bg-[#010326] p-4 flex items-center justify-between">
		<div class="flex items-center justify-between w-72 text-[#010326] dark:text-[#D5F2F2] text-2xl">
			<i class="relative fi fi-br-menu-burger top-1" />
			<ToggleDarkThemeButton />
			<ApplicationLogo />
		</div>
		<SearchRow />
		<button class="py-1 px-4 text-[#010326] dark:text-[#D5F2F2] flex items-center rounded-2xl hover:bg-[#116EBF] dark:hover:bg-[#1F82BF] hover:text-[#D5F2F2] dark:hover:text-[#010326] transition-all">
			<div class="relative mr-4 text-2xl top-1">
				<i class="fi fi-br-user" />
			</div>
			<div class="font-semibold">Войти</div>
		</button>
	</div>
</template>
