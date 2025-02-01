<script setup>
	import ApplicationLogo from '@/Components/ApplicationLogo.vue';
	import ToggleDarkThemeButton from '@/Components/ToggleDarkThemeButton.vue';
</script>

<template>
	<div class="bg-[#D5F2F2] dark:bg-[#010326] p-4 flex items-center justify-between">
		<div class="flex items-center justify-between w-72 text-[#010326] dark:text-[#D5F2F2] text-2xl">
			<i class="relative fi fi-br-menu-burger top-1" />
			<ToggleDarkThemeButton />
			<ApplicationLogo />
		</div>
		<form action="" class="flex">
			<input type="text" class="w-96 bg-[#D5F2F2] dark:bg-[#010326] text-[#010326] dark:text-[#D5F2F2] rounded-s-2xl border-2 border-[#202020] border-r-0" placeholder="Введите запрос" />
			<button type="submit" class="bg-[#010326] dark:bg-[#D5F2F2] hover:bg-[#116EBF] dark:hover:bg-[#1F82BF] transition-all text-2xl py-1 px-8 rounded-e-2xl">
				<span class="text-[#D5F2F2] dark:text-[#010326] relative top-1">
					<i class="fi fi-br-search" />
				</span>
			</button>
		</form>
		<button class="py-1 px-4 text-[#010326] dark:text-[#D5F2F2] flex items-center rounded-2xl hover:bg-[#116EBF] dark:hover:bg-[#1F82BF] hover:text-[#D5F2F2] dark:hover:text-[#010326] transition-all">
			<div class="relative mr-4 text-2xl top-1">
				<i class="fi fi-br-user" />
			</div>
			<div class="font-semibold">Войти</div>
		</button>
	</div>
</template>
