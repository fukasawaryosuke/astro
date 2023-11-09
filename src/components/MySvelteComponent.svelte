<!-- MySvelteComponent.svelte -->

<script>
  let message = "Hello from Svelte!";
</script>

<div class="my-svelte-component">
  <h3>MySvelteComponent</h3>
  <p>{message}</p>
</div>

<style>
  .my-svelte-component {
    background-color: #e0e0e0;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
</style>
