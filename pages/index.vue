<template>
	<div>
		<headercom/>
		<asidecom/>
		<createcom/>
		<createcom/>
		<createcom/>
	</div>
</template>

<script>
import headercom from '~/components/headercom.vue'
import asidecom from '~/components/asidecom.vue'
import createcom from '~/components/createcom.vue'

export default {
  name: 'IndexPage',
  components: {
  	headercom,
  	asidecom,
  	createcom
  },
}
</script>

<style>
	* {
	margin: 0;
	padding: 0;
	}
</style>