<script>
	import Navbar from "../components/shared/Navbar.svelte";
	import Sidebar from "../components/shared/Sidebar.svelte";

</script>

<Navbar />

<div class="d-flex min-vh-100">
	<aside>
		<Sidebar />
	</aside>

	<main class="flex-grow-1">
		<slot />
	</main>

	<aside>

	</aside>
</div>
