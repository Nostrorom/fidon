<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Batailles 1',
			src: 'https://i.ibb.co/vwhHSf5/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Batailles 2',
			src: 'https://i.ibb.co/C5xRyGG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Batailles 3',
			src: 'https://i.ibb.co/pd5Mzf7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Batailles 4',
			src: 'https://i.ibb.co/9V0FhNd/batailles-4.jpg',
			technique: 'encre sur papier',
			dimensions: '20 x 20 cm'
		},
		{
			name: 'Batailles 5',
			src: 'https://i.ibb.co/xJzcJX4/batailles-5.jpg',
			technique: 'encre sur papier',
			dimensions: '20 x 20 cm'
		},
		{
			name: 'Batailles 6',
			src: 'https://i.ibb.co/3m3VDc6/batailles-6.jpg',
			technique: 'encre sur papier',
			dimensions: '20 x 20 cm'
		},
		{
			name: 'Batailles 7',
			src: 'https://i.ibb.co/tcZ3B9k/batailles-7.jpg',
			technique: 'encre sur papier',
			dimensions: '20 x 20 cm'
		}
	];
</script>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
