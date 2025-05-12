<script>
	import Navigation from '$lib/components/Navigation.svelte';
</script>

<header>
	<h3>Johan Hammarstedt</h3>
	<Navigation />
</header>

<style>
	header {
		width: 100%;
		height: 75px;
		background-color: black;
		display: flex;
		justify-content: space-evenly;
		align-items: center;
		padding: 10px;
		border-bottom: 1px solid white;
	}

	h3 {
		color: white;
	}
</style>
