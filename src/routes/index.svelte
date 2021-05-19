<script>

import { count } from './../stores/test.js'

function decrement() {
    count.update(n => n - 1);
}
</script>
<h1>Welcome to SvelteKit P {$count}</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<button on:click|preventDefault={decrement}>down</button>
