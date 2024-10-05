<script>
	import Page from '../routes/+page.svelte';
</script>

<nav class="bg-[#3c6066] h-14">
	<div class="flex justify-between items-center">
		<h1 class="text-2xl font-bold">Questo mi manca!</h1>
		<div class="">
			<a class="hover:text-red-500" href="/">Home</a>
			<a class="hover:text-red-500" href="/collezione">Collezione</a>
			<a class="hover:text-red-500 hover:bg-red-400" href="/about">About</a>
		</div>
	</div>
</nav>

<!-- Cose da sistemare:
 distanziare gli elementi dal bordo
 centrarli verticalmente
 trovare una palette colori migliore
 dare spazio agli elementi del menù (padding)
 distanziare gli elementi del menù tra di loro (border)
-->

<!-- <style>
	nav {
		background-color: rgb(0, 0, 0);
		color: white;
		padding: 10px;
	}
	nav a:hover {
		width: 100%;
		background-color: white;
		color: black;
		padding: 2px;
		transition: 0.5s;
	}

	.container {
		display: flex;
	}
	ul {
		display: flex;
		margin: 0;
		margin-left: auto;
		list-style: none;
	}
	li {
		margin-right: 20px;
		margin-top: 5px;
	}
	h1 {
		margin: 0;
		font-size: x-large;
		font: bolder;
	}
	a {
		text-decoration: none;
		color: white;
	}
</style>
 -->
