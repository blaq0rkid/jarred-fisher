<script>
	import Nav from '../components/Nav.svelte';
	import Footer from '../components/Footer.svelte';
	
	export let segment;
</script>

<style>
	main {
		position: relative;
		max-width: 60em;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
		color: black;
		padding-top: 8%;
	}
	
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>

<Footer {segment}/>
