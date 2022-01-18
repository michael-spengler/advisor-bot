<script>
  export let name;
  let inputValue;

  function handleClick() {
    alert(
      "das ist ja ein lustiges problem, sei froh dass du keine anderen problemen hast."
    );
  }
</script>

<h1>Hello {name}!</h1>
<p>
  Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how
  to build Svelte apps.
</p>

<input
  type="text"
  bind:value={inputValue}
  placeholder="geben sie ihr thema ein"
/>

<button on:click={handleClick}> Send </button>

<link
  href="https://fonts.googleapis.com/css?family=Overpass:100,400"
  rel="stylesheet"
/>

<style>
  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }
</style>
