<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Dans les ruines 1',
			src: 'https://i.ibb.co/7SrvdTf/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '150 x 100 cm'
		},
		{
			name: 'Dans les ruines 2',
			src: 'https://i.ibb.co/WzqZcJ3/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '150 x 100 cm'
		},
		{
			name: 'Dans les ruines 3',
			src: 'https://i.ibb.co/nRBqpmm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '150 x 100 cm'
		},
		{
			name: 'Dans les ruines 4',
			src: 'https://i.ibb.co/g9gGT9N/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '150 x 100 cm'
		},
		{
			name: 'Dans les ruines 5',
			src: 'https://i.ibb.co/nBBT9Lz/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '150 x 100 cm'
		},
		{
			name: 'Dans les ruines 6',
			src: 'https://i.ibb.co/Fmw0tdp/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Dans les ruines 7',
			src: 'https://i.ibb.co/DRnLvRF/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Dans les ruines 8',
			src: 'https://i.ibb.co/GnVJpwz/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Dans les ruines 9',
			src: 'https://i.ibb.co/j3YKSmG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 10',
			src: 'https://i.ibb.co/tQLpw60/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 11',
			src: 'https://i.ibb.co/pX1dqXg/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 12',
			src: 'https://i.ibb.co/VCcT9t7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 120 cm'
		},
		{
			name: 'Dans les ruines 13',
			src: 'https://i.ibb.co/LRC9MKr/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 120 cm'
		},
		{
			name: 'Dans les ruines 14',
			src: 'https://i.ibb.co/W3VrfDP/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 150 cm'
		},
		{
			name: 'Dans les ruines 15',
			src: 'https://i.ibb.co/f0ZtRxS/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 150 cm'
		},
		{
			name: 'Dans les ruines 16',
			src: 'https://i.ibb.co/DDMC127/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 120 cm'
		},
		{
			name: 'Dans les ruines 17',
			src: 'https://i.ibb.co/DM7W1jr/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Dans les ruines 18',
			src: 'https://i.ibb.co/Sd74dXK/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Dans les ruines 19',
			src: 'https://i.ibb.co/NYW9tHN/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Dans les ruines 20',
			src: 'https://i.ibb.co/Vp30g8w/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Dans les ruines 21',
			src: 'https://i.ibb.co/KyKg1hV/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Dans les ruines 22',
			src: 'https://i.ibb.co/LJ5MDvs/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Dans les ruines 23',
			src: 'https://i.ibb.co/P9wpT96/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 24',
			src: 'https://i.ibb.co/x1TJtXb/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 25',
			src: 'https://i.ibb.co/g6TBVW9/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 26',
			src: 'https://i.ibb.co/2SrL1PY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 27',
			src: 'https://i.ibb.co/c2f2TfV/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 28',
			src: 'https://i.ibb.co/y0SfXk3/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 80 cm'
		},
		{
			name: 'Dans les ruines 29',
			src: 'https://i.ibb.co/VmbzBmN/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '200 x 100 cm'
		}
	];
</script>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
