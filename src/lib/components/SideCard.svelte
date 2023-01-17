<script lang="ts">
	export let data = {
		title: '',
		date: '',
		status: ''
	};
</script>

<div
	class="bg-neutral-900 rounded-md hover:bg-neutral-800 tranistion-all duration-200 p-4 hover:scale-[102%] hover:shadow-lg overflow-hidden"
>
	<div class="flex justify-between items-center">
		<div class="capitalize overflow-ellipsis">
			{data.title.slice(0, 30)}
		</div>

		<div class="">
			{#if data.status === 'new'}
				<div class="bg-green-700 rounded-lg px-2 uppercase">
					{data.status}
				</div>
			{:else if data.status === 'updated'}
				<div class="bg-yellow-600 rounded-lg px-2 uppercase">
					{data.status}
				</div>
			{:else}
				<div class="bg-red-700 rounded-lg px-2 uppercase">
					{data.status}
				</div>
			{/if}
		</div>
	</div>
</div>
