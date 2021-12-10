<script>
	import { page } from '$app/stores';
	import Icon from '$lib/components/Icon.svelte';
	import logo from '/static/nosdev_logo_64_nobg.png';
</script>

<header class="w-full h-full flex flex-col items-center">
	<div class="">
		<a href="/">
			<h1 class="font-hand">J&rôme Fidon</h1>
		</a>
	</div>

	<nav class="h-full">
		<ul class="space-y-2 uppercase text-white-500 h-full">
			<li class="">
				<a class="" sveltekit:prefetch href="/">
					<div
						class="h-full px-4 flex items-center justifiy-center hover:text-white"
						class:text-white={$page.path === '/amour_et_mort'}
					>
						Code
					</div>
				</a>
			</li>
			<li class="">
				<a class="" sveltekit:prefetch href="/design">
					<div
						class="h-full px-4 flex items-center justifiy-center border-b border-blueGray-500 border-opacity-0 hover:text-red-700 hover:border-red-500"
						class:border-opacity-100={$page.path === '/design'}
					>
						Design
					</div>
				</a>
			</li>
			<li class="">
				<a class="" sveltekit:prefetch href="/web">
					<div
						class="h-full px-4 flex items-center justifiy-center border-b border-blueGray-500 border-opacity-0 hover:text-red-700 hover:border-red-500"
						class:border-opacity-100={$page.path === '/web'}
					>
						Web
					</div>
				</a>
			</li>
		</ul>
	</nav>

	<div class="h-10 text-blueGray-400 hover:text-white p-2">
		<a href="https://github.com/Nostrorom?tab=repositories" target="_blank">
			<Icon icon="instagram" />
		</a>
	</div>
</header>
