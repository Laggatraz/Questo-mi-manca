<nav>
	<div class="container">
		<h1>Questo mi manca!</h1>
		<ul>
			<li>
				<a href="/">Home</a>
			</li>
			<li>
				<a href="/Collezione">Collezione</a>
			</li>
			<li>
				<a href="/Librearia">Librearia</a>
			</li>
		</ul>
	</div>
</nav>
<slot />

<style>
	nav {
		background-color: rgb(0, 0, 0);
		color: white;
		padding: 10px;
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
