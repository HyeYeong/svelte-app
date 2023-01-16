<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<script>
	/**
	 * @type {{ title: string; description: string }}
	 */
	 export let data

	 console.log(data)
</script>

<div class="text-column">
	<h1>About this app</h1>

	<p>
		{data.title}
		<br/>
		{data.description}
	</p>
</div>
