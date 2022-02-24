<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Trombines 1',
			src: 'https://i.ibb.co/SRCY7D9/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Trombines 2',
			src: 'https://i.ibb.co/CsmNtmq/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Trombines 3',
			src: 'https://i.ibb.co/W5LtRkS/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Trombines 4',
			src: 'https://i.ibb.co/mJtZ4s7/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Trombines 5',
			src: 'https://i.ibb.co/d0JRg1L/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Trombines 6',
			src: 'https://i.ibb.co/6s5Htw0/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Trombines 7',
			src: 'https://i.ibb.co/zr6G7Hs/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '120 x 100 cm'
		},
		{
			name: 'Trombines 8',
			src: 'https://i.ibb.co/jVnmCbT/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 9',
			src: 'https://i.ibb.co/Lv9tgXz/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 10',
			src: 'https://i.ibb.co/Mn8j4KT/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 11',
			src: 'https://i.ibb.co/VpNjWdG/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 12',
			src: 'https://i.ibb.co/b60QPm0/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 13',
			src: 'https://i.ibb.co/N1dG9yn/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 14',
			src: 'https://i.ibb.co/XWTp1ny/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 15',
			src: 'https://i.ibb.co/16Lcpvy/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 16',
			src: 'https://i.ibb.co/VJVsV2c/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 17',
			src: 'https://i.ibb.co/w4Nhhzx/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 18',
			src: 'https://i.ibb.co/bvMCvgY/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 19',
			src: 'https://i.ibb.co/zxzvnt5/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 20',
			src: 'https://i.ibb.co/hVgxbXz/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 21',
			src: 'https://i.ibb.co/0MzBWnr/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 22',
			src: 'https://i.ibb.co/02wRxVC/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 23',
			src: 'https://i.ibb.co/TcwXxsv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 24',
			src: 'https://i.ibb.co/pyf4Yyv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 25',
			src: 'https://i.ibb.co/5ss05vv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 26',
			src: 'https://i.ibb.co/31Rp9WF/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 27',
			src: 'https://i.ibb.co/cFHxgxs/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 28',
			src: 'https://i.ibb.co/K7qVy4J/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 29',
			src: 'https://i.ibb.co/VqryPHR/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 30',
			src: 'https://i.ibb.co/qsKSPKF/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 31',
			src: 'https://i.ibb.co/G0JDy2k/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 32',
			src: 'https://i.ibb.co/YQMNWH8/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 33',
			src: 'https://i.ibb.co/4YgPD4z/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 34',
			src: 'https://i.ibb.co/TrQsyFy/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 35',
			src: 'https://i.ibb.co/7b2VPbw/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 36',
			src: 'https://i.ibb.co/hXVC9pZ/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 37',
			src: 'https://i.ibb.co/cFhtMrN/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 38',
			src: 'https://i.ibb.co/2y0kLwv/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 39',
			src: 'https://i.ibb.co/vQT25Fh/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 40',
			src: 'https://i.ibb.co/MgZ8j2q/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 41',
			src: 'https://i.ibb.co/wsSncBL/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 42',
			src: 'https://i.ibb.co/rkLx3tS/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 43',
			src: 'https://i.ibb.co/XSy9HRb/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 44',
			src: 'https://i.ibb.co/PWPF9Tm/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 45',
			src: 'https://i.ibb.co/hy8tbbW/SONY-DSC.jpg',
			technique: 'huile sur toile',
			dimensions: '50 x 70 cm'
		},
		{
			name: 'Trombines 46',
			src: 'https://i.ibb.co/sykzxtm/SONY-DSC.jpg',
			technique: 'installation',
			dimensions: ''
		}
	];
</script>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
