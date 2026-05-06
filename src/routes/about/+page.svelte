<script>
	import Post from '$lib/Post.svelte';
	import Credit from '$lib/Credit.svelte';
</script>

<svelte:head>
	<title>About Filip</title>
</svelte:head>
<Post title="About Filip:" entry="Filip is a Slovenian Software Developer." />

<div class="fixed right-0 bottom-0 z-150 flex w-[20rem] flex-col gap-2 p-8">
	<Credit label="Made with ♥ in Slovenia." />
</div>
