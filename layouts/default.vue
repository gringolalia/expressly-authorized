<template lang="pug">
div
	b-navbar(toggleable='lg' type='dark' variant='primary' fixed='top')
		b-navbar-brand(href='#') 
			i.fas.fa-sun.fa-2x.mr-3
			| Engenho do Povo
		b-navbar-toggle(target='nav-collapse')
		b-collapse#nav-collapse(is-nav)
			b-navbar-nav
				b-nav-item(href='#') Entrelaço
				b-nav-item(href='#' ) Desenlaço
			b-navbar-nav.ml-auto
				b-nav-item-dropdown(text='Lingos' right)
					b-icon(icon='chevron-bar-up')
					b-dropdown-item(href='#') Japonês
					b-dropdown-item(href='#') Mandarino
					b-dropdown-item(href='#') Árabe
					b-dropdown-item(href='#') Euskara
					b-dropdown-item(href='#') Finlandês
					b-dropdown-item(href='#') Euskara
					b-dropdown-item(href='#') Húngaro
					b-dropdown-item(href='#') Navajo
					b-dropdown-item(href='#') Koreano
					b-dropdown-item(href='#') Islandês
					b-dropdown-item(href='#') Polonês

				b-nav-item-dropdown.ml-4(text='Bureaucracy' right)
					template(v-slot:button-content)
					b-dropdown-item(href='#') Profile
					b-dropdown-item(href='#') Sign Out
					b-dropdown-item(href='#') Freak Out

	nuxt


</template>

<style>
html {
	font-family: 'News Cycle', -apple-system, BlinkMacSystemFont, 'Segoe UI',
		Roboto, 'Helvetica Neue', Arial, sans-serif;
	font-size: 16px;
	word-spacing: 1px;
	-ms-text-size-adjust: 100%;
	-webkit-text-size-adjust: 100%;
	-moz-osx-font-smoothing: grayscale;
	-webkit-font-smoothing: antialiased;
	box-sizing: border-box;
}

*,
*:before,
*:after {
	box-sizing: border-box;
	margin: 0;
}

a:hover {
	text-decoration: none;
}

</style>
