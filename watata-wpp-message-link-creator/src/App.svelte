<script>
	export let name;
	let phone = '85991633993'
	let greeting = 'Hello'
	let personName = 'Jonh'
	let message = 'this is a test'
	let generatedMessage = ''

	const generateMessage = () => {
		generatedMessage = `https://wa.me/${phone}?text=${greeting} ${personName}%0${message}`
	}

	generateMessage()

</script>

<div id="container">
	<aside>
		<h1>Watata...</h1>
		<p>Let's create your Whatsapp message?</p>
	</aside>
	<main>
		<h1>Insert your data and create your message</h1>
		<a href={generatedMessage}>{generatedMessage}</a>
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