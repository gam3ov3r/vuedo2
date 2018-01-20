<template>
	<div>
		<app-header></app-header>
		<app-main></app-main>		
		<app-footer></app-footer>
	</div>
</template>

<script>
import Header from './components/header.vue';
import Main from './components/main.vue';
import Footer from './components/footer.vue';
	
export default {
	components: {
		'app-header': Header,
		'app-main': Main,
		'app-footer': Footer
	},
	data() {
		return {
		
		}
	}
}
</script>

<style>
	
</style>
