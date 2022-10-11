<template>
	<aside class = "asideblock">
		<div class = "asideblock__content">
			<ul class = "aside__ul">
				<div class = "aside__ul01">
					<img src = "~assets/svg/projects.svg" class = "aside__ul01__icon">
					<p>
						Проекты	
					</p>
				</div>
				<img src = "~assets/svg/arrow-drop-up-line.svg">
			</ul>
			<div class = "hrline">
				
			</div>
			<ul class = "aside__ul">
				<div class = "aside__ul01">
					<img src = "~assets/svg/earth-line.svg" class = "aside__ul01__icon">
					<p>
						Сообщество
					</p>
				</div>
				<img src = "~assets/svg/arrow-drop-up-line.svg">
			</ul>
			<div class = "hrline">
				
			</div>
			<ul class = "aside__ul">
				<div class = "aside__ul01">
					<img src = "~assets/svg/users.svg" class = "aside__ul01__icon">
					<p>
						Пользователи
					</p>
				</div>
				<img src = "~assets/svg/arrow-drop-up-line.svg">
			</ul>
			<div class = "hrline">
				
			</div>
			<ul class = "aside__ul">
				<div class = "aside__ul01">
					<img src = "~assets/svg/team-line.svg" class = "aside__ul01__icon">
					<p>
						Команды
					</p>
				</div>
				<img src = "~assets/svg/arrow-drop-up-line.svg">
			</ul>
		</div>
	</aside>
</template>

<script>

</script>

<style scoped>
	.asideblock {
		width: 30.125rem;
	}
	.asideblock__content {
		margin-top: 2.5rem;
		padding: 0 2.5rem;
	}
	.aside__ul {
		display: flex;
		justify-content: space-between;
		border: 0.063rem solid black
	}
	.aside__ul01 {
		display: flex;
		font-size: 1.25rem;
		line-height: 1.5rem;
	}
	.aside__ul01__icon {
		margin-right: 0.5rem;
	}
	.hrline {
		width: 402px;
		height: 0;
		border: 1px solid rgba(0, 0, 0, 0.05);
		margin: 20px auto;
	}
</style>