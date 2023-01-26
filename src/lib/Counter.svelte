<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };

  const down = () => {
    count -= 1;
  };
</script>

<button on:click={increment}>
  count is {count}
</button>

<button on:click={down}>
  count is {count}
</button>
