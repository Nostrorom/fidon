<script>
	import Lightbox from './Lightbox.svelte';
	export let pic;

	let showLightbox = false;

	const toggleLightbox = () => {
		showLightbox = !showLightbox;
	};
</script>

{#if showLightbox}
	<Lightbox on:toggle={toggleLightbox} src={pic.src} />
{/if}

<div class="grid lg:grid-cols-5 p-4 sm:p-12 md:p-24 xl:px-48 w-full">
	<div class="w-full lg:col-span-4 lg:pr-12 flex items-center justify-center">
		<img on:click={toggleLightbox} src={pic.src} alt={pic.name} class="max-h-screen shadow-2xl" />
	</div>
	<div class="col-span-1">
		<div
			class="ml-0 lg:ml-2 px-0 lg:px-2 pb-4 mt-3 lg:mt-0 pt-1 lg:pt-0 border-t lg:border-t-0 lg:border-l-2 border-zinc-500 space-y-2"
		>
			<h6 class="italic text-amber-400">
				{pic.name}
			</h6>
			<p class="text-zinc-400 text-sm">
				{pic.technique}
			</p>
			<p class="text-zinc-400 text-sm">
				{pic.dimensions}
			</p>
		</div>
	</div>
</div>
