<script class="ts">
	import Plus from 'svelte-icons/fa/FaPlus.svelte';
</script>

<div class="bg-neutral-900 fixed w-full p-2 px-4 shadow-md z-50">
	<div class="flex justify-center items-center gap-2">
		<a
			href="/"
			class="mr-auto py-2 px-4 bg-blue-800 hover:bg-blue-900 transition-all duration-200 rounded-lg flex justify-center text-lg font-semibold"
		>
			Wiki Platform
		</a>

		<div class="flex gap-2 items-center justify-center w-96">
			<input
				type="text"
				placeholder="Search"
				class="rounded-lg pl-4 p-2	bg-neutral-800 focus:bg-neutral-700 transition-colors duration-200 focus:outline-none md:w-full"
			/>

			<button
				class="bg-blue-800 rounded-lg px-4 py-2 hover:bg-blue-900 tranistion-all duration-200 h-full"
			>
				<div class="w-4 h-full">
					<Plus />
				</div>
			</button>
		</div>
		<div
			class="ml-auto w-8 h-8 bg-gradient-to-r from-blue-700 to-purple-700 hover:bg-blue-900 rounded-full hover:from-blue-500 hover:to-purple-700 shadow-lg cursor-pointer transition-all duration-500"
		/>
	</div>
</div>
