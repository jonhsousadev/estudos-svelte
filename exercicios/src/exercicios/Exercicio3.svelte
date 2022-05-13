<script>
  export let value1;
  export let value2;
  let result = 0

  const soma = () => {
    result = parseInt(value1) + parseInt(value2)
  }

</script>

<div>
  O valor da soma é: {result}
  <button on:click={soma}>
    Somar
  </button>
</div>
