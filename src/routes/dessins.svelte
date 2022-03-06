<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Dessins 1',
			src: 'https://i.ibb.co/DDT221x/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 2',
			src: 'https://i.ibb.co/TqGm5gv/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 3',
			src: 'https://i.ibb.co/c3zzRLJ/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 4',
			src: 'https://i.ibb.co/PW5Td3v/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 5',
			src: 'https://i.ibb.co/Tv628yn/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 6',
			src: 'https://i.ibb.co/H7130sr/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 7',
			src: 'https://i.ibb.co/wJqBgnb/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 8',
			src: 'https://i.ibb.co/4pPQk6j/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 9',
			src: 'https://i.ibb.co/0ZmtVNV/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 10',
			src: 'https://i.ibb.co/Hnwch95/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 11',
			src: 'https://i.ibb.co/R0RH8Qv/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 12',
			src: 'https://i.ibb.co/MZR1kz7/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 13',
			src: 'https://i.ibb.co/6bDMtNQ/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 14',
			src: 'https://i.ibb.co/rwHNYQx/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 15',
			src: 'https://i.ibb.co/CncxfJ1/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 16',
			src: 'https://i.ibb.co/X87Nrtq/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 17',
			src: 'https://i.ibb.co/253FB4W/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 19',
			src: 'https://i.ibb.co/HYzVhnR/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 20',
			src: 'https://i.ibb.co/z4kR8Bw/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 21',
			src: 'https://i.ibb.co/FBmLHJQ/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 22',
			src: 'https://i.ibb.co/TmBVRrC/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 23',
			src: 'https://i.ibb.co/86Mv7sG/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 24',
			src: 'https://i.ibb.co/k8pTsxY/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 25',
			src: 'https://i.ibb.co/b66dRVK/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 26',
			src: 'https://i.ibb.co/Mg3gdWJ/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 27',
			src: 'https://i.ibb.co/CMqw4c9/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 28',
			src: 'https://i.ibb.co/6BWPT5b/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 29',
			src: 'https://i.ibb.co/cgSMchC/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 30',
			src: 'https://i.ibb.co/Tb344NM/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 31',
			src: 'https://i.ibb.co/ydwB91s/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 32',
			src: 'https://i.ibb.co/yYyFKWJ/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 34',
			src: 'https://i.ibb.co/ryRzK1F/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 35',
			src: 'https://i.ibb.co/ysCHZPG/SONY-DSC.jpg',
			technique: 'pastel sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 36',
			src: 'https://i.ibb.co/5GZhvNb/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 37',
			src: 'https://i.ibb.co/bdm1ygy/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 38',
			src: 'https://i.ibb.co/9bCJW5d/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 39',
			src: 'https://i.ibb.co/2vYpTsF/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 40',
			src: 'https://i.ibb.co/KFsnprR/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 41',
			src: 'https://i.ibb.co/2Z6VgKh/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 42',
			src: 'https://i.ibb.co/TcBLpQv/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 43',
			src: 'https://i.ibb.co/JW1YkKK/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 44',
			src: 'https://i.ibb.co/Tcchy5Q/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 45',
			src: 'https://i.ibb.co/cTBJhNQ/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		},
		{
			name: 'Dessins 46',
			src: 'https://i.ibb.co/Ws61dn2/SONY-DSC.jpg',
			technique: 'crayon sur papier',
			dimensions: '21 x 29,7 cm'
		}
	];
</script>

<svelte:head>
	<title>Dessins</title>
</svelte:head>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
