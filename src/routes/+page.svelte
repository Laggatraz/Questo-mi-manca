<script lang="ts">
	import CardManga from '$lib/CardManga.svelte';
	var mangas = [
		{
			titolo: 'One Piece',
			autore: 'Eiichiro Oda',
			data: '22/07/1997',
			prezzo: '4,30',
			immagine: '81hipaenXVL.jpg',
			voto: '5/10'
		},
		{
			titolo: 'Jujutsu Kaisen',
			autore: 'Gege Akutami',
			data: '04/06/2018',
			prezzo: '4,50',
			immagine: 'jjk.jpg',
			voto: '9/10'
		},
		{
			titolo: 'Chainsaw Man',
			autore: 'Tatsuki Fujimoto',
			data: '04/03/2019',
			prezzo: '5,20',
			immagine: '71xceC0p1cL._AC_UF1000,1000_QL80_.jpg',
			voto: '10/10'
		},
		{
			titolo: 'Berserk Collection',
			autore: 'Kentaro Miura',
			data: '25/07/1989',
			prezzo: '5,50',
			immagine: 'Berserk.jpg',
			voto: '10/10'
		}
	];
</script>

<h1 class="text-3xl text-center uppercase">Benvenuti!</h1>

<div class="p-16 grid grid-cols-4 gap-52">
	{#each mangas as manga}
		<CardManga
			titolo={manga.titolo}
			autore={manga.autore}
			data={manga.data}
			prezzo={manga.prezzo}
			immagine={manga.immagine}
			voto={manga.voto}
		/>
	{/each}
</div>
<!--
Compiti: V Aggiungere copertine manga
         mettere tutto in una griglia
		 creare una pagina descrizione del manga
		 V aggiungere una variabile ranking
		 -->
