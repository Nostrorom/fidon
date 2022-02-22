<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Au revoir et merci 1',
			src: 'https://i.ibb.co/pXbjh5S/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 2',
			src: 'https://i.ibb.co/LnYvcfn/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 3',
			src: 'https://i.ibb.co/WB9HbxZ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 4',
			src: 'https://i.ibb.co/z7nLdNh/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 5',
			src: 'https://i.ibb.co/TYNn746/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 6',
			src: 'https://i.ibb.co/6mR3CrT/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 7',
			src: 'https://i.ibb.co/qRHYTH0/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 8',
			src: 'https://i.ibb.co/tZSQZdm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Au revoir et merci 9',
			src: 'https://i.ibb.co/jD81TDM/SONY-DSC.jpg',
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
