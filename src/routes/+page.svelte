<main>
	<h1>KOKODO</h1>
</main>

<style>

:global(body) {
	color: #333;
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

	main {
		height: 100vh;
		background-color: #111;
		font-family: "Major Mono Display";
		text-align: center;
		color: #FFF;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	h1 {
		background-image: url("effect.gif");
		background-size: cover;
		color: transparent;
        background-clip: text;
		text-transform: uppercase;
		font-size: 10vw;
	}

	@media only screen and (min-width: 320px) {
		h1 {
			font-size: 20vw;
		}
	}
	@media only screen and (min-width: 768px) {
		h1 {
			font-size: 15vw;
		}
	}
	@media only screen and (min-width: 980px) {
		h1 {
			font-size: 10vw;
		}
	}
	@media only screen and (min-width: 1280px) {
		h1 {
			font-size: 8vw;
		}
	}
	@media only screen and (min-width: 1600px) {
		h1 {
			font-size: 6vw;
		}
	}
</style>
