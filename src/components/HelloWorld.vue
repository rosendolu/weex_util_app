<template lang="pug">
  div.body
    div.flex
      div.flex-justify-center weex pug textflex-justify-center weex pug textflex-justify-center weex pug text
        | weex pug textflex-justify-center weex pug textflex-justify-center weex pug text
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
			this.msg = `hello weex
      one
      tow
      `
		}, 2000)
	},
	methods: {
		init() {
			//
		},
	},
}
</script>

<style scoped>
.body {
	background-color: #000;
	width: 750px;
}
.flex {
	display: flex;
}
.main {
	background-color: green;
	font-size: 24px;
}
</style>
