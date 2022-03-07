<script context="module">
	export const prerender = true;
</script>

<script>
	import Serie from '$lib/Serie.svelte';
	import series from '$lib/series.json';

	$: console.log(series.length);
</script>

<svelte:head>
	<title>Fidon</title>
</svelte:head>

<section class="grid grid-cols-7">
	{#each series as serie}
		<div class="col-span-1 h-52">
			<Serie {serie} />
		</div>
	{/each}
	<div class="col-start-1 row-start-7 col-span-2" />

	<div
		class="col-start-2 col-span-5 row-span-4 row-start-2 text-amber-300 opacity-90 p-8 flex items-center justify-center"
	>
		<div class="space-y-3 leading-relaxed">
			<h6 class="font-bold">Jérôme Fidon : la fabrique des images</h6>
			<p>
				Au XXième siècle, Jérôme Fidon est sur une île déserte, celle d’un peintre fabricant
				d’images avec des tubes de peintures, des pinceaux, des crayons, un chevalet. Dans son
				atelier, les effluves de peinture à l’huile vous assaillent. Est-il de son temps ? La
				question peut se poser à l’entendre asséner « les peintres italiens de la Renaissance
				avaient trois règles : penser, architecturer, illustrer le sensible. Je m’applique à
				respecter ces règles. »
			</p>
			<p>
				Il s’en fiche. Il a préféré se demander si « on peut peindre des portraits après Giacometti
				ou Bacon ; des paysages après Nicolas de Staël, de la peinture abstraite après Rothko ». Et
				dresse le bilan « j’ai macéré dans mon jus pendant une bonne vingtaine d’années en
				fournissant des kilomètres d’images qui ne méritaient pas de spectateurs ». Il a des mots
				sans complaisance pour cette première période peu ou prou abstraite : nombreuses sont les
				toiles qui furent détruites alors même qu’il avait été adoubé par des critiques d’art
				reconnus.
			</p>
			<p>
				Aujourd’hui, celui qui se voit comme « un absurde clown en déséquilibre » parsème son
				univers figuratif très structuré -il a été architecte dans une vie antérieure- d’images
				empruntant à un bestiaire fourni qui contamine sa représentation des humains, notamment ses
				séries de têtes. Ses couples n’ont rien à envier à la Comédie humaine et aux figures
				grotesques du Moyen-Age. On peut imaginer, qu’à l’instar de Goya, il ouvre une boîte de
				Pandore chaque nuit. Les musées, surtout le Louvre et en Italie, seraient ouverts la nuit
				qu’il y installerait un lit de camp.
			</p>
			<p>
				Les images de ses personnages errants dans les mers et les villes en ruine, ses « Pietas »
				hiératiques et admirables de douleur, ne sont pas destinées à « charmer les ignorants » mais
				en phase avec les questionnements picturaux et existentiels d’un artiste voulant embrasser
				le passé et son époque. Car s’il convoque implicitement l’histoire de l’art et l’actualité
				dans ses images c’est pour les inscrire dans une démarche de remise en cause permanente
				quasi obsessionnelle d’un artiste acharné au travail quotidien de son métier dans son
				atelier.
			</p>

			<p>
				Pour lui, les références ne doivent pas occulter l’émotion mais la magnifier. Jérôme Fidon
				souhaite toucher un public élargi et sensible plutôt que des spécialistes et des
				théoriciens. Son écriture forte et exigeante, passe par l’humour, la dérision, la
				distanciation. La poésie aussi. Celle d’un moine soldat solitaire de la peinture, ennemi de
				toute imposture et posture dictée par le marché et les tendances.
			</p>
			<div class="opacity-80 text-sm space-y-1">
				<p>
					Brigitte Camus Artiste/Auteure/Directrice de collection :
					<a href="https://www.lelivredart.com/" class="underline hover:text-white">
						lelivredart.com
					</a>
				</p>

				<p class="">
					Dernier livre publié
					<em class="italic"> « L’abécédaire impertinent de l’art d’aujourd’hui » </em>
					avec Sophie Blachet et Georges Maisonneuve
				</p>
			</div>
		</div>
	</div>
</section>
