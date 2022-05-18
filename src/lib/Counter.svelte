<script lang="ts">
  import Button from '$lib/Button.svelte';

  let count = 0;

  function increment() {
    count++;
  }
</script>

<Button on:click={increment}>+</Button>
<span>{count}</span>

