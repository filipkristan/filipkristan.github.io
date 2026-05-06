<script>
	let { label = 'Default Text', link = '' } = $props();
</script>

<button
	class="border-text flex w-full transform cursor-pointer items-center
  justify-center rounded-sm border-t-0 border-r-0 border-b-0 p-2 px-2 py-3 text-sm leading-6 font-bold text-white capitalize
  duration-100 sm:px-8"
>
	{label}
</button>
