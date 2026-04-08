<script>
    let count = $state(0)

    console.log("hello world")
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<button onclick={() => count++}>
    Clicks: {count}
</button>

<style>
    h1 {
        color: deepskyblue;
    }
</style>