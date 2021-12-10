<script>
	let pics = ['DSC00010', 'DSC01106', 'DSC01108', 'DSC01113'];

	let folder = 'au_revoir_et_merci';

	let paths = [];

	$: pics.forEach((pic) => {
		paths.push(`static/${folder}/${pic}.jpg`);
	});

	console.log(paths);
</script>

{#each paths as src}
	<div class="py-4 flex justify-center">
		<img {src} alt="painting" class="h-full w-fullshadow-2xl object-contain" />
	</div>
{/each}
