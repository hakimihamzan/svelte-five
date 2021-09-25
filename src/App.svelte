<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Pariatur nulla earum minus perferendis sunt, illum iste excepturi reiciendis itaque sed.</p>
	<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, dolor nihil. Consectetur expedita eaque labore magni voluptatum quam reprehenderit debitis.</p>
	<h4>Lorem ipsum dolor sit amet consectetur adipisicing elit.</h4>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>