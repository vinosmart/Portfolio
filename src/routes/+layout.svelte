<script>
	import '../app.postcss';
	import Sidebar from './Sidebar.svelte';

</script>

<div class="app">
	
	<main class="flex bg-[#2F4858]/95">
		<Sidebar />
		<slot />
	</main>

	<footer>
		
	</footer>
</div>
