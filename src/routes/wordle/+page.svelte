<script>
  // Here the logic for the game will live
</script>

<svelte:window on:keydown={keydown} />

<svelte:head>
    <title>Wordle</title>
    <meta name="description" content="A Wordle App Built By Me" />
</svelte:head>

<h1>Wordle Party Yo!</h1>

<form method="post" action="?/enter">
    {#each Array.from(Array.keys(6)) as row (row)}

    {/each}
</form>
