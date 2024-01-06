<script lang="ts"></script>

<style lang="scss" scoped>

	section {
		background-color: #EAD196;
		padding: 150px 0;
		height: 91vh;

		h1.main-intro {
			width: 100%;
		}

		div.main-brand {
			width: 100%;

			img.brand-logo {
				height: 100%;
			}
		}
	}

</style>

<template>

	<section>

		<div class="container mx-auto flex md:flex-column justify-between">
			<div class="flex flex-column justify-between">
				<h1 class="main-intro text-7xl font-semibold text-wrap">My learn of NuxtJS project.</h1>

				<span>By me, Ibent95...</span>
			</div>

			<div class="main-brand flex justify-end">
				<img class="brand-logo lg:pe-14" src="@/assets/img/brand-logo-blue.png" alt="Brand">
			</div>
		</div>

	</section>

</template>
