<script lang="ts">
	export let data = {
		title: '',
		author: '',
		team: '',
		tags: []
	};
</script>

<div
	class="p-10 lg:max-w-[66%] xl:max-w-[75%] 2xl:max-w-[80%] overflow-scroll flex flex-col gap-4 bg-neutral-900"
>
	<div class="my-5">
		<div class="text-5xl mb-5">{data.title || 'Page Title'}</div>

		<div class="flex gap-2">
			<div
				class="w-full flex flex-col gap-2 p-2 bg-neutral-900 rounded-lg hover:bg-neutral-800/20 shadow-md"
			>
				<div class="text-lg"><a href="/">{data.author || 'John Smith'}</a></div>
				<div class="text-md font-thin text-neutral-500">
					<a href="/">{data.team || 'Team Name'}</a>
				</div>

				<div class="flex gap-2">
					{#each data.tags || ['#hey', '#page', '#tags'] as tag}
						<div class="text-md text-blue-400 gap-2 flex"><a href="/">{tag}</a></div>
					{/each}
				</div>
			</div>
			<div class="w-full p-2 bg-neutral-900 rounded-lg shadow-md hover:bg-neutral-800/20">
				<div>yes</div>
				<div>no</div>
			</div>
			<div class="w-full p-2 bg-neutral-900 rounded-lg shadow-md hover:bg-neutral-800/20">
				hello
			</div>
		</div>
	</div>

	<div class="text-4xl semibold">Heading</div>
	<div>
		Incididunt ullamco et sit aliquip. Commodo minim nulla eiusmod nostrud aliquip excepteur ipsum
		tempor dolore sunt duis. Do enim id veniam amet proident incididunt tempor ipsum ad. Id laboris
		officia nulla laboris anim enim et et sunt. Deserunt sit excepteur amet deserunt aliqua amet
		cillum ex reprehenderit. Nostrud labore nulla sint veniam ut. Et consectetur eiusmod ut laboris
		Lorem proident amet nulla est. Voluptate qui consectetur culpa laborum amet. Ad labore
		adipisicing tempor qui Lorem officia deserunt consequat. Sunt officia Lorem cupidatat incididunt
		tempor. Sunt ea ut laboris tempor id ullamco voluptate. Ullamco nostrud eiusmod nostrud amet ad
		tempor qui aliqua consectetur do do pariatur. Anim amet consequat deserunt veniam est eu eiusmod
		enim. Culpa commodo magna cupidatat pariatur. Adipisicing ea ex eu labore ullamco incididunt
		anim laboris ipsum esse duis pariatur. Ut commodo et enim aute quis qui sint. Minim officia
		ullamco est enim incididunt laborum incididunt ullamco aliqua Lorem ea enim. Mollit enim tempor
		id minim magna. Sunt aliqua minim nisi officia nostrud in enim ipsum tempor mollit est duis eu.
		Proident fugiat laboris qui reprehenderit tempor aliquip nisi officia ad non occaecat quis est.
		Dolor do deserunt ad fugiat sit laborum nulla culpa commodo anim do. Incididunt est adipisicing
		eu ipsum eiusmod mollit duis fugiat proident enim dolor cupidatat officia minim. Incididunt
		consequat excepteur
	</div>

	<div class="text-3xl semibold">Heading 2</div>
	<div>
		voluptate ut Lorem ipsum ipsum ipsum nulla dolore elit. Ipsum proident aute incididunt esse
		magna magna nostrud aliquip. Ullamco voluptate eiusmod occaecat et nulla eiusmod excepteur.
		Dolore incididunt deserunt quis aute proident cillum. Sit proident eiusmod aute amet culpa qui
		nulla cillum voluptate. Dolor laboris irure tempor incididunt ea ullamco. Reprehenderit enim non
		ex occaecat. Irure ad exercitation et culpa laborum dolore excepteur sit voluptate. Ex sint
		occaecat velit sint pariatur commodo veniam. Commodo ipsum dolor ullamco duis exercitation
		tempor dolore sunt duis. Do enim id veniam amet proident incididunt tempor ipsum ad. Id laboris
		officia nulla laboris anim enim et et sunt. Deserunt sit excepteur amet deserunt aliqua amet
		cillum ex reprehenderit. Nostrud labore nulla sint veniam ut. Et consectetur eiusmod ut laboris
	</div>

	<div class="text-3xl semibold">Heading 2</div>
	<div>
		Lorem proident amet nulla est. Voluptate qui consectetur culpa laborum amet. Ad labore
		adipisicing tempor qui Lorem officia deserunt consequat. Sunt officia Lorem cupidatat incididunt
		tempor. Sunt ea ut laboris tempor id ullamco voluptate. Ullamco nostrud eiusmod nostrud amet ad
		tempor qui aliqua consectetur do do pariatur. Anim amet consequat deserunt veniam est eu eiusmod
		enim. Culpa commodo magna cupidatat pariatur. Adipisicing ea ex eu labore ullamco incididunt
		anim laboris ipsum esse duis pariatur. Ut commodo et enim aute quis qui sint. Minim officia amet
		deserunt aliqua amet cillum ex reprehenderit. Nostrud labore nulla sint veniam ut. Et
		consectetur eiusmod ut laboris Lorem proident amet nulla est. Voluptate qui consectetur culpa
		laborum amet. Ad labore adipisicing tempor qui Lorem officia deserunt consequat. Sunt officia
		Lorem cupidatat incididunt tempor. Sunt ea ut laboris tempor id ullamco voluptate. Ullamco
		nostrud eiusmod nostrud amet ad tempor qui
	</div>

	<div class="text-2xl semibold">Heading 3</div>
	<div>
		aliqua consectetur do do pariatur. Anim amet consequat deserunt veniam est eu eiusmod enim.
		adipisicing reprehenderit esse ut nisi quis ad. Consequat non laborum minim cupidatat qui. Duis
		amet fugiat non nostrud nostrud quis nisi. Aliqua voluptate anim quis amet anim occaecat et anim
		qui incididunt. Non enim qui excepteur laborum voluptate duis magna ipsum ad cupidatat. Deserunt
	</div>

	<div class="text-2xl semibold">Heading 3</div>
	<div>
		aliqua consectetur do do pariatur. Anim amet consequat deserunt veniam est eu eiusmod enim.
		adipisicing reprehenderit esse ut nisi quis ad. Consequat non laborum minim cupidatat qui. Duis
		amet fugiat non nostrud nostrud quis nisi. Aliqua voluptate anim quis amet anim occaecat et anim
		qui incididunt. Non enim qui excepteur laborum voluptate duis magna ipsum ad cupidatat. Deserunt
	</div>

	<div>
		labore mollit commodo magna aliqua elit fugiat sint proident ipsum sint. Eu ex ea duis commodo
		aute exercitation. Veniam laboris id cupidatat fugiat aute deserunt laboris cillum elit do et
		sint. Esse in laborum dolor sint duis. Exercitation fugiat laborum qui id exercitation Lorem
		mollit ut. Do excepteur ipsum ea laborum commodo mollit id officia dolore aliqua magna ex sunt.
		Irure incididunt labore voluptate exercitation occaecat eu. Sunt sunt aliquip elit esse id
		deserunt eiusmod. Nisi tempor in excepteur id. Lorem laborum elit commodo ex esse officia in
		veniam dolor minim sit. Magna labore ullamco exercitation ipsum veniam exercitation eiusmod
		cupidatat irure. Sint qui officia officia non mollit anim culpa culpa consectetur id proident
		eiusmod adipisicing. Cillum sunt deserunt dolor minim do reprehenderit proident cupidatat aliqua
		quis. Exercitation culpa sit tempor exercitation enim consequat pariatur non deserunt ad aliquip
		Lorem sint. Aliqua aliquip commodo officia adipisicing laboris fugiat consectetur ex sint
		aliqua. Tempor non consectetur fugiat deserunt qui ullamco velit dolor elit quis eiusmod. Labore
		velit dolor tempor ea labore reprehenderit irure aliqua. Deserunt aute proident proident esse
		consequat. Proident aute velit exercitation consectetur nisi do labore quis et in amet dolor
		velit.
	</div>
</div>
