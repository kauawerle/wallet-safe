<template>
	<div>
		<div class="bg-gray-100">
			<div class="container mx-auto flex items-center space-x-4 h-10">
				<NuxtLink :to="{name: 'a-empresa'}">A empresa</NuxtLink>
				<NuxtLink :to="{name: 'servicos'}">Serviços</NuxtLink>
				<NuxtLink :to="{name: 'produtos'}">Produtos</NuxtLink>
			</div>
		</div>

		<div>
			<div class="container mx-auto">
				<h1 class="text-lg font-bold">A empresa</h1>
				<p>
					Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus
					posuere maximus velit at mattis. Nulla a finibus tortor. Quisque
					pulvinar sed est sed sollicitudin. Phasellus at tincidunt nibh, in
					dignissim nibh. Praesent vel convallis orci, eget semper metus. Morbi
					laoreet pellentesque dui eget elementum.a
				</p>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "",

	data() {
		return {};
	},

	methods: {},
};
</script>
