<svelte:head>
	<title>Contacta</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<form>
		<label for="name">Name:</label>
		<input type="text" id="name" name="name" />

		<label for="email">Email:</label>
		<input type="email" id="email" name="email" />

		<label for="message">Message:</label>
		<textarea id="message" name="message"></textarea>

		<button type="submit">Submit</button>
	</form>
</div>

<style>
	.text-column {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		margin-top: 50px;
	}

	form {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	label {
		margin-bottom: 10px;
	}

	input,
	textarea {
		width: 300px;
		padding: 10px;
		margin-bottom: 10px;
		border: 1px solid #ccc;
		border-radius: 5px;
	}

	button {
		padding: 10px 20px;
		background-color: #007bff;
		color: #fff;
		border: none;
		border-radius: 5px;
		cursor: pointer;
	}

	button:hover {
		background-color: #0056b3;
	}
</style>
