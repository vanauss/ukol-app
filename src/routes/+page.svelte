<section class="hero">
	<div>
		<h1>Jack Jackson</h1>
		<p>
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
			labore et dolore magna aliqua. Viverra nibh cras pulvinar mattis. Lacus laoreet non curabitur
			gravida arcu ac tortor dignissim. Sodales ut eu sem integer vitae justo eget. Euismod
			elementum nisi quis eleifend.
		</p>
		<button>learn more</button>
	</div>

	<div class="photo">
		<img src="/pics/ukol_app_portrait.webp" alt="Here, in future, we be some page data ans params" />
	</div>
</section>

<section class="work">
	<h2>What i did</h2>

	<div class="list">
		<div class="list-item">
			<img src="/pics/ukol_app_work1.webp" alt="Here, in future, we be some page data ans params" />
			<div>
				<h3>epic project from scratch</h3>
				<p>sed do eiusmod tempor incididunt ut labore et</p>
			</div>
		</div>

		<div class="list-item">
			<img src="/pics/ukol_app_work2.webp" alt="Here, in future, we be some page data ans params" />
			<div>
				<h3>Another work i did</h3>
				<p>Sodales ut eu sem integer vitae justo eget.</p>
			</div>
		</div>

		<div class="list-item">
			<img src="/pics/ukol_app_work3.webp" alt="Here, in future, we be some page data ans params" />
			<div>
				<h3>rebrand of this company</h3>
				<p>Euismod elementum nisi quis eleifend.</p>
			</div>
		</div>
	</div>
</section>

<style>
	* {
		font-family: 'Quicksand', sans-serif;
	}

	h1 {
		font-size: 3em;
	}

	h2 {
		font-size: 2em;
	}
	.hero {
		display: flex;
		color: #d2d6d4;
		margin: 4em 10em;
		padding: 0em 2.5em;
	}

	.hero div:first-child {
		padding-right: 25em;
	}

	.hero p {
		margin: 3em 0em;
		font-weight: bold;
	}

	.work {
		margin: 4em 10em;
		padding: 0em 2.5em;
		margin-bottom: 12em;
	}

	.list {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
	}

	.list-item {
		width: auto;
		max-width: 450px;
		background-color: rgb(54, 151, 167);
		color: #abd5d8;
		text-align: center;
	}

	.list-item h3 {
		text-transform: uppercase;
	}

	.list-item img {
		width: auto;
		max-width: 450px;
	}

	.list-item:hover {
		cursor: pointer;
	}
	.work h2 {
		text-transform: uppercase;
		color: rgb(122, 124, 123);
	}

	button {
		border-radius: 0px;
		border: none;
		color: white;
		background-color: #3697a7;
		text-transform: uppercase;
		padding: 0.4em 6em;
	}

	button:hover {
		cursor: pointer;
	}

	@media only screen and (max-width: 850px) {
		div {
			width: auto;
			max-width: 100vw;
		}

		.list-item {
			max-width: 200px;
		}

		.list-item img {
			width: auto;
			max-width: 200px;
		}

		.hero {
			margin: 0em 1em;
		}

		.hero div:first-child {
			padding-right: 5em;
		}

		.work {
			margin: 1em 1em;
			padding: 0em 2.5em;
			margin-bottom: 2em;
		}

		.photo img {
			max-width: 350px;
			padding-top: 3em;
		}
	}

	@media only screen and (min-width: 850px) and (max-width: 1800px) {
		.hero {
			margin: 0em 1em;
		}

		.hero div:first-child {
			padding-right: 1em;
		}

		.photo img {
			max-width: 300px;
			padding-top: 3em;
		}

		.work {
			margin: 1em 1em;
			padding: 0em 2.5em;
			margin-bottom: 2em;
		}

		.list-item {
			width: 320px;
			max-width: 100vw;
			margin-bottom: 5em;
		}

		.list-item img,
		.photo img {
			width: 100%;
			max-width: 86vw;
		}
	}

	@media only screen and (max-width: 767px) {
		.list {
			display: flex;
			flex-direction: column;
		}

		.list-item {
			width: auto;
			max-width: 100vw;
			margin-bottom: 5em;
		}

		.list-item img,
		.photo img {
			width: 100%;
			max-width: 86vw;
		}

		.hero {
			display: flex;
			flex-direction: column;
		}

		.hero div:first-child {
			padding-right: 0em;
		}

		.hero p {
			margin: 3em 0em;
			font-weight: bold;
		}

		button {
			margin-left: 25%;
			margin-right: 25%;
		}
	}
</style>
