<template>
	<footer>
		<p>{{ copyright }}</p>
	</footer>
</template>

<script>
export default {
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
