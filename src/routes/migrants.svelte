<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Migrants 1',
			src: 'https://i.ibb.co/fCsMJRM/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Migrants 2',
			src: 'https://i.ibb.co/CwL3rCN/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Migrants 3',
			src: 'https://i.ibb.co/0cPy9L3/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Migrants 4',
			src: 'https://i.ibb.co/r7D64VG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Migrants 5',
			src: 'https://i.ibb.co/cwdf1vH/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Migrants 6',
			src: 'https://i.ibb.co/qknd4b6/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Migrants 7',
			src: 'https://i.ibb.co/BgYRHSk/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		}
	];
</script>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
