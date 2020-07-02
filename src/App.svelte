<h2>Data Table</h2>

<svelte:head>
	<link rel="stylesheet" href="./dark-theme.css">
	<title>Data Table - SMUI</title>
</svelte:head>

<h1>Hello world! Test here</h1>

<script>
	let name = '';
</script>

<input bind:value={name} placeholder="enter your name">
<p>Hello {name || 'stranger'}!</p>