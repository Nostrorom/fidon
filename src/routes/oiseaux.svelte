<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Oiseaux 1',
			src: 'https://i.ibb.co/BjghfWt/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 2',
			src: 'https://i.ibb.co/5LTD5mb/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 3',
			src: 'https://i.ibb.co/FXgy5Jh/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 4',
			src: 'https://i.ibb.co/w7JnHqY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 5',
			src: 'https://i.ibb.co/zH2KqL9/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 6',
			src: 'https://i.ibb.co/L8jDr7d/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 7',
			src: 'https://i.ibb.co/cQScBSX/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 8',
			src: 'https://i.ibb.co/TvL2ytQ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 9',
			src: 'https://i.ibb.co/QP7LBCv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 10',
			src: 'https://i.ibb.co/9qYMhT1/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 11',
			src: 'https://i.ibb.co/2ZPfs9B/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Oiseaux 12',
			src: 'https://i.ibb.co/jhSRbHq/SONY-DSC.jpg',
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
