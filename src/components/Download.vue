<script lang="ts" setup></script>
<template>
	<div class="download text-center flex flex-col items-center mb-48">
		<div class=" text-4xl font-semibold text-center mb-4" id="download">Download Chronicle </div>
		<img src="/chronicle.png" alt="" class="w-40 ">
		<div class="text-neutral-600 mb-4">
			current version: beta 0.2.0
		</div>
		<div class="btns flex justify-around ">
			<div
				class="cursor-pointer mac border-solid rounded-md text-white border-slate-100 border-2 bg-violet-400 p-2 mr-10">
				<i class="bi bi-apple mr-2"></i> <a
					href="https://github.com/mytho-team/mytho/releases/download/v0.2.0-alpha/mytho_0.2.0.dmg">Download for mac</a>
			</div>
			<div class="mr-2 cursor-pointer mac border-solid rounded-md text-white border-slate-100 border-2 bg-violet-400 p-2">
				<i class="bi bi-windows"></i> <a
					href="https://github.com/mytho-team/mytho/releases/download/v0.2.0-alpha/mytho_0.2.0.exe">
					Donwload for windows
				</a>
			</div>

		</div>
	</div>
</template>
<style lang="scss" scoped></style>