<script>
	import { page } from '$app/stores';
	import Icon from '$lib/components/Icon.svelte';

	let series = [
		{
			title: 'Amour et mort',
			path: 'amour_et_mort'
		},
		{
			title: 'Au revoir et merci',
			path: 'au_revoir_et_merci'
		}
	];
</script>

<header class="w-full h-full flex flex-col items-center text-gray-400">
	<div class="">
		<a href="/">
			<h1 class="font-hand text-3xl text-white p-4 text-center">Jérôme FIDON</h1>
		</a>
	</div>

	<nav class="h-full">
		<ul class="space-y-2 text-white-500 h-full">
			{#each series as serie}
				<li class="">
					<a class="" sveltekit:prefetch href={serie.path}>
						<div
							class="h-full px-4 flex items-center justifiy-center hover:text-white"
							class:text-white={$page.path === serie.path}
						>
							{serie.title}
						</div>
					</a>
				</li>
			{/each}
		</ul>
	</nav>

	<div class="h-6 w-6 pb-8 text-gray-400 hover:text-white">
		<a href="https://github.com/Nostrorom?tab=repositories" target="_blank">
			<Icon icon="instagram" />
		</a>
	</div>
</header>
