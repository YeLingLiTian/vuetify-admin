<template>
			<!-- class="grey lighten-4" -->
	<v-app >
		  <Navbar />
		<v-content class="mx-4">
			<router-view></router-view>
		</v-content>
	</v-app>
</template>

<script>
	
	import Navbar from '@/components/navbar'

	export default {
		name: 'App',

		components: {
			Navbar
		},

		data: () => ({
			//
		}),
	};
</script>
