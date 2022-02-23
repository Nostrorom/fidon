<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Les errants 1',
			src: 'https://i.ibb.co/yykzSMv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 2',
			src: 'https://i.ibb.co/fNwtb86/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 3',
			src: 'https://i.ibb.co/gPwwdr7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 4',
			src: 'https://i.ibb.co/rppBDRj/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 5',
			src: 'https://i.ibb.co/mJ05tfY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 6',
			src: 'https://i.ibb.co/17Xcj5q/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 7',
			src: 'https://i.ibb.co/8dCJND3/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 8',
			src: 'https://i.ibb.co/RDjTw0d/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 9',
			src: 'https://i.ibb.co/0JsxY0c/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 10',
			src: 'https://i.ibb.co/wzSjBhP/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 11',
			src: 'https://i.ibb.co/hs1pC6g/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 12',
			src: 'https://i.ibb.co/yRw7Xfm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 13',
			src: 'https://i.ibb.co/TMqzRth/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants ',
			src: 'https://i.ibb.co/vc7Khxq/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '3 x 3 m'
		},
		{
			name: 'Les errants 14',
			src: 'https://i.ibb.co/N95xG9p/SONY-DSC.jpg',
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
