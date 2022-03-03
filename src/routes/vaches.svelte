<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Les vaches 1',
			src: 'https://i.ibb.co/n7ys7CV/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '35 x 48 cm'
		},
		{
			name: 'Les vaches 2',
			src: 'https://i.ibb.co/vqvdhw5/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Les vaches 3',
			src: 'https://i.ibb.co/tD73S8J/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '200 x 100 cm'
		},
		{
			name: 'Les vaches 4',
			src: 'https://i.ibb.co/h9s3T6Z/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Les vaches 5',
			src: 'https://i.ibb.co/2t0spgG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		}
	];
</script>

<svelte:head>
	<title>Les vaches</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
