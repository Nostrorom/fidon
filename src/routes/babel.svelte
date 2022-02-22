<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Babel 1',
			src: 'https://i.ibb.co/wzNSTty/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 2',
			src: 'https://i.ibb.co/t4wbhmy/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 3',
			src: 'https://i.ibb.co/TkBf5fY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 4',
			src: 'https://i.ibb.co/cX8jC4W/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 5',
			src: 'https://i.ibb.co/brtxRF9/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 6',
			src: 'https://i.ibb.co/NTvHsLX/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 7',
			src: 'https://i.ibb.co/tDMRQWq/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 8',
			src: 'https://i.ibb.co/g9ZnnLS/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 9',
			src: 'https://i.ibb.co/cxGF0p4/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 10',
			src: 'https://i.ibb.co/StWYHLn/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Babel 11',
			src: 'https://i.ibb.co/6FNsh0t/SONY-DSC.jpg',
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
