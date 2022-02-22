<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Les épaves 1',
			src: 'https://i.ibb.co/qmx8sZq/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 2',
			src: 'https://i.ibb.co/gVT5pc7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 3',
			src: 'https://i.ibb.co/vdfxvz7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 4',
			src: 'https://i.ibb.co/bPq65Ww/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 5',
			src: 'https://i.ibb.co/JvzGWQs/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 6',
			src: 'https://i.ibb.co/9V4gXrR/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 7',
			src: 'https://i.ibb.co/QQRcp15/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 8',
			src: 'https://i.ibb.co/vxpkCsZ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 9',
			src: 'https://i.ibb.co/h7QHTKj/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 10',
			src: 'https://i.ibb.co/6869RDY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 11',
			src: 'https://i.ibb.co/cQQc82n/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},

		{
			name: 'Les épaves 12',
			src: 'https://i.ibb.co/B25ScSM/SONY-DSC.jpg',
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
