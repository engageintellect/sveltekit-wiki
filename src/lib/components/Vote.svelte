<script lang="ts">
	import ThumbsUp from 'svelte-icons/fa/FaThumbsUp.svelte';
	import ThumbsDown from 'svelte-icons/fa/FaThumbsDown.svelte';
</script>

<div
	class="w-full flex p-2 gap-2 border-[1px] border-neutral-800 items-center justify-center bg-neutral-900 rounded-lg shadow-md"
>
	<div
		class="w-full h-full uppercase group  flex items-center justify-center transition-all duration-200 rounded-lg hover:bg-green-500/20 text-center active:scale-95"
	>
		<div class="w-4 group-hover:w-5 transition-all duration-300">
			<ThumbsUp />
		</div>
	</div>

	<div
		class="uppercase group w-full h-full flex items-center justify-center rounded-lg hover:bg-red-500/20 transition-all duration-200 active:scale-95 text-center"
	>
		<div class="w-4 group-hover:w-5 transition-all duration-300">
			<ThumbsDown />
		</div>
	</div>
</div>
