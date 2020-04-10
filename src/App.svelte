<script>
	import Button from './components/Button.svelte';
	export let name;

	const Hello = () => {
		name = 'Button';
	};
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>
<Button on:click={Hello}>Button</Button>
