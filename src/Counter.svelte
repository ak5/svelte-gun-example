<div>
  <button on:click={() => (value += step)}>+</button>
  {value}
  <button on:click={() => (value -= step)}>-</button>
</div>

<script>
  export let value = 0;
  export let step = 1;
</script>
