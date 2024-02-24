<script>
	// Aquí puedes agregar la lógica de tu componente Svelte si es necesario
</script>

<svelte:head>
	<title>Nuestros Productos</title>
	<meta name="description" content="Descubre nuestros productos disponibles en la tienda" />
	<style>
		/* Estilos para el contenedor principal */
		.text-column {
			max-width: 800px;
			margin: 0 auto;
			padding: 20px;
			background-color: #f9f9f9;
		}

		/* Estilos para el título */
		h1 {
			text-align: center;
			font-size: 2em;
			margin-bottom: 20px;
		}

		/* Estilos para el contenido de la tarjeta */
		.card {
			border: 1px solid #ddd;
			border-radius: 5px;
			margin-bottom: 20px;
			padding: 10px;
			background-color: #fff;
			box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
			transition: transform 0.3s ease;
		}

		/* Estilos para la imagen dentro de la tarjeta */
		.card img {
			width: 100%;
			height: auto;
			border-radius: 5px;
		}

		/* Estilos para el título dentro de la tarjeta */
		.card h2 {
			text-align: center;
			margin-top: 10px;
		}

		/* Efecto de hover para las tarjetas */
		.card:hover {
			transform: translateY(-5px);
		}

		/* Estilos para el contenedor de las tarjetas */
		.card-container {
			display: grid;
			grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
			gap: 20px;
		}
	</style>
</svelte:head>

<div class="text-column">
	<h1>Productos</h1>
	<p>
		En esta sección podrás encontrar todos los productos que tenemos disponibles en nuestra tienda.
	</p>

	<div class="card-container">
		<div class="card">
			<img
				src="https://elpintoresco.es/wp-content/uploads/2022/05/patatasfritasgrandespequenas-pintoresco-500x500.jpg"
				alt="Imagen 1"
			/>
			<h2>Patatas</h2>
		</div>
		<div class="card">
			<img
				src="https://gutreigalicia.com/wp-content/uploads/2019/11/Chuleton-Buey-Roxad%E2%80%99Ouro-500x500.jpeg"
				alt="Imagen 2"
			/>
			<h2>Carnes</h2>
		</div>
		<div class="card">
			<img
				src="https://www.sugarsaltmagic.com/wp-content/uploads/2021/06/Beef-Shish-Kebabs-with-Mojo-Verde-B-6FEAT-500x500.jpg"
				alt="Imagen 3"
			/>
			<h2>Kebebabs</h2>
		</div>
		<div class="card">
			<img
				src="https://organicoasucasa.com/image/cache/catalog/productos/cod-49-500x500.jpg"
				alt="Imagen 4"
			/>
			<h2>Cebollas</h2>
		</div>
		<div class="card">
			<img
				src="https://res.cloudinary.com/riqra/image/upload/w_656,h_656,c_limit,q_auto,f_auto/v1677260275/sellers/14/ghfhmij2wk9skepmxm8z.png"
				alt="Imagen 5"
			/>
			<h2>Pimientos</h2>
		</div>
		<div class="card">
			<img
				src="https://www.elpaladar.es/server/Portal_0005448/img/products/salsa-picante-extrema-pack-4-salsas-y-especias-sierra-nevada_6793346.jpg"
				alt="Imagen 6"
			/>
			<h2>Salsas</h2>
		</div>
	</div>
</div>
