<script>
	let { title = 'Default Title', entry = 'Entry Placeholder Text' } = $props();
</script>

<div class="flex grid flex-col justify-center p-2">
	<section>
		<h2>{title}</h2>
		<p>
			{entry}
		</p>
	</section>
</div>
