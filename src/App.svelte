<main>
	<h1>KOKODO</h1>
</main>

<style>
	main {
		background-color: #111;
		font-family: "Major Mono Display";
		text-align: center;
		color: #FFF;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		height: 100vh;
		letter-spacing: 1px;
	}

	h1 {
		background-image: url("/images/effect.gif");
		background-size: cover;
		color: transparent;
		-moz-background-clip: text;
		-webkit-background-clip: text;
		text-transform: uppercase;
		font-size: 120px;
		margin: 10px 0;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>