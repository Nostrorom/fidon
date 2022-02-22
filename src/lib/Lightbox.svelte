<script>
	import { createEventDispatcher } from 'svelte';
	import { scale, fade } from 'svelte/transition';
	export let src;
	const dispatch = createEventDispatcher();

	function toggle() {
		dispatch('toggle');
	}
</script>

<div
	transition:fade={{ duration: 200 }}
	class="fixed top-0 left-0 h-screen w-screen bg-black bg-opacity-90 flex items-center justify-center p-4"
	on:click={toggle}
>
	<img
		transition:scale={{ duration: 200 }}
		{src}
		alt="painting"
		class="object-contain h-full w-full"
	/>
</div>
