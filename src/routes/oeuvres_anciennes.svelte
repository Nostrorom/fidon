<script>
	import Pic from '$lib/Pic.svelte';
	let pics = [
		{
			name: 'Œuvres anciennes 1',
			src: 'https://i.ibb.co/SX3cszz/oeuvres-anciennes-1.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 2',
			src: 'https://i.ibb.co/k329sQP/oeuvres-anciennes-2.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 3',
			src: 'https://i.ibb.co/3mD6Bq3/oeuvres-anciennes-3.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 4',
			src: 'https://i.ibb.co/Nyk8yfM/oeuvres-anciennes-4.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 5',
			src: 'https://i.ibb.co/3FgyPXQ/oeuvres-anciennes-5.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 6',
			src: 'https://i.ibb.co/CVzf6HB/oeuvres-anciennes-6.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 7',
			src: 'https://i.ibb.co/98yNKCx/oeuvres-anciennes-7.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 8',
			src: 'https://i.ibb.co/tH4qddd/oeuvres-anciennes-8.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 9',
			src: 'https://i.ibb.co/N6Psx2c/oeuvres-anciennes-9.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 10',
			src: 'https://i.ibb.co/yRJKnsn/oeuvres-anciennes-10.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 11',
			src: 'https://i.ibb.co/cvtx4QY/oeuvres-anciennes-11.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 12',
			src: 'https://i.ibb.co/DV626Xg/oeuvres-anciennes-12.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 13',
			src: 'https://i.ibb.co/YZyY8VG/oeuvres-anciennes-13.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 14',
			src: 'https://i.ibb.co/zhtkDNX/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 15',
			src: 'https://i.ibb.co/3Cyxyn4/oeuvres-anciennes-15.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 16',
			src: 'https://i.ibb.co/NFm288T/oeuvres-anciennes-16.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 17',
			src: 'https://i.ibb.co/LvzK2Cx/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 18',
			src: 'https://i.ibb.co/dDbttvM/oeuvres-anciennes-18.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 19',
			src: 'https://i.ibb.co/WFc0fK2/oeuvres-anciennes-19.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 20',
			src: 'https://i.ibb.co/MGSTM8c/oeuvres-anciennes-20.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 21',
			src: 'https://i.ibb.co/nbNxWvn/oeuvres-anciennes-21.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 22',
			src: 'https://i.ibb.co/sFfctKd/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'huile sur toile',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 23',
			src: 'https://i.ibb.co/Jzb7T9m/oeuvres-anciennes-23.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 24',
			src: 'https://i.ibb.co/0Bh009S/oeuvres-anciennes-24.jpg',
			technique: 'encre sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 25',
			src: 'https://i.ibb.co/N2XzDm8/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 26',
			src: 'https://i.ibb.co/0FGk57p/oeuvres-anciennes-26.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 27',
			src: 'https://i.ibb.co/LZwzhb1/oeuvres-anciennes-27.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 28',
			src: 'https://i.ibb.co/ZLK6JS9/oeuvres-anciennes-28.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 29',
			src: 'https://i.ibb.co/FHKqvzz/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'huile sur toile',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 30',
			src: 'https://i.ibb.co/tmzQKKk/oeuvres-anciennes-30.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 31',
			src: 'https://i.ibb.co/80fGbtj/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 32',
			src: 'https://i.ibb.co/WnkmGvh/oeuvres-anciennes-32.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 33',
			src: 'https://i.ibb.co/59qvf8C/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 34',
			src: 'https://i.ibb.co/Qm0dqd6/oeuvres-anciennes-34.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 35',
			src: 'https://i.ibb.co/H7CK10P/oeuvres-anciennes-35.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 36',
			src: 'https://i.ibb.co/z46mcZ4/oeuvres-anciennes-36.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 37',
			src: 'https://i.ibb.co/X458rQt/oeuvres-anciennes-37.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 38',
			src: 'https://i.ibb.co/vkNT12X/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 39',
			src: 'https://i.ibb.co/rwDPzTT/oeuvres-anciennes-39.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 40',
			src: 'https://i.ibb.co/KwrWPDN/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 41',
			src: 'https://i.ibb.co/RCHy2Mg/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'huile sur toile',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 42',
			src: 'https://i.ibb.co/SVn2Y8s/oeuvres-anciennes-42.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 43',
			src: 'https://i.ibb.co/0JdXhq4/oeuvres-anciennes-43.jpg',
			technique: 'pastel sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 44',
			src: 'https://i.ibb.co/YTkTK9X/oeuvres-anciennes-44.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 45',
			src: 'https://i.ibb.co/SvX2QSj/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 46',
			src: 'https://i.ibb.co/GPTwHjP/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 47',
			src: 'https://i.ibb.co/C9rz1vd/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 48',
			src: 'https://i.ibb.co/X2bs6mq/oeuvres-anciennes-48.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 49',
			src: 'https://i.ibb.co/dPfRqbJ/SONY-DSC.jpg" alt="SONY-DSC',
			technique: 'huile sur toile',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 50',
			src: 'https://i.ibb.co/H2Wc799/oeuvres-anciennes-50.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 51',
			src: 'https://i.ibb.co/X5gvp40/oeuvres-anciennes-51.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 52',
			src: 'https://i.ibb.co/cNsZ4XL/oeuvres-anciennes-52.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 53',
			src: 'https://i.ibb.co/zFxG8Pv/oeuvres-anciennes-53.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		},
		{
			name: 'Œuvres anciennes 54',
			src: 'https://i.ibb.co/Vg3S1sF/oeuvres-anciennes-54.jpg',
			technique: 'aquarelle sur papier',
			dimensions: ''
		}
	];
</script>

<div class="">
	{#each pics as pic}
		<Pic {pic} />
	{/each}
</div>
