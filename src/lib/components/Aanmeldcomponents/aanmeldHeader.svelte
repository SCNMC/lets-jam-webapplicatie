<script>
	export let title;
</script>


<header>
	<h1>{title}</h1>
	<nav>
		<ul>
			<li>Homepagina</li>
			<li>Agenda</li>
		</ul>
	</nav>
</header>

<style>
	h1 {
		font-size: 2.5em;
		color: white;
		background: #050542;
		box-shadow: -4px 4px 0px #a675f5;
		border: solid 3px #a675f5;
		border-radius: 9px;
        padding: .1em;
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
		background-color: #050542;
        border:  solid 2px #a675f5;
		color: white;
		padding: 0.5em;
		border-radius: 1em;
		font-size: 1em;
	}
	ul :nth-child(2) {
		background-color: #050542;
		color: white;
		border-radius: 1em;
	}

	@media (min-width: 45rem) {
		header {
			padding: 3em 2em;
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
			padding: 2.5em 5em;
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
</style>