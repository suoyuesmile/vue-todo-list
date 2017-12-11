<template>
	<input 
		type="text" 
		class="input" 
		:value="value" 
		v-on="$listeners" 
		@input="$emit('input', $event.target.value)"
	>
</template>

<script type="text/javascript">
export default {
	props: {
		value: {
			type: String,
			default: '',
		}
	}
}
</script>

<style lang="scss" scoped>
@import '../variable.scss';

.input {
	width: 100%;
	padding: 8px 10px;
	border: 1px solid $vue-blue;
}
</style>