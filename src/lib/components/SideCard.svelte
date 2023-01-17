<script lang="ts">
	export let data = {
		title: '',
		team: '',
		date: '',
		status: ''
	};
</script>

<a
	href="/"
	class="bg-neutral-900 rounded-md hover:bg-neutral-900 tranistion-all duration-200 p-4 hover:scale-[102%] hover:shadow-lg overflow-hidden"
>
	<div class="flex justify-between items-center">
		<div class="capitalize overflow-ellipsis flex flex-col">
			<div>
				{data.title.slice(0, 30)}
			</div>

			<div class="text-sm font-thin text-neutral-500">
				{data.team}
			</div>
			<div class="text-xs">
				{data.date}
			</div>
		</div>

		<div>
			{#if data.status === 'verified'}
				<div class="bg-green-700 rounded-full w-3 h-3 uppercase" />
			{:else if data.status === 'unverified'}
				<div class="bg-yellow-500 rounded-full w-3 h-3 uppercase" />
			{:else}
				<div class="bg-red-600 rounded-full w-3 h-3 uppercase" />
			{/if}
		</div>
	</div>
</a>
