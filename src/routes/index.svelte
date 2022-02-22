<script context="module">
	export const prerender = true;
</script>

<script>
	import Category from '$lib/Category.svelte';
	let categories = [
		{
			name: "L'amour et la mort",
			image: 'https://i.ibb.co/2tM7zyZ/SONY-DSC.jpg',
			link: '/amour_et_mort'
		},
		{
			name: 'Au revoir et merci',
			image: 'https://i.ibb.co/pXbjh5S/SONY-DSC.jpg',
			link: '/au_revoir_et_merci'
		},
		{
			name: 'Babel',
			image: 'https://i.ibb.co/wzNSTty/SONY-DSC.jpg',
			link: '/babel'
		},
		{
			name: 'Batailles',
			image: 'https://i.ibb.co/vwhHSf5/SONY-DSC.jpg',
			link: '/batailles'
		}
	];
</script>

<svelte:head>
	<title>Fidon</title>
</svelte:head>

<section class="grid grid-cols-3">
	{#each categories as category}
		<div class="col-span-1 h-72">
			<Category {category} />
		</div>
	{/each}
</section>
