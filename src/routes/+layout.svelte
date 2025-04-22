<script>
	import Sidebar from '$lib/Sidebar.svelte';
	import '../app.css';
	export let data;
  </script>
  
  <div class="flex h-screen bg-gray-100 font-sans">
	<!-- Sidebar -->
	<Sidebar />
  
	<!-- Main Content -->
	<main class="flex-1 p-10 overflow-y-auto">
	  <slot />
	</main>
  </div>
  