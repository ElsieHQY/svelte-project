<script>
	import IconLogo from '../components/icons/logo/IconLogo.svelte';
</script>

<header>
	<div class="logo">
		<IconLogo />
	</div>
	<div class="menu">
		<div class="menu-icon">
			<div />
			<div />
			<div />
		</div>
	</div>
</header>

<style>
	header {
		height: 55px;
		border-bottom: 1px solid gray;
		display: flex;
		align-items: center;
		justify-content: space-between;
	}

	.logo {
		border-right: 1px solid gray;
		height: 100%;
		display: flex;
		align-items: center;
		padding: 0 14px;
		/* box-sizing: border-box; */
	}

	.menu {
		height: 100%;
		width: 55px;
		display: flex;
		justify-content: center;
		flex-direction: column;
		align-items: center;
	}

	.menu-icon {
		height: 24px;
		width: 33px;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-between;
	}

	.menu-icon div {
		height: 4px;
		border-radius: 2px;
		width: 100%;
		background-color: black;
	}
</style>
