<script>
	export let title;
</script>


<header>
	<h1>{title}</h1>
	<nav>
		<ul>
			<li>Agenda</li>
			<li>Meld je aan</li>
		</ul>
	</nav>
</header>

<style>
	h1 {
		font-size: 2.5em;
		color: #66e5bf;
		background: #050542;
		box-shadow: -4px 4px 0px #66e5bf;
		border: solid 3px #66e5bf;
		border-radius: 9px;
		background: var(--color);
	}
	header {
		display: flex;
		align-items: center;
		justify-content: space-between;
		padding: 3em 1em;
	}

	ul {
		display: flex;
		flex-direction: row;
		gap: 1em;
	}

	li {
		text-align: center;
		background-color: #66e5bf;
		color: #050542;
		padding: 0.5em;
		border-radius: 1em;
		font-size: 1em;
	}
	ul :nth-child(2) {
		background-color: #050542;
		border: 2px solid #66e5bf;
		color: #66e5bf;
		border-radius: 1em;
	}

	@media (min-width: 45rem) {
		header {
			padding: 3em 5em;
		}
		ul {
			gap: 2em;
		}
		li {
			padding: 0.6em;
			border-radius: 2em;
			width: 7em;
		}
	}
	@media (min-width: 60rem) {
		header {
			padding: 3em 5em;
		}
		ul {
			gap: 2em;
		}
		li {
			padding: 0.6em;
			border-radius: 2em;
			width: 7em;
		}
	}
	@media (min-width: 106rem) {
		h1{
			font-size: 6em;
			padding: .1em;
		}
		li{
			font-size: 2em;
		}
	}
</style>
