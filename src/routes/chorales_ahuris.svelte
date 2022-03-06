<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: "Chorales d'ahuris 1",
			src: 'https://i.ibb.co/2tyYdjR/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: "Chorales d'ahuris 2",
			src: 'https://i.ibb.co/0F9tLTW/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: "Chorales d'ahuris 3",
			src: 'https://i.ibb.co/9tLpPQm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: "Chorales d'ahuris 4",
			src: 'https://i.ibb.co/ns3Ffv2/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: "Chorales d'ahuris 5",
			src: 'https://i.ibb.co/WfB51Zq/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: "Chorales d'ahuris 6",
			src: 'https://i.ibb.co/BcGNpmm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: "Chorales d'ahuris 7",
			src: 'https://i.ibb.co/f4fS7Dq/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: "Chorales d'ahuris 8",
			src: 'https://i.ibb.co/X7FJRH5/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		}
	];
</script>

<svelte:head>
	<title>Chorales d'ahuris</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
