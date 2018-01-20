<template>
	<footer>
		<p>{{ copyright }} {{ title }}</p>
	</footer>
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
			copyright: 'Copyright 2018'
		}	
	}
}
</script>

<style scooped>
	footer {
		background: #ccc;
		padding: 20px;
		font-size: 1em;
	}
	p {
		text-align: center;
	}
</style>
