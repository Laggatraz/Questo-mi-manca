<script lang="ts">
	export var titolo: string = 'One Piece';
	export var autore: string = 'Eiichiro Oda';
	export var prezzo: string = '4,30';
	export var data: string = '22/07/1997';
	export var immagine: string = 'https://picsum.photos/seed/picsum/200/300';
	export var voto: string = '10/10';
</script>

<main class="pb-4">
	<div class="h-72 w-64 border-2 border-black rounded-lg flex flex-col overflow-hidden md:flex">
		<div class="bg-orange-500 h-[60%] border-b-2 border-black md:shrink">
			<img class="w-full rounded-lg md:h-auto md:w-64" src={immagine} alt="" />
		</div>
		<div class="px-2 pt-1 flex flex-col justify-between h-[40%] bg-white border-t-2 border-black">
			<div>
				<p class="text-2xl italic">{titolo}</p>
				<p>{autore}</p>
				<p class="flex justify-end">{voto}</p>
			</div>
			<div class="flex justify-between">
				<p>{data}</p>
				<p>€{prezzo}</p>
			</div>
		</div>
	</div>
</main>
