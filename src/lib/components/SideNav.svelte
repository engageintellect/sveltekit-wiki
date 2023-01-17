<script>
	import SideCard from './SideCard.svelte';
</script>

<div
	class="hidden md:flex w-[33%] bg-neutral-900 hover:bg-neutral-700 transition-colors duration-500 flex-col p-4 gap-2 overflow-scroll"
>
	<div class="flex gap-2 flex-col">
		<div class="flex items-center p-2 bg-neutral-800 rounded-full gap-2 my-10">
			<div class="w-10 h-10 bg-purple-700 rounded-full" />
			<div>
				<div>Name</div>
				<div>Status</div>
			</div>
		</div>

		<SideCard
			data={{
				title:
					'Tempor est dolor excepteur elit id aliquip enim reprehenderit aliquip nisi voluptate consequat.',
				status: 'updated',
				date: 'age'
			}}
		/>
		<SideCard
			data={{
				title: 'hey',
				status: 'updated',
				date: 'age'
			}}
		/>
		<SideCard
			data={{
				title: 'hey',
				status: 'new',
				date: 'age'
			}}
		/>
		<SideCard
			data={{
				title: 'hey',
				status: 'new',
				date: 'age'
			}}
		/>
		<SideCard
			data={{
				title: 'hey',
				status: 'new',
				date: 'age'
			}}
		/>
		<SideCard
			data={{
				title: 'hey',
				status: 'new',
				date: 'age'
			}}
		/>
		<SideCard
			data={{
				title: 'hey',
				status: 'name',
				date: 'age'
			}}
		/>
	</div>
</div>
