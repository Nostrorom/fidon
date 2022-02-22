<script>
	import { page } from '$app/stores';
	import Icon from '$lib/Icon.svelte';

	let series = [
		{
			title: "L'amour et la mort",
			path: '/amour_et_mort',
			image: 'https://i.ibb.co/2tM7zyZ/SONY-DSC.jpg'
		},
		{
			title: 'Au revoir et merci',
			path: '/au_revoir_et_merci',
			image: 'https://i.ibb.co/pXbjh5S/SONY-DSC.jpg'
		},
		{
			title: 'Babel',
			path: '/babel',
			image: 'https://i.ibb.co/wzNSTty/SONY-DSC.jpg'
		},
		{
			title: 'Batailles',
			path: '/batailles',
			image: 'https://i.ibb.co/vwhHSf5/SONY-DSC.jpg'
		}
	];

	$: console.log($page.path);
</script>

<header class="w-full h-full flex flex-col items-center text-zinc-400">
	<div class="">
		<a href="/">
			<h1 class="font-hand text-3xl text-amber-400 py-4 px-4 text-left">Jérôme FIDON</h1>
		</a>
	</div>

	<nav class="h-full w-full px-2">
		<ul class="space-y-1 text-zinc-300">
			{#each series as serie}
				<li class="w-full ">
					<a sveltekit:prefetch href={serie.path}>
						<div class="relative group">
							<img
								src={serie.image}
								alt={serie.title}
								class="h-12 w-full object-cover grayscale opacity-70 group-hover:grayscale-0 group-hover:opacity-100"
							/>
							<div
								class="absolute top-0 w-full bg-zinc-900 bg-opacity-70 group-hover:bg-opacity-30 leading-tight py-1 px-3 h-full flex items-center justifiy-center hover:text-white"
								class:text-amber-300={$page.path === serie.path}
							>
								{serie.title}
							</div>
						</div>
					</a>
				</li>
			{/each}
		</ul>
	</nav>

	<div class="h-6 w-6 pb-8 text-zinc-400 hover:text-amber-400">
		<a href="https://www.instagram.com/j.fidon/" target="_blank">
			<Icon icon="instagram" />
		</a>
	</div>
</header>
