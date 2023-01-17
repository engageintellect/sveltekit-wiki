<script>
	import '../app.css';
	import Nav from '../lib/components/Nav.svelte';
	import Footer from '../lib/components/Footer.svelte';
	import SideNav from '../lib/components/SideNav.svelte';
</script>

<div>
	<div class="bg-neutral-900 text-neutral-300 flex max-h-screen">
		<Nav />
		<div class="flex mt-10">
			<SideNav />
			<slot />
		</div>
	</div>
</div>
