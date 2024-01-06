<script lang="ts">

	export default defineNuxtComponent({
		data: () => ({
			tab: "1",
		}),
	});

</script>

<style lang="scss" scoped>

	section {
		padding: 50px 0;
	}

</style>

<template>
	<section>
		<div
			class="container mx-auto flex flex-column justify-between align-center"
		>
			<h1 class="title font-bold text-3xl">Service</h1>

			<div class="flex flex-column md:flex-row mt-10">
				<v-tabs v-model="tab" direction="vertical" color="primary">
					<v-tab value="1">
						<v-icon start> mdi-account </v-icon>
						API in Symfony 6
					</v-tab>

					<v-tab value="2">
						<v-icon start> mdi-lock </v-icon>
						API in Laravel Lumen 10
					</v-tab>

					<v-tab value="3">
						<v-icon start> mdi-access-point </v-icon>
						API in Spring Boot 3
					</v-tab>
				</v-tabs>

				<v-window v-model="tab">
					<v-window-item value="1">
						<v-card flat>
							<v-card-text>
								<p>
									Sed aliquam ultrices mauris. Donec posuere vulputate arcu. Morbi
									ac felis. Etiam feugiat lorem non metus. Sed a libero.
								</p>

								<p>
									Nam ipsum risus, rutrum vitae, vestibulum eu, molestie vel,
									lacus. Aenean tellus metus, bibendum sed, posuere ac, mattis
									non, nunc. Aliquam lobortis. Aliquam lobortis. Suspendisse non
									nisl sit amet velit hendrerit rutrum.
								</p>

								<p class="mb-0">
									Phasellus dolor. Fusce neque. Fusce fermentum odio nec arcu.
									Pellentesque libero tortor, tincidunt et, tincidunt eget, semper
									nec, quam. Phasellus blandit leo ut odio.
								</p>
							</v-card-text>
						</v-card>
					</v-window-item>

					<v-window-item value="2">
						<v-card flat>
							<v-card-text>
								<p>
									Morbi nec metus. Suspendisse faucibus, nunc et pellentesque
									egestas, lacus ante convallis tellus, vitae iaculis lacus elit
									id tortor. Sed mollis, eros et ultrices tempus, mauris ipsum
									aliquam libero, non adipiscing dolor urna a orci. Curabitur
									ligula sapien, tincidunt non, euismod vitae, posuere imperdiet,
									leo. Nunc sed turpis.
								</p>

								<p>
									Suspendisse feugiat. Suspendisse faucibus, nunc et pellentesque
									egestas, lacus ante convallis tellus, vitae iaculis lacus elit
									id tortor. Proin viverra, ligula sit amet ultrices semper,
									ligula arcu tristique sapien, a accumsan nisi mauris ac eros. In
									hac habitasse platea dictumst. Fusce ac felis sit amet ligula
									pharetra condimentum.
								</p>

								<p>
									Sed consequat, leo eget bibendum sodales, augue velit cursus
									nunc, quis gravida magna mi a libero. Nam commodo suscipit quam.
									In consectetuer turpis ut velit. Sed cursus turpis vitae tortor.
									Aliquam eu nunc.
								</p>

								<p>
									Etiam ut purus mattis mauris sodales aliquam. Ut varius
									tincidunt libero. Aenean viverra rhoncus pede. Duis leo. Fusce
									fermentum odio nec arcu.
								</p>

								<p class="mb-0">
									Donec venenatis vulputate lorem. Aenean viverra rhoncus pede. In
									dui magna, posuere eget, vestibulum et, tempor auctor, justo.
									Fusce commodo aliquam arcu. Suspendisse enim turpis, dictum sed,
									iaculis a, condimentum nec, nisi.
								</p>
							</v-card-text>
						</v-card>
					</v-window-item>

					<v-window-item value="3">
						<v-card flat>
							<v-card-text>
								<p>
									Fusce a quam. Phasellus nec sem in justo pellentesque facilisis.
									Nam eget dui. Proin viverra, ligula sit amet ultrices semper,
									ligula arcu tristique sapien, a accumsan nisi mauris ac eros. In
									dui magna, posuere eget, vestibulum et, tempor auctor, justo.
								</p>

								<p class="mb-0">
									Cras sagittis. Phasellus nec sem in justo pellentesque
									facilisis. Proin sapien ipsum, porta a, auctor quis, euismod ut,
									mi. Donec quam felis, ultricies nec, pellentesque eu, pretium
									quis, sem. Nam at tortor in tellus interdum sagittis.
								</p>
							</v-card-text>
						</v-card>
					</v-window-item>
				</v-window>
			</div>

			<!--
			<v-card variant="tonal">
				<template v-slot:title>Services</template>

				<template v-slot:text>
					Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptas soluta mollitia ipsa sint, quod illo. Aut corrupti fugiat praesentium velit quos. Dolorum nemo dignissimos sapiente laborum quas numquam ipsum non!
				</template>
			</v-card>
			-->
		</div>
	</section>
</template>
