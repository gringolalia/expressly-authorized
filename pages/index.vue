<template lang="pug">
section.container
	div.text-center
		h1
			i.fas.fa-sun.fa-5x
		h1 Expressly Authorized
		h2.mb-4 Checked Out and Good to Go
		b-button(size="lg") Freely Press Me
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
	components: {
		Logo
	}
}
</script>

<style>

.container {
	min-height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
	text-align: center;
}

i, .material-icons {
	vertical-align: middle;
}


</style>
