<template>
	<div class ="wrapper">
		<div class ="main__content">
			<asidecom/>
			<div class ="wrapper__content">
				<div class ="wrapper__create">
					<createcom/>
					<createcom/>
					<createcom/>
				</div>
				<div class ="postlist">
					<postcard/>
					<postcard/>
					<postcard/>
					<postcard/>
					<postcard/>
					<postcard/>
				</div>
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
		display: flex;
		flex-direction: column;
	}
	.wrapper__create {
		display: flex;
		height: 13.313rem;
		align-items: center;
	}
	.main__content {
		height: 100%;
		display: flex;
		width: 100%;
	}
	.wrapper__content {
		display: flex;
		flex-direction: column;
	}
	.postlist {
		display: flex;
		flex-wrap: wrap;
	}
</style>