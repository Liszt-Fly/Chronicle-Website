<script lang="ts" setup></script>
<template>
	<div class="download text-center flex flex-col items-center pb-36">
		<div class=" text-4xl font-semibold text-center mb-4" id="download">Download Chronicle </div>
		<img src="/chronicle.png" alt="" class="w-40">
		<div class="text-neutral-600 mb-4">
			current version: beta 0.2.0
		</div>
		<div class="btns flex justify-around ">
			<div class="cursor-pointer mac border-solid rounded-md bg-gray-900  text-slate-50 p-4 mr-10  flex items-center">
				<i class="bi bi-apple mr-2 text-[3rem]"></i>
				<a href="https://github.com/mytho-team/mytho/releases/download/v0.2.0-alpha/mytho_0.2.0.dmg">
					<div class="font-extrabold text-[1.5rem]">macOS</div>
					<div class="font-bold">Desktop App</div>
				</a>
			</div>
			<div class=" mr-2 cursor-pointer mac border-solid rounded-md bg-gray-900 text-slate-50 p-4 flex  items-center">
				<i class="bi bi-windows text-[2.8rem] mr-[0.8rem]"></i>
				<a href="https://github.com/mytho-team/mytho/releases/download/v0.2.0-alpha/mytho_0.2.0.exe">
					<div class="font-extrabold text-[1.5rem]">windows</div>
					<div class="font-bold">Desktop App</div>
				</a>
			</div>

		</div>
	</div>
</template>
<style lang="scss" scoped></style>