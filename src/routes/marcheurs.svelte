<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Les marcheurs 1',
			src: 'https://i.ibb.co/jVZzCng/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Les marcheurs 2',
			src: 'https://i.ibb.co/hBbgrw0/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Les marcheurs 3',
			src: 'https://i.ibb.co/qy39ScK/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Les marcheurs 4',
			src: 'https://i.ibb.co/Sd6GxDp/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		},
		{
			name: 'Les marcheurs 5',
			src: 'https://i.ibb.co/x8gRmpD/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '70 x 50 cm'
		}
	];
</script>

<svelte:head>
	<title>Les marcheurs</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
