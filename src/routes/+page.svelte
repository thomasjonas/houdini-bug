<script lang="ts">
	import { type PageData } from './$houdini';

	export let data: PageData;

	$: ({ ExampleQuery } = data);

	console.log(ExampleQuery);
</script>

<div>
	<h1>Welcome to SvelteKit</h1>
	<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</div>
