<script lang="ts">
	export let name: string;

	function x () {
		console.log('hi')
	}
</script>

<main>
	<h1 class="text-lg hover:text-blue-700 hover:font-medium" on:click="{x}">Hello {name}!</h1>
	<button on:click={x}>click me</button>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style lang="postcss" global>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>