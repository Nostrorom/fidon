<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Guantanamo 1',
			src: 'https://i.ibb.co/5GyhrbY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Guantanamo 2',
			src: 'https://i.ibb.co/0YFSJWJ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Guantanamo 3',
			src: 'https://i.ibb.co/YLN9QwG/SONY-DSC.jpg',
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
