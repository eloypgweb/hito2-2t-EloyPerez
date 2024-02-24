<script>
	let name = 'Marilu';
	let age = 25;
	let email = 'Marilu666@marilu.com';
</script>

<svelte:head>
	<title>Mi Perfil</title>
	<meta name="description" content="Mi perfil de usuario" />
	<style>
		/* Estilos para el contenedor principal */
		.text-column {
			margin: 0 auto;
			width: 300px;
			padding: 20px;
			background-color: #f9f9f9;
			border-radius: 20px;
			box-shadow: 0 30px 30px rgba(0, 0, 0, 0.2);
		}

		/* Estilos para el título */
		h1 {
			text-align: center;
			margin-bottom: 20px;
		}

		/* Estilos para los párrafos */
		p {
			margin-bottom: 10px;
		}

		/* Estilos para los datos del perfil */
		.data {
			font-weight: bold;
		}
	</style>
</svelte:head>

<div class="text-column" style="text-align: center;">
	<h1 style="margin-top: -40px;">Mi Perfil</h1>
	<p><span class="data">Nombre:</span> {name}</p>
	<p><span class="data">Edad:</span> {age}</p>
	<p><span class="data">Email:</span> {email}</p>
</div>
