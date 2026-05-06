<script>
	// @ts-nocheck
	import Button from '$lib/Button.svelte';
	import Credit from '$lib/Credit.svelte';
	import { base } from '$app/paths';
</script>

<svelte:head>
	<title>Filip's Website</title>
</svelte:head>

<div class="fixed bottom-0 left-0 z-150 flex flex-col gap-2 p-8">
	<Button link="{base}/about" label="> About" />
	<!-- <Button link="{base}/portfolio" label="> Portfolio" /> -->
	<Button link="https://github.com/filipkristan" label="> GitHub" />
	<Button link="https://linkedin.com/in/filipkristan" label="> LinkedIn" />
</div>

<div class="fixed right-0 bottom-0 z-150 flex w-[20rem] flex-col gap-2 p-8">
	<Credit label="Made with ♥ in Slovenia." />
</div>
