<script>
	import Header from '$lib/components/Sidebar.svelte';
	import '../app.css';
	import '@fontsource/zeyada';
</script>

<svelte:head />
<main class="w-full min-h-screen bg-gray-600 flex">
	<div class="h-full fixed left-0 w-1/6">
		<div class="h-full">
			<Header />
		</div>
	</div>

	<div class=" w-4/6 mx-auto">
		<slot />
	</div>
</main>
