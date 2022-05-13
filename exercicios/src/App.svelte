<script>
	import Exercicio1 from './exercicios/Exercicio1.svelte'
	import Exercicio2 from './exercicios/Exercicio2.svelte'
	export let name;
</script>

<main>
	<p>Executando exercício 1:</p>
	<Exercicio1 {name}></Exercicio1>
	<hr>
	<p>Executando exercício 1:</p>
	<Exercicio2></Exercicio2>
	<hr>
</main>

<style lang="scss">
	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}
</style>