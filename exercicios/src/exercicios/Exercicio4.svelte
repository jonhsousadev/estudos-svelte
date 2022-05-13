<script>
  export let primeiroNome;
  export let sobrenome;
  $: nomeCompleto = primeiroNome+' '+sobrenome

</script>

<div>
  Seu primeiro nome é: {primeiroNome} e seu sobrenome é: {sobrenome}, logo seu nome completo é: {nomeCompleto}
</div>
