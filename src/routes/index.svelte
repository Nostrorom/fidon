<script context="module">
	export const prerender = true;
</script>

<script>
	import Serie from '$lib/Serie.svelte';
	import series from '$lib/series.json';
</script>

<svelte:head>
	<title>Fidon</title>
</svelte:head>

<section class="grid grid-cols-3">
	{#each series as serie}
		<div class="col-span-1 h-72">
			<Serie {serie} />
		</div>
	{/each}
</section>
