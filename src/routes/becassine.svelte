<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Bécassine 1',
			src: 'https://i.ibb.co/YLy1tXF/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 2',
			src: 'https://i.ibb.co/pQ30rzB/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 3',
			src: 'https://i.ibb.co/JF7cXVF/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 4',
			src: 'https://i.ibb.co/1GtF1cF/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 5',
			src: 'https://i.ibb.co/HNsTJn2/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 6',
			src: 'https://i.ibb.co/2MrW5wJ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 7',
			src: 'https://i.ibb.co/VCNbgkw/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 8',
			src: 'https://i.ibb.co/Pmv27R7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bécassine 9',
			src: 'https://i.ibb.co/T0V8zVT/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		}
	];
</script>

<svelte:head>
	<title>Bécassine</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
