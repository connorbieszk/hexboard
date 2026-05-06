<script>
	import favicon from '$lib/assets/favicon.svg';
	import "$lib/styles.css";
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="navbar">
	<a class="button" href="/">Home</a>
	<a class="button" href="/scouting">Scouting</a>
	<!-- <a class="button" href="/data-viewer">Data</a>
	<a class="button" href="/member-dash">Member Dashboard</a> -->

	<a class="button-right" href="/admin-panel">Admin</a>

</div>

{@render children()}

<div class="footer">
	<p>&copy; 2026 Cedarburg Robotics. All Rights Reserved.</p>
</div>

