<script lang="ts">
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button class="text-[3rem] cursor-pointer" on:click={increment}>
  count is {count}
</button>
