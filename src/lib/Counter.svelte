<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment}>
  button is clicked {count}
  {count <= 1 ? "time" : "times"}
</button>
