<template>
	<header>
		<div class = "nav__primary">
			<div class = "mainbtn">
				<img class = "mainbtn__icon" src = "~static/home.svg">
				<p class = mainbtn__text>Главная</p>
			</div>
		</div>
		<div class = "nav__secondary">
			<div class = "search">
				<img class = "search__icon" src = "~static/search-icon.svg"></img>
				<input type = "text" size = "20" class = "search__input" value = "Поиск по проектам">
			</div>
			<div class = "user__profile">
				<img class = "user__profile__icon" src = "~static/user-profile.svg">	
			</div>
		</div>
	</header>
</template>

<script>

</script>
	
<style scoped>
	header {
		height: 5rem;
		background-color: #232323;
		display: flex;
		align-items: center;
		justify-content: space-between;
		/* Настройки шрифта */
		font-family: 'Inter';
		font-size: 1.625rem;
		line-height: 1.375rem;
		color: #FFF;
	}
	.nav__primary {
		height: 100%;
	}
	.nav__secondary {
		height: 100%;
		display: flex;
		align-items: center;
		justify-content: flex-start;
	}
	.mainbtn {
		height: 100%;
		width: 13rem;
		font-size: 1.125rem;
		display: flex;
		align-items: center;
		background-color: #000;
		justify-content: center;
	}
	.mainbtn__icon {
		width: 1.5rem;
		height: 1.5rem;
		margin-right: 0.688rem;
	}
	
	.search {
		height: 70%;
		display: flex;
		border: 1px solid rgba(255, 255, 255, 0.03);
		border-radius: 2px;
		align-items: center;
		padding: 24px 24px 24px 16px;
	}
	.search__icon {
		width: 1.5rem;
		height: 1.5rem;
		margin-right: 0.606rem;
	}
	.search__input {
		height: 1.375rem;
		width: 10.688rem;
		background: none;
		color: rgba(255, 255, 255, 0.5);
		border: none;
		font-size: 1.125rem;

	}
	.user__profile {
		display: flex;
		align-items: center;
		justify-content: center;
		border-radius: 50%;
		border: 1px solid rgba(255, 255, 255, 0.03);
		margin-right: 2.5rem;
		margin-left: 0.688rem;
		width: 3.5rem;
		height: 3.5rem;
	}
</style>