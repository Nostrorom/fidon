<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Migrants 1',
			src: 'https://i.ibb.co/fCsMJRM/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '185 x 150 cm'
		},
		{
			name: 'Migrants 2',
			src: 'https://i.ibb.co/CwL3rCN/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '185 x 150 cm'
		},
		{
			name: 'Migrants 3',
			src: 'https://i.ibb.co/0cPy9L3/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '185 x 150 cm'
		},
		{
			name: 'Migrants 4',
			src: 'https://i.ibb.co/r7D64VG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Migrants 5',
			src: 'https://i.ibb.co/cwdf1vH/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Migrants 6',
			src: 'https://i.ibb.co/qknd4b6/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Migrants 7',
			src: 'https://i.ibb.co/BgYRHSk/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '40 x 60 cm'
		}
	];
</script>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
