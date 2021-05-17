<script>
	import LoginForm from './Login.svelte'
	import LoginLogo from './Login-logo.svelte'
</script>
<div class="main">
	<LoginLogo />
	<LoginForm />

</div>

<style>
	:global(*) {
		margin: 0;
		padding: 0;
	}
	:global(body) {
		background: rgb(65, 121, 167);
	}

	.main {
		display: flex;
		flex-direction: column;
		width: 100%;
		height: 100%;
	}


</style>