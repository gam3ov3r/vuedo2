<template>
	<header>
		<h1>{{ title }}</h1>
	</header>
</template>

<script>
export default {
  data () {
    return {
		title: 'My app'
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
