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

<div class="flex py-4 " on:click={toggleLightbox}>
	<div class="w-4/5 flex items-center justify-center">
		<img src={pic.src} alt={pic.name} class="max-h-screen shadow-2xl" />
	</div>
	<div class="w-1/5">
		<div class="ml-2 px-2 pb-6 border-l-2 border-zinc-500 space-y-2">
			<h6 class="italic text-amber-300">
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
