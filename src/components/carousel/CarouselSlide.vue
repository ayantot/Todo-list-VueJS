<template>
	<div v-show="visible">
		index: {{ index }}
		visible ? {{ visible }}
		<slot></slot>
	</div>
</template>

<script>
export default {
	data () {
		return {
			index: 0
		}
	},

	computed: {
		visible () {
			return this.index === this.$parent.index
		}
	}
}
</script>

<style>

</style>

