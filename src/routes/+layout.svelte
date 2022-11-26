<script>
// @ts-nocheck

	import '../app.postcss';
	import Sidebar from './Sidebar.svelte';
	
</script>

<div class="app">
	
	<main class="  md:flex bg-[#2F4858]/95 w-full">
		<Sidebar />

		<slot />
	</main>

	<footer>
		
	</footer>
</div>
