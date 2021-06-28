<template>
	<div>
		<b-nav tabs>
			<b-nav-item disabled><b>Fancy Quiz</b></b-nav-item>
			<b-nav-item disabled>Counter: {{ index + 1 }}/10</b-nav-item>
		</b-nav>
	</div>
</template>

<script>
	export default {
		props: {
			index: Number
		}
	}
</script>