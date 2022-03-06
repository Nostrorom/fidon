<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Face à la mer 1',
			src: 'https://i.ibb.co/f1F86kK/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 2',
			src: 'https://i.ibb.co/3T6n17y/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 3',
			src: 'https://i.ibb.co/5F8MMFm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 4',
			src: 'https://i.ibb.co/HPDvQmd/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 5',
			src: 'https://i.ibb.co/ZJZvrgM/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 6',
			src: 'https://i.ibb.co/CnXH2fR/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 7',
			src: 'https://i.ibb.co/4RctCkd/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 8',
			src: 'https://i.ibb.co/Dw9MKd2/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 9',
			src: 'https://i.ibb.co/rsbryY8/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '81 x 65 cm'
		},
		{
			name: 'Face à la mer 10',
			src: 'https://i.ibb.co/kgzDsSV/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 81 cm'
		},
		{
			name: 'Face à la mer 11',
			src: 'https://i.ibb.co/Sdm4mRQ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '65 x 81 cm'
		}
	];
</script>

<svelte:head>
	<title>Face à la mer</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
