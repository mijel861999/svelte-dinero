<script>
  let count = 0;
  function handleClick() {
    count += 1;
  }
</script>

<div class="button">
  <button on:click={handleClick}>Click me: {count}</button>
</div>

<style></style>
