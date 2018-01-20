<template>
	<div>
		<app-header v-bind:title="title"></app-header>
		<app-main v-bind:ninjas="ninjas"></app-main>		
		<app-footer v-bind:title="title"></app-footer>
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
			ninjas: [
			{name: 'Ryu', speciality: 'Vue Components', show: false},
			{name: 'Crystal', speciality: 'HTML Wizardry', show: false},
			{name: 'Hitoshi', speciality: 'Click Events', show: false},
			{name: 'Tango', speciality: 'Conditionals', show: false},
			{name: 'Kami', speciality: 'Webpack', show: false},
			{name: 'Yoshi', speciality: 'Data Diggin', show: false}
			],
			title: "Vue Ninjas"		
		}
	}
}
</script>

<style>
	
</style>
