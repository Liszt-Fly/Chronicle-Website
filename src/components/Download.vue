<script lang="ts" setup></script>
<template>
	<div class="download text-center flex flex-col items-center pb-36">
		<div class=" text-4xl font-semibold text-center mb-4" id="download">Download Chronicle </div>
		<img src="/chronicle.png" alt="" class="w-40">
		<div class="text-neutral-600 mb-4">
			current version: beta 0.2.0
		</div>
		<div class="btns flex justify-around ">
			<div class="download-btn cursor-pointer mac border-solid rounded-md bg-violet-500 text-slate-50 p-2 mr-10 w-80">
				<i class="bi bi-apple mr-2"></i>
				<a href="https://github.com/mytho-team/mytho/releases/download/v0.2.0-alpha/mytho_0.2.0.dmg">
					Download for Mac
				</a>
			</div>
			<div
				class="download-btn mr-2 cursor-pointer mac border-solid rounded-md bg-violet-500 text-slate-50 p-1 pl-3 pr-3 w-80">
				<i class="bi bi-windows"></i>
				<a href="https://github.com/mytho-team/mytho/releases/download/v0.2.0-alpha/mytho_0.2.0.exe">
					Donwload for Windows
				</a>
			</div>

		</div>
	</div>
</template>
<style lang="scss" scoped></style>