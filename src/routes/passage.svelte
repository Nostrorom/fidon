<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Le passage 1',
			src: 'https://i.ibb.co/02nDtp7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Le passage 2',
			src: 'https://i.ibb.co/Hgx8G2Q/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Le passage 3',
			src: 'https://i.ibb.co/LpKKGNT/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Le passage 4',
			src: 'https://i.ibb.co/TT9n8kV/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Le passage 5',
			src: 'https://i.ibb.co/kJh9BZN/SONY-DSC.jpg',
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
