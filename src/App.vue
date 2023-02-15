<script setup lang="ts">
import NavBar from './components/NavBar.vue';
</script>

<template>
	<!--# NavBar-->
	<NavBar></NavBar>
	<div class="blank h-16 s"> </div>
	<div id="title" class="mt-10  h-40 flex flex-col items-center">
		<h1 class="sm:text-5xl font-semibold mb-6 text-2xl tracking-wide">The Future of Notes</h1>
		<div id="description" class=" hidden sm:block w-96 text-neutral-900 font-light text-center">Chronicle is a
			note-taking
			application, but
			more
			precisely it is a highly customisable knowledge base . </div>
	</div>
	<div class="text-center block mt-8">
		<img src="http://mikes.oss-cn-beijing.aliyuncs.com/uPic/Feb-15-2023-16-54-53.gif"
			class="w-full sm:w-7/12 text-center inline border-solid border-4">
	</div>

</template>

<style lang="scss" scoped>

</style>
