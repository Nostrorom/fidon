<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Mères éplorées 1',
			src: 'https://i.ibb.co/q5Chc91/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 150 cm'
		},
		{
			name: 'Mères éplorées 2',
			src: 'https://i.ibb.co/vw5gmqH/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 150 cm'
		},
		{
			name: 'Mères éplorées 3',
			src: 'https://i.ibb.co/kc49nwG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 150 cm'
		},
		{
			name: 'Mères éplorées 4',
			src: 'https://i.ibb.co/QjZ1fCv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 150 cm'
		},
		{
			name: 'Mères éplorées 5',
			src: 'https://i.ibb.co/tPVjdq9/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 150 cm'
		}
	];
</script>

<svelte:head>
	<title>Mères éplorées</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
