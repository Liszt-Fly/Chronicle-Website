<script lang="ts" setup>
const props = defineProps({
	item: Object as () => featureComponent,
});

</script>
<template>
	<div class="rounded-md mb-4 justify-self-center hover:bg-violet-100 p-4 text-justify">
		<div class="my-icon">
			<i :class="item!.icon" class="text-3xl text-violet-800"></i>
		</div>
		<div class="small-title text-2xl mt-2 font-semibold capitalize">
			{{ item!.title }}
		</div>
		<div class="text-neutral-600 mt-2">
			{{ item!.content }}
		</div>
	</div>
</template>
<style lang="scss" scoped></style>
