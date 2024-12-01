<script>
	export let serie;
</script>

<a class="flex h-40 lg:h-full w-full" href={serie.path}>
	<div class="relative w-full">
		<img src={serie.image} alt={serie.title} class=" h-full w-full object-cover" />
		<div
			class="absolute group top-0 h-full w-full bg-black bg-opacity-40 hover:bg-opacity-0 flex items-center justify-center text-lg text-zinc-200 hover:text-white"
		>
			<h6 class="bg-black bg-opacity-0 group-hover:opacity-0 rounded-md group-hover:shadow-lg p-4">
				{serie.title}
			</h6>
		</div>
	</div>
</a>
