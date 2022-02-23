<script>
	import { page } from '$app/stores';
	import Icon from '$lib/Icon.svelte';
	import series from '$lib/series.json';
</script>

<header class="w-full h-full  flex flex-col items-center justify-between text-zinc-400 px-2">
	<div class="">
		<a href="/">
			<h1 class="font-hand text-3xl text-amber-400 py-4 px-2 text-center">Jérôme FIDON</h1>
		</a>
	</div>

	<nav class=" overflow-y-scroll w-full ">
		<ul class="space-y-0 text-zinc-300">
			{#each series as serie}
				<li class="w-full ">
					<a sveltekit:prefetch href={serie.path}>
						<div class="relative group">
							<img
								src={serie.image}
								alt={serie.title}
								class="h-14 w-full object-cover grayscale opacity-70 group-hover:grayscale-0 group-hover:opacity-100"
							/>
							<div
								class="absolute top-0 w-full bg-zinc-900 bg-opacity-70 group-hover:bg-opacity-30 leading-tight py-1 px-3 h-full flex items-center justifiy-center hover:text-white"
								class:text-amber-300={$page.url.pathname === serie.path}
							>
								{serie.title}
							</div>
						</div>
					</a>
				</li>
			{/each}
		</ul>
	</nav>

	<div class="h-12 w-6 py-4 text-zinc-400 hover:text-amber-400">
		<a href="https://www.instagram.com/j.fidon/" target="_blank">
			<Icon icon="instagram" />
		</a>
	</div>
</header>
