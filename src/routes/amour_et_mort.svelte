<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: "L'amour et la mort 1",
			src: 'https://i.ibb.co/2tM7zyZ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: "L'amour et la mort 2",
			src: 'https://i.ibb.co/gwVthsw/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: "L'amour et la mort 3",
			src: 'https://i.ibb.co/qjwwJq1/SONY-DSC.jpg',
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
