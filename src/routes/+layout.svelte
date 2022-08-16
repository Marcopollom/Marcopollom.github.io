<script>
	import '../app.css';

	// redirect user to main page if they visit any other page
	import { page } from '$app/stores';
	import { redirect } from '@sveltejs/kit';
	import { onMount } from 'svelte';
</script>

<slot />
