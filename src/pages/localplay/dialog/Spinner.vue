<template>
	<div v-show="spinner.show" class="spinner-modal">
		<div class="spinner-modal-content spinner">
			<div class="rect1"></div>
			<div class="rect2"></div>
			<div class="rect3"></div>
			<div class="rect4"></div>
			<div class="rect5"></div>
		</div>
	</div>
</template>
<script>
	export default {
		data: function() {
			return {
				spinner: null
			}
		},
		props: [

		],
		created: function() {
			this.scene = this.$parent.scene;
			this.spinner = this.scene.spinner;
		},
		computed: {

		}
	}
</script>

<style>

</style>