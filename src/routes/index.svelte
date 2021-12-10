<script context="module">
	export const prerender = true;
</script>

<script>
	import Card from '$lib/components/Card.svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section class="">
	<Card>
		<div slot="header">nosdev</div>
		<div slot="content" class="space-y-2">
			Well, this is here. Less complex than Kava World, it provides a quick look at the way I code,
			striving for clean, clear and dry.
		</div>
	</Card>
</section>
