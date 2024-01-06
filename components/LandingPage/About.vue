<script lang="ts">

	export default defineNuxtComponent({
		data: () => ({
			tab: "option-1",
		}),
	});

</script>

<style lang="scss" scoped>

	section {
		padding: 50px 0;
	}

</style>

<template>
	<section class="container mx-auto">
		<div
			class="container mx-auto flex flex-column justify-between align-center"
		>
			<h1 class="title font-bold text-3xl">About</h1>

			<p class="mt-10">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Neque non soluta ad, fugiat itaque officia quod in dignissimos vitae mollitia nisi consequatur, earum veniam culpa porro beatae cumque quisquam eum?</p>
		</div>
	</section>
</template>
