<script>
	export let info;
</script>

<main>
	<h1>{info}</h1>
</main>

<style>
	main {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (max-width: 380px) {
		h1 {
			font-size: 3em;
		}
	}
</style>