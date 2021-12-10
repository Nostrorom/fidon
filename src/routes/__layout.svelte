<script>
	import Header from '$lib/components/Sidebar.svelte';
	import '../app.css';
</script>

<svelte:head />
<main class="w-full bg-gray-600 flex">
	<div class="h-full fixed left-0 w-1/6">
		<div class="h-full font-main">
			<Header />
		</div>
	</div>

	<div class="bg-gray-900 w-4/6 mx-auto">
		<slot />
	</div>
</main>
