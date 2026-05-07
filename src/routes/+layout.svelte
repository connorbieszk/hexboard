<script>
	import { resolve } from '$app/paths';
	import favicon from '$lib/assets/favicon.svg';
	import '$lib/styles.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="navbar">
	<a
		class="button"
		href={resolve('/')}>Home</a
	>
	<a
		class="button"
		href={resolve('/scouting')}>Scouting</a
	>
	<a
		class="button-right"
		href={resolve('/admin-panel')}>Admin</a
	>
</div>

{@render children()}

<div class="footer">
	<p>&copy; 2026 Cedarburg Robotics. All Rights Reserved.</p>
</div>
