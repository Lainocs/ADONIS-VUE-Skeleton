<template>
  <h1>Hello {{ user }}</h1>
</template>
<script>
export default {
	name: 'Home',
	props: [
		'user'
	]
}
</script>