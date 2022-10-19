<template>
 <div class = "createwrapper">
 	<img src = "~assets/svg/newproject-icon.svg" class = "createicon">
 	<p class = "createtext">
 		<b>Создать новый проект</b>
 	</p>
 	<img src = "~assets/svg/plus.svg" class = "createbtn">
 </div>
</template>

<style scoped>
	.createwrapper {
		margin-left: 1.5rem;
		width: 27.625rem;
		display: flex;
		padding: 1.5rem;
		border: 0.063rem solid rgba(0, 0, 0, 0.03);
	}
	.createicon {
		width: 4rem;
		height: 4rem;
		margin-top: auto;
		margin-bottom: auto;
	}
	.createtext {
		width: 16.125rem;
		align-items: center;
		font-weight: 500;
		size: 1.25rem;
		color: #000;
		margin-top: auto;
		margin-bottom: auto;
		margin-left: 1.5rem;
		margin-right: 1.5rem;
	}
	.createbtn {
		margin-right: 1.5rem;
		margin-top: auto;
		margin-bottom: auto;
		height: 1.5rem;
		width: 1.5rem;
	}
</style>
