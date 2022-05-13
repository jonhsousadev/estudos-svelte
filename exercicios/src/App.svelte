<script>
	import Exercicio1 from './exercicios/Exercicio1.svelte'
	export let name;
</script>

<main>
	<p>Executando exercício 1:</p>
	<Exercicio1 {name}></Exercicio1>
	<hr>
</main>

<style lang="scss">
	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
		
	}
</style>