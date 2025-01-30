<script>
	let world = $state('world');

	function onclick(event) {
		world = 'svelte';
	}
</script>

<h1>Hello <span>{world}</span></h1>
<button {onclick}>Change!</button>

<style>
	h1 {
		font-family: 'Courier New', Courier, monospace;
	}

	span {
		color: red;
	}
</style>
