<script lang="ts">
	export let name: string;
</script>

<main>
	<h1>Hello, I am {name}!!!</h1>
	<p>Interests: Computer Architecture and RTL design</p>
	<p>Previously: iOS App Developer, Embedded Developer</p>
	
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>