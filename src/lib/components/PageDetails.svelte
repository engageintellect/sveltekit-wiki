<script class="ts">
	export let data = {
		title: '',
		author: '',
		team: '',
		tags: []
	};
</script>

<div
	class="w-full flex flex-col p-2 border-[1px] border-neutral-800 bg-neutral-900 rounded-lg hover:bg-neutral-800/20 shadow-md"
>
	<div class="text-sm semibold"><a href="/">{data.author || 'John Smith'}</a></div>
	<div class="text-sm font-thin text-neutral-500">
		<a href="/">{data.team || 'Team Name'}</a>
	</div>

	<div class="flex gap-2">
		{#each data.tags || ['#hey', '#page', '#tags'] as tag}
			<div class="text-sm text-blue-400 gap-2 flex"><a href="/">{tag}</a></div>
		{/each}
	</div>
</div>
