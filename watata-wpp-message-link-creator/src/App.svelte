<script>
	export let name;
</script>

<div id="container">
	<aside>
		<h1>Watata...</h1>
		<p>Let's create your Whatsapp message?</p>
	</aside>
	<main>
		<h1>Hello {name}!</h1>
		<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	</main>
</div>

<style lang="scss">

	#container {
		display: flex;
		flex-flow: row nowrap;
		height: 100vh;

		aside {
			width: 30vw;
		}
		
		main {
			flex: 1;
			text-align: center;
			padding: 1em;
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
	}
</style>