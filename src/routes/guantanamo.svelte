<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Guantanamo 1',
			src: 'https://i.ibb.co/5GyhrbY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '185 x 130 cm'
		},
		{
			name: 'Guantanamo 2',
			src: 'https://i.ibb.co/0YFSJWJ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '185 x 130 cm'
		},
		{
			name: 'Guantanamo 3',
			src: 'https://i.ibb.co/YLN9QwG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '185 x 130 cm'
		}
	];
</script>

<svelte:head>
	<title>Guantanamo</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
