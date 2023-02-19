<script lang="ts" setup></script>
<template>
	<div
		class=" border-solid  h-16  w-full flex items-center md:justify-evenly md:pl-16 md:pr-16 justify-between pl-4 pr-4 fixed z-10 border-b bg-white">

		<div class="logo font-extrabold text-3xl  cursor-pointer">Chronicle</div>

		<div class="items md:flex justify-center flex-1 text-slate-800 font-semibold hidden ">
			<div class="item cursor-pointer hover:underline underline-offset-4 text-sm">Products</div>
			<div class="separator text-sm">&nbsp · &nbsp</div>
			<div class="item cursor-pointer hover:underline underline-offset-4 text-sm">Solutions</div>
			<div class="separator text-sm">&nbsp · &nbsp</div>
			<div class="item cursor-pointer hover:underline underline-offset-4 text-sm">Pricing</div>
		</div>

		<a class="border-2 p-2 rounded text-sm text-violet-800" href="#download">Download</a>
	</div>
</template>
<style lang="scss" scoped></style>