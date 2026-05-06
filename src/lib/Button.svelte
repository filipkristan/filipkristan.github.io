<script>
	let { label = 'Default Text', link = '' } = $props();
</script>

<div class="">
	<a
		class="focus:ring-opacity-50 border-text flex h-25 w-80 transform cursor-pointer items-center rounded-sm border-7
        border-t-1 border-r-1 border-b-1 bg-white/10 py-3 font-mono text-sm text-[24px] leading-6 text-white duration-100 hover:-translate-y-1 hover:border-green-300 hover:bg-white/15 hover:shadow-lg focus:ring-4 sm:pl-5"
		href={link}>{label}</a
	>
</div>
