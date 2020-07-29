<script lang="ts">
	import './assets/styles/main.css';
	export let name: string;
</script>

<style>
	.center {
		@apply flex justify-center;
	}
</style>

<main>
	<div class="flex justify-center">
		<h1 class="text-6xl text-gray-700">Hello there {name}!</h1>
	</div>
	<div class="center">
		<p class="text-gray-700 text-xl">Visit the <a class="text-blue-600" href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	</div>
</main>