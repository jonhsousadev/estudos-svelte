<script>
  export let primeiroNome;
  export let sobrenome;
  let count = 0
  
  // Declarações reativas
  $: nomeCompleto = primeiroNome+' '+sobrenome
  $: {
    console.log(`O valor de count agora é: ${count}`)
  }

  function somarUm() {
    count++
  }

</script>

<div>
  Seu primeiro nome é: {primeiroNome} e seu sobrenome é: {sobrenome}, logo seu nome completo é: {nomeCompleto}
  <button on:click={somarUm}>
    somar 1: {count}
  </button>
</div>
