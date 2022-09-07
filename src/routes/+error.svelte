<script>
	import { page } from '$app/stores';
</script>

<div class="error">
	<h1>Toto se tady bohužel nenechází :(</h1>

	<p>chyba: {$page.status}</p>
</div>

<style>
	* {
		font-family: 'Quicksand', sans-serif;
	}

	.error {
		height: 10em;
		width: 50em;
		background-color: #3697a7;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		margin: 0 auto;
		margin-top: 10em;
		margin-bottom: 10em;
		color: white;
	}
</style>
