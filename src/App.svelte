<script>
  import Counter from './Counter.svelte'
  import { counter } from './stores'
</script>

<p>
  <Counter bind:value={$counter}/>
</p>