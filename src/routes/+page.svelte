<script lang="ts">
	import CardManga from '$lib/CardManga.svelte';
	var mangas = [
		{ titolo: 'One Piece', autore: 'Eiichiro Oda', data: '22/07/1997', prezzo: '4,30' },
		{ titolo: 'cvbfgh', autore: 'hgbvm', data: 'bazv', prezzo: 'ryen' },
		{ titolo: 'Chainsaw Man', autore: 'Tatsuki Fujimoto', data: '04/03/2019', prezzo: '5,20' },
		{ titolo: 'Chainsaw Man', autore: 'Tatsuki Fujimoto', data: '04/03/2019', prezzo: '5,20' }
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
		/>
	{/each}
</div>
<!--
Compiti: Aggiungere copertine manga
         mettere tutto in una griglia
		 creare una pagina descrizione del manga
		 -->
