<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Bestiaire 1',
			src: 'https://i.ibb.co/mXwTPnC/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Bestiaire 2',
			src: 'https://i.ibb.co/VMsKhVk/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 120 cm'
		},
		{
			name: 'Bestiaire 3',
			src: 'https://i.ibb.co/fSp5mtp/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '67 x 48 cm'
		},
		{
			name: 'Bestiaire 4',
			src: 'https://i.ibb.co/DDZ174x/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Bestiaire 5',
			src: 'https://i.ibb.co/1JgyPGh/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Bestiaire 6',
			src: 'https://i.ibb.co/pz30bLg/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Bestiaire 7',
			src: 'https://i.ibb.co/MsGt2bN/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '130 x 85 cm'
		},
		{
			name: 'Bestiaire 8',
			src: 'https://i.ibb.co/S3NTzhP/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Bestiaire 9',
			src: 'https://i.ibb.co/C6yJKFm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Bestiaire 10',
			src: 'https://i.ibb.co/G30pHms/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Bestiaire 11',
			src: 'https://i.ibb.co/r0DN8w0/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Bestiaire 12',
			src: 'https://i.ibb.co/hLxbHtL/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '80 x 65 cm'
		},
		{
			name: 'Bestiaire 13',
			src: 'https://i.ibb.co/RTVRq9Z/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '150 x 100 cm'
		},
		{
			name: 'Bestiaire 14',
			src: 'https://i.ibb.co/bH9CdpC/SONY-DSC.jpg',
			technique: 'installation',
			dimensions: ''
		}
	];
</script>

<svelte:head>
	<title>Bestiaire</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
