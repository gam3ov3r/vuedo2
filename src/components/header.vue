<template>
	<header>
		<h1 v-on:click="changeTitle">{{ title }}</h1>
	</header>
</template>

<script>
export default {
	props: {
		title: {
			type: String
		}	
	},
	data () {
		return {
		title: 'My appzzz'
		}
	},
	methods: {
		changeTitle: function() {
			this.title ="Vue Wizzards"
		}
	}
}
</script>

<style scoped>
	header {
		background: black;
		padding: 20px;
	}
	h1 {
		color: #fff;
		text-align: center;
	}
</style>
