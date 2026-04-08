<script>
    let { initialCount } = $props()

    let doubled = $derived(initialCount * 2)
</script>

<h3>Clicks Counter</h3>

<button onclick={() => initialCount++}>
    Clicks: {initialCount}
</button>

<span>doubled is {doubled}</span>