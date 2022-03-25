<template>
	<div>
		<div>
			<h1 class="text-lg font-bold">Serviços</h1>
			<NuxtLink to="/servicos/desenvolvimento">
				Desenvolvimento de Sites </NuxtLink
			>\
			<NuxtLink to="/servicos/marketing-digital"> Marketing Digital </NuxtLink>\
			<div class="text-information">
				<br /><br />

				<NuxtChild />
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
