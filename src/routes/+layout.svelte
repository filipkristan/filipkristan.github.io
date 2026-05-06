<script>
	import favicon from '$lib/assets/leaves.png';
	import Background from '$lib/Background.svelte';
	import '../app.css';
	let { children } = $props();
</script>

<Background />
<svelte:head>
	<title>Welcome</title>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}
