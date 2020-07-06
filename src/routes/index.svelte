<style>
	.grid {
		display: grid;
		grid-gap: 0rem 0rem;
		grid-template-columns: 21rem auto 21rem;
	}

	.controls {
		width: auto;
		height: auto;
		background: #2B206F;
		display: flex;
		justify-content: center;
	}

	.ctrl-items {
		color: #fff;
	}

	.preview {
		width: auto;
		height: auto;
		background: #E5E5E5;
		color: #000;
		height: 90vh;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.tools {
		width: auto;
		height: auto;
		background: #2B206F;
		display: flex;
		justify-content: center;
	}

	.tls-items {
		color: #fff;

	}

	p {
		text-align: center;
	}

	.page {
		background: #fff;
		color: #000;
		height: 60vh;
		margin: 0rem 7rem;
		display: flex;
		flex: 1;
		width: auto;
		box-shadow: 0px 2px 3px grey;
	}

	button {
		text-align: center;
		width: 17rem;
		padding: 0.8rem 1rem;
		border-radius: 7px;
		border: 1px solid #fff;
		outline: 0px;
		color: #fff;
		background: transparent;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Home | Slides</title>
</svelte:head>

<div>
	<div class="grid">
		<div class="controls">
			<div class="ctrl-items">
				<p> controls </p>

				<button> Import Templates </button>
			</div>

		</div>

		<div class="preview">
			<div class="page">
				<p> item in a page </p>
			</div>
		</div>

		<div class="tools">
			<div class="tls-items">
				<p> tools </p>
				<button> Open Pallete </button>
			</div>
		</div>
	</div>

</div>