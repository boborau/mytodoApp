<script>
	import Todo from './Todo.svelte';
</script>

<main>
	<h1>REY MYSTERIO'S TO DO LIST!</h1>
	<p> WELCOME TO REY MYSTERIO'S <span class="superCool">SUPER COOL</span> TO DO LIST! BOOYAKA BOOYAKA</p>
	<Todo />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	p {
		color: black;
		font-size: 2rem;
	}

	h1 {
		color: black;
		font-weight: bolder;
		text-transform: uppercase;
		font-size: 5rem;
		border-style: double;
		border-width: 20px;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>