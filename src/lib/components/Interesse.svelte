<script>
	import Instruction from "./instruction.svelte";
</script>

<section>
	<p>INTERESSE?</p>
	<Instruction />
</section>

<style>
	section {
		padding: 3em 1em;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		min-height: 100vh;
		gap: 10em;
		background-color: #050542;
		color: #66e5bf;
	}
	p {
		font-size: 3.5em;
		font-weight: bold;
	}

	@media (min-width: 60rem) {
		p {
			font-size: 5em;
		}
		section {
			margin: 3em;
		}
	}
</style>
