<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Morceaux choisis 1',
			src: 'https://i.ibb.co/Lp9KRxL/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Morceaux choisis 2',
			src: 'https://i.ibb.co/MGTnBzb/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Morceaux choisis 3',
			src: 'https://i.ibb.co/8rpKt9r/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Morceaux choisis 4',
			src: 'https://i.ibb.co/K2yZrgV/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Morceaux choisis 5',
			src: 'https://i.ibb.co/KXKKpvR/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Morceaux choisis 6',
			src: 'https://i.ibb.co/C2TWHBR/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Morceaux choisis 7',
			src: 'https://i.ibb.co/pZ2kXZv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Morceaux choisis 8',
			src: 'https://i.ibb.co/XstKTnr/SONY-DSC.jpg',
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
