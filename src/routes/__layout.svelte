<script>
	import Header from '$lib/Sidebar.svelte';
	import '../app.css';
	import '@fontsource/zeyada';
</script>

<svelte:head>
	<meta charset="UTF-8" />
	<meta
		name="description"
		content="Les oeuvres de Jérôme Fidon, peintre. Plusieurs années de travail regroupées en séries thématiques."
	/>
	<meta name="keywords" content="peinture painting art jerome fidon" />
	<meta name="author" content="Nos Dev" />
	<script async src="https://www.googletagmanager.com/gtag/js?id=G-MJLZJK1YY9"></script>
	<script>
		window.dataLayer = window.dataLayer || [];
		function gtag() {
			dataLayer.push(arguments);
		}
		gtag('js', new Date());

		gtag('config', 'G-MJLZJK1YY9');
	</script>
</svelte:head>
<main class="w-full min-h-screen bg-zinc-800  from-zinc-700 to-zinc-700 via-zinc-700 z-0 flex">
	<div class="h-full hidden lg:block fixed left-0 w-1/6 z-0">
		<div class="h-full">
			<Header />
		</div>
	</div>

	<div class="lg:w-5/6 ml-auto h-full">
		<slot />
	</div>
</main>
