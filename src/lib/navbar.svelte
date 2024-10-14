<script>
	import Page from '../routes/+page.svelte';
</script>

<nav class="bg-[#173753] h-14 border-t-8 border-[#173753] border-x-8 text-white font-serif">
	<div class="flex justify-between items-center mx-8">
		<h1 class="text-2xl font-bold">Questo mi manca!</h1>
		<div class="flex space-x-12 transition">
			<a
				class="hover:text-white hover:bg-cyan-700 transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 duration-300 rounded-tl-lg rounded-br-lg border-none border-2 px-2"
				href="/">Home</a
			>
			<a
				class="hover:text-white hover:bg-cyan-700 transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 duration-300 rounded-tl-lg rounded-br-lg border-none border-2 px-2"
				href="/collezione">Collezione</a
			>
			<a
				class="hover:text-white hover:bg-cyan-700 transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110 duration-300 rounded-tl-lg rounded-br-lg border-none border-2 px-2"
				href="/about">About</a
			>
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
