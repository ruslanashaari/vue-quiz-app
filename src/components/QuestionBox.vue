<template>
	<div class="question-box-container">
		<b-jumbotron lead="Bootstrap 4 Components for Vue.js 2">
			<template slot="lead">
				{{ currentQuestion.question }}
			</template>

			<hr class="my-4" />

			<p>
				List of answers
			</p>

			<b-button variant="primary" href="#">Submit</b-button>
			<b-button @click="next" variant="success" href="#">Next</b-button>
		</b-jumbotron>
	</div>
</template>

<script>
	export default {
		props: {
			currentQuestion: Object,
			next: Function
		}
	}
</script>