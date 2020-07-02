<svelte:head>
	<link rel="stylesheet" href="./dark-theme.css">
	<title>Data Table - SMUI</title>
</svelte:head>

<h2>Data Table H2</h2>

<h1>Hello world! Test here</h1>

<script>
	let name = '';
	import RssFeed from './RssFeed.svelte';
</script>

<input bind:value={name} placeholder="enter your name">
<p>Hello {name || 'stranger'}!</p>
<hr>

<RssFeed />