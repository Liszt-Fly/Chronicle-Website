<script setup lang="ts">
import NavBar from "./components/NavBar.vue";
import Intro from "./components/Intro.vue";
import Feature from "./components/Feature.vue";
import { features } from "./data";
import Download from "./components/Download.vue";
</script>

<template>
	<div class="bg-zinc-50">
		<NavBar></NavBar>
		<Intro></Intro>
		<div id="features-page" class="p-4">
			<h1 class="text-center mt-40 sm:text-4xl font-semibold tracking-wide">
				Study With One Application
			</h1>
			<div class="description text-center mt-5">
				Create a comfortable writing environment with the powerful features of
				Chronicle and create your own learning style.
			</div>
		</div>
		<div class="box grid gap-10 sm:grid-cols-1 md:grid-cols-2 p-4 sm:p-8 xl:grid-cols-3 box-border mt-5">
			<template v-for="item in features">
				<Feature :item="item"></Feature>
			</template>
		</div>
		<Download></Download>
	</div>
</template>

<style lang="scss" scoped></style>
