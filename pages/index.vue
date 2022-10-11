<template>
	<div class ="wrapper">
		<headercom/>
		<div class ="main__content">
			<asidecom/>
			<div class ="wrapper__create">
				<createcom/>
				<createcom/>
				<createcom/>
			</div>
		</div>
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
	.wrapper {
		height: 100%;
	}
	.wrapper__create {
	}
	.main__content {
		height: 100%;
		display: flex;
		width: 100%;
	}

</style>