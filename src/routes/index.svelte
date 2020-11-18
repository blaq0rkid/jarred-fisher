<script>
	import image1 from 'images/image1.jpg';
</script>

<style>
	h1, h2, figure {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	main {
		background-image: url(https://images.unsplash.com/photo-1521587760476-6c12a4b040da?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=400&q=60);
		background-position: center;
        background-repeat: no-repeat;
		background-size: cover;
		position: sticky;
	}

	.bg {
        background: rgba(255, 255, 255, 0.7);
       }

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Jarred Fisher, Esq.</title>
</svelte:head>

<main>
	<div class="bg">
<h1>Jarred Fisher, Esq.</h1>

<figure>
	<img alt="Man in suit" src="{image1}">
	<figcaption>Estate Planning and Elder Law</figcaption>
</figure>

<h2>Helping you navigate life, after death, and disability. </h2><br>
<h2>We help families when there's been a death in the family, or when a loved one has a disability.</h2><br>

<h2>Call now for a free consultation!</h2>
</div>
</main>