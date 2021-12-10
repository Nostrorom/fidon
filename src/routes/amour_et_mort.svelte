<script>
	let pics = ['DSC00099', 'DSC08532', 'DSC08534', 'DSC08532'];

	let folder = 'amour_et_mort';

	let paths = [];

	$: pics.forEach((pic) => {
		paths.push(`static/${folder}/${pic}.jpg`);
	});

	console.log(paths);
</script>

{#each paths as src}
	<div class="h-screen py-4 flex justify-center">
		<img {src} alt="painting" class="h-full shadow-2xl" />
	</div>
{/each}
