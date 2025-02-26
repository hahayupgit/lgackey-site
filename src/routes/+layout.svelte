
<script lang="ts">
	// for static site generation
	export const prerender = true;
	
	import '../app.css';
	let { children } = $props();
</script>

{@render children()}
