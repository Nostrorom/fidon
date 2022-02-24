<script>
	import Header from '$lib/Sidebar.svelte';
	import '../app.css';
	import '@fontsource/zeyada';
</script>

<svelte:head />
<main class="w-full min-h-screen bg-zinc-800  from-zinc-700 to-zinc-700 via-zinc-700 z-0 flex">
	<div class="h-full fixed left-0 w-1/6 z-0">
		<div class="h-full">
			<Header />
		</div>
	</div>

	<div class="w-5/6 ml-auto h-full">
		<slot />
	</div>
</main>
