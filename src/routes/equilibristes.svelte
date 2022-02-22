<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Les équilibristes 1',
			src: 'https://i.ibb.co/b1P2Zkn/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 2',
			src: 'https://i.ibb.co/WDpcYFj/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 3',
			src: 'https://i.ibb.co/j62xFrB/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 4',
			src: 'https://i.ibb.co/R7v2kgJ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 5',
			src: 'https://i.ibb.co/jbjSbTt/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 6',
			src: 'https://i.ibb.co/j6r4WTL/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 7',
			src: 'https://i.ibb.co/rwt5szn/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 8',
			src: 'https://i.ibb.co/njtMgdk/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 9',
			src: 'https://i.ibb.co/X5SGHYV/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 10',
			src: 'https://i.ibb.co/HqkY9PZ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 11',
			src: 'https://i.ibb.co/GJ8wPV3/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 12',
			src: 'https://i.ibb.co/DKLQBLR/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 13',
			src: 'https://i.ibb.co/nkHyZZX/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les équilibristes 14',
			src: 'https://i.ibb.co/CHFC2fn/SONY-DSC.jpg',
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
