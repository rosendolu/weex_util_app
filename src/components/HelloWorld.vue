<template lang="pug">
  text.main {{msg}}
</template>

<script>
export default {
	// eslint-disable-next-line no-tabs
	data() {
		return {
			msg: 'wa hahah ',
		}
	},
	created() {},
	mounted() {
		setTimeout(() => {
			this.msg = 'hello weex '
		}, 2000)
	},
	methods: {
		init() {
			//
		},
	},
}
</script>

<style scoped></style>>
