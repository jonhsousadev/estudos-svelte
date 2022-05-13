<script>
	import Exercicio1 from './exercicios/Exercicio1.svelte'
	import Exercicio2 from './exercicios/Exercicio2.svelte'
	import Exercicio3 from './exercicios/Exercicio3.svelte'
	import Exercicio4 from './exercicios/Exercicio4.svelte'
	export let name;
</script>

<main>
	<p>Executando exercício 1:</p>
	<Exercicio1 {name}></Exercicio1>
	<hr>
	<p>Executando exercício 2:</p>
	<Exercicio2></Exercicio2>
	<p>Executando exercício 3:</p>
	<Exercicio3 value1="5" value2="2"></Exercicio3>
	<p>Executando exercício 4:</p>
	<Exercicio4 primeiroNome="Jonh" sobrenome="Sousa"></Exercicio4>
	<hr>
</main>

<style lang="scss">
	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}
</style>