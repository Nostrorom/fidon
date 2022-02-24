<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Recueillement 1',
			src: 'https://i.ibb.co/jH1qq9r/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '40 x 60 cm'
		},
		{
			name: 'Recueillement 2',
			src: 'https://i.ibb.co/8K489Ws/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 185 cm'
		},
		{
			name: 'Recueillement 3',
			src: 'https://i.ibb.co/xL9mkN6/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 185 cm'
		},
		{
			name: 'Recueillement 4',
			src: 'https://i.ibb.co/DVNmnxz/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 185 cm'
		},
		{
			name: 'Recueillement 5',
			src: 'https://i.ibb.co/jgt8mBq/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '100 x 185 cm'
		}
	];
</script>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
