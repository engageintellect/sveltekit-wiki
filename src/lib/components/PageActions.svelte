<script class="ts">
	import Plus from 'svelte-icons/fa/FaPlus.svelte';
	import Edit from 'svelte-icons/fa/FaEdit.svelte';
	import Check from 'svelte-icons/fa/FaCheck.svelte';
	import Comment from 'svelte-icons/fa/FaComment.svelte';

	let isFollowing = false;

	const handleFollow = () => {
		isFollowing = !isFollowing;
	};
</script>

<div
	class="w-full p-2 bg-neutral-900 border-[1px] border-neutral-800 rounded-lg shadow-md flex items-center justify-center gap-2"
>
	<div
		class="w-full group h-full flex items-center justify-center active:scale-95 hover:bg-blue-400/20 tansition-all duration-300 rounded-lg"
	>
		<div class="w-4 group-hover:w-5 transition-all duration-300 active:scale-95">
			<Comment />
		</div>
	</div>

	<div
		class="w-full h-full group flex items-center justify-center active:scale-95 hover:bg-yellow-400/20 rounded-lg tansition-all duration-300"
	>
		<div class="w-4 group-hover:w-5 transition-all duration-30">
			<Edit />
		</div>
	</div>

	<button
		on:click={() => {
			handleFollow();
		}}
		class="w-full h-full flex group items-center justify-center active:scale-95 hover:bg-green-400/20 rounded-lg tansition-all duration-300"
	>
		{#if isFollowing}
			<div class="w-4 group-hover:w-5 transition-all duration-300">
				<Plus />
			</div>
		{:else}
			<div class="w-4 group-hover:w-5 transition-all duration-300">
				<Check />
			</div>
		{/if}
	</button>
</div>
