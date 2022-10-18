<template>
 <div class = "createwrapper">
 	<img src = "~assets/svg/newproject-icon.svg" class = "createicon">
 	<p class = "createtext">
 		Создать новый проект
 	</p>
 	<img src = "~assets/svg/arrow-drop-up-line.svg" class = "createbtn">
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
	}
	.createtext {
		width: 16.125rem;
		align-items: center;
		font-weight: 500;
		size: 1.25rem;
		color: #000;
		margin: 1.5rem;
	}
	.createbtn {
		margin: 1.5rem 3rem;
		height: 1.5rem;
		width: 1.5rem;
	}
</style>
