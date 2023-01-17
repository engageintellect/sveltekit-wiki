<script lang="ts">
	import SideCard from './SideCard.svelte';
	let name: string;
</script>

<div
	class="hidden lg:flex w-[33%] bg-neutral-900 hover:bg-neutral-800 transition-colors duration-500 flex-col p-4 gap-2 overflow-scroll"
>
	<div class="flex gap-2 flex-col">
		<div
			class="flex items-center justify-between p-2 bg-neutral-800 rounded-full gap-2 my-10 shadow-md"
		>
			<div class="w-10 h-10 bg-purple-700 rounded-full" />
			<div>
				<div class="capitalize">Welcome, {name || 'stranger'}!</div>
			</div>

			<div class="flex">
				<div class="p-2 bg-blue-800 rounded-full px-4">H</div>
			</div>
		</div>

		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'verified', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'verified', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'unverified', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'verified', team: 'team a' }}
		/>
		<SideCard
			data={{
				title: 'Laboris non ut do tempor ipsum fugiat.',
				date: '2021-10-10',
				status: 'verified',
				team: 'team a'
			}}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'draft', team: 'team b' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'draft', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'unverified', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'updated', team: 'team b' }}
		/>
		<SideCard
			data={{
				title: 'Laboris non ut do tempor ipsum fugiat.',
				date: '2021-10-10',
				status: 'updated',
				team: 'team b'
			}}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'verified', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'verified', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'verified', team: 'team a' }}
		/>
		<SideCard
			data={{ title: 'Hello World', date: '2021-10-10', status: 'verified', team: 'team a' }}
		/>
	</div>
</div>
